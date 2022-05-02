# sam-playground

A project to play around with AWS SAM CLI

## Build project

```
  npm run build
```

## Deploy project

```
  npm run deploy
```

## Sync execution

This command will allow you to run a Lambda function on the Cloud and having its console locally

```
  npm run sync
```

## Logs

This command should be used in pair with `npm run sync`. It will tail the latest logs from Cloudwatch and display them in your terminal window.

```
  npm run logs
```
