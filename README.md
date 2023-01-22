# appsyncmasterclass-backend

Backend for appsync masterclass demo app

# Deploy serverless stack

$ npm run sls -- deploy

# Export environment variables from provider environment

$ npm run sls -- export-env

# Export environment variables for specific function

$ npm run sls -- export-env --function confirmUserSignup --filename **tests**/test_cases/integration/confirm-user-signup/.env

# Export outputs from cloudformation stack

$ npm run sls -- manifest

# generate cloudformation stacks

$ npm run sls -- package
