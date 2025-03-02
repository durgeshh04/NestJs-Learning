## NestJS Tutorial

This repository contains a comprehensive NestJS tutorial to help you get started with building scalable Node.js applications.

## Prerequisites
- Node.js (v14 or later)
- npm (v6 or later)

## Getting Started

### Installation
First, install the NestJS CLI globally:
```bash
npm i -g @nestjs/cli
```

### Create a new project
```bash
nest new project-name
```

### Running the app
```bash
# development mode
npm run start

# watch mode
npm run start:dev

# production mode
npm run start:prod
```

### Testing
```bash
# unit tests
npm run test

# e2e tests
npm run test:e2e

# test coverage
npm run test:cov
```

## Project Structure
```
src/
├── app.controller.ts
├── app.module.ts
├── app.service.ts
└── main.ts
```

## Key Concepts Covered
- Controllers
- Providers
- Modules
- Middleware
- Exception filters
- Pipes
- Guards
- Interceptors
- Custom decorators
- Database integration
- Authentication
- Authorization
- Validation
- Error handling
- Testing


## For example download:
## To create module
```bash
nest g module users
```
## To create controller
```bash
nest g controller users
```
## To create service
```bash
nest g service users
```

## Additional Resources
- [NestJS Official Documentation](https://docs.nestjs.com)
- [NestJS GitHub Repository](https://github.com/nestjs/nest)
- [NestJS Discord Community](https://discord.gg/nestjs)

## Contributing
Feel free to submit issues, fork the repository and create pull requests for any improvements.

## License
This project is licensed under the MIT License - see the LICENSE file for details.