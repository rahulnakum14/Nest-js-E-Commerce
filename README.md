# For run programme

npm start dev

## Nest Js clean Architecture With Rest API
```
nestjs-clean-architecture/
├── src/
│   ├── application/
│   │   ├── services/
│   │   │   ├── user.service.ts
│   │   ├── use-cases/
│   │       ├── create-user.use-case.ts
│   │       ├── get-user.use-case.ts
│   ├── domain/
│   │   ├── entities/
│   │   │   ├── user.entity.ts
│   │   ├── repositories/
│   │       ├── user.repository.ts
│   ├── infrastructure/
│   │   ├── database/
│   │   │   ├── user.schema.ts
│   │   │   ├── user.repository.impl.ts
│   │   ├── controllers/
│   │       ├── user.controller.ts
│   │   ├── config/
│   │       ├── app.module.ts
│   │       ├── database.module.ts
│   ├── shared/
│       ├── dto/
│       │   ├── create-user.dto.ts
│       ├── interfaces/
│           ├── user.interface.ts
├── test/
├── .env
├── .gitignore
├── package.json
├── tsconfig.json
```
