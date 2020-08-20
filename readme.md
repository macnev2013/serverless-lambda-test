# Serverless - Lambda Deployment

### Compilation instructions:

Install all the npm dependancies

```sh
$ npm install
```

Run serverless deployment on localstack
```sh
export AWS_ACCESS_KEY_ID=NONE_FOR_LOCAL
export AWS_SECRET_ACCESS_KEY=NONE_FOR_LOCAL
serverless deploy --stage local
```