# End to end testing a microservice with Cypress.

First you must boot the microservices application:

```bash
docker-compose up --build
```

Now install dependencies for testing:

```bash
cd project_folder
npm install
```

Then run headless Cypress tests:

```bash
npm test
```

Or to show the Cypress UI:

```bash
npm run test:watch
```
