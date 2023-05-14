# piggy docs

How to clone this repo.
1. If you have no token yet - go [here](https://github.com/settings/tokens?type=classic) and generate a token
2. During `git clone` paste your token as a password

How to do a DB migration (after adding/removing/changing any fields or tables).
[prisma docs](https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases-typescript-postgres)
1. Make changes to `schema.prisma` file
2. `npx prisma migrate dev --name [comment]`
