# piggy docs

How to clone this repo.
1. If you have no token yet - go [here](https://github.com/settings/tokens?type=classic) and generate a token
2. During `git clone` paste your token as a password

Currently this repo includes: 
- Image generation backend from [this repo](https://github.com/AbdBarho/stable-diffusion-webui-docker)
Will be added soon:
- Router backend
- DB
- Frontend

How to run the stack:
1. Install Docker
2. `docker compose --profile auto up --build`

How to do a DB migration (after adding/removing/changing any fields or tables).
[prisma docs](https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases-typescript-postgres)
1. Make changes to `schema.prisma` file
2. `npx prisma migrate dev --name [comment]`
