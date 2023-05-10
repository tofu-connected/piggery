# piggy docs

How to do a DB migration (after adding/removing/changing any fields or tables).
[prisma docs](https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases-typescript-postgres)
1. Make changes to `schema.prisma` file
2. `npx prisma migrate dev --name [comment]`
