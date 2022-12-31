# Project AWS Lambda Hero Trigger Dynamo

### Config Dashboad

```
sls
```

### Deployment

```
sls deploy
```

### Watch trigger

```bash
sls logs -f hero-trigger -t 
```

### Invocation

After successful deployment, you can invoke the deployed function by using the following command:

```bash
npm run invoke
```

Which should result in response similar to the following:

```json
{
    "statusCode": 200,
    "body": "{\"nome\":\"Batman\",\"poder\":\"Força\",\"id\":\"8b2684e0-88bc-11ed-833a-cfaf34b1ccd7\",\"createdAt\":\"2022-12-31T03:38:08.814Z\"}"
}
```

### Local development

You can invoke your function locally by using the following command:

```bash
npm run invoke-local
```

Which should result in response similar to the following:

```
{
    "statusCode": 200,
    "body": "{\"nome\":\"Batman\",\"poder\":\"Força\",\"id\":\"8b2684e0-88bc-11ed-833a-cfaf34b1ccd7\",\"createdAt\":\"2022-12-31T03:38:08.814Z\"}"
}
```
