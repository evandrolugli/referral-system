# Referral System
Referral System: users register, refer others, earn points, and rank up.

# technologies:
- full api rest
- swagger (documentation)
- fastify
- zod (validation)
- postgres (db) : structure data, subscriptions
- redis (db) : ranking, and clicks counts (hashes, sort sets functionalities)
- docker

# installations:
    > npm init -y
    > npm i fastify
    > npm i tsx typescript @types/node -D
    > npx tsc --init (tsconfig.json)
        https://github.com/tsconfig/bases
        Node v22: copy and paste “tsconfig” configuration
    > npm i @fastify/cors
    > npm i fustily-type-provider-zod
    > npm i @fastify/swagger @fastify/swagger-ui
    > npm i @biomejs/biome -D

    > npm i ioredis
    > npm i postgres drizzle-orm
    > npm i drizzle-kit -d
    > npx drizzle-kit generate (create sql)
    > npx drizzle-kit migrate (execute on database)

# notes:
- env.ts (to validate file .env)


Biome (like prittier, etc…)
- Install the extension - Biome
- biome.json (config file)
- CMD + Shift + P : Preferences: Open Workspace Settings (only the current project)
- CMD + Shift + P : Reload Window

