# Welcome to Mic-base
## description
That microservice was made to be the template-base to microservices

## Frameworks used

### Serverless Framework AWS NodeJS

### Local development

You can invoke your function locally by using the following command:

```bash
serverless invoke local --function hello

iniciar projeto -> git clone https://github.com/jerfsonsilva/mic-base.git

gerar variaveis AWS e configurar maquina

serveless

https://www.serverless.com/framework/docs/getting-started

npm install -g serverless

serveless

serverless invoke -f hello -l

serveless deploy

serverless config credentials --provider aws --key KEY --secret SECRET

to test local:
mic-base serverless invoke --function hello --path mock/http/input.json

serverless invoke --function optimize --path mock/s3/optimize.json


https://www.serverless.com/plugins/serverless-localstack

localstack start --docker -d -> after config, to apply configs in start to do it into a container

to test local
docker-compose up -> http://localhost:4566/health


serverless deploy --stage local
serverless deploy --stage production
```

