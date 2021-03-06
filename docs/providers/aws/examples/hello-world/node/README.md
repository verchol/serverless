<!--
title: Hello World AWS Lambda Node Example
menuText: Hello World Node Example
description: Create a nodeJS Lambda function on amazon web services
layout: Doc
-->

<!-- DOCS-SITE-LINK:START automatically generated  -->
### [Read this on the main serverless docs site](https://www.serverless.com/framework/docs/providers/aws/examples/hello-world/node/)
<!-- DOCS-SITE-LINK:END -->

# Hello World Node.js

Make sure serverless is installed. [See installation guide](/framework/docs/providers/aws/guide/installation/)

## 1. Deploy

`serverless deploy` or `sls deploy`. `sls` is shorthand for the serverless CLI command

## 2. Invoke the remote function

`serverless invoke --function hello` or `serverless invoke -f hello`

`-f` is shorthand for `--function`

In your terminal window you should be the response from AWS Lambda

```bash
{
  "message": "Hello World",
  "event": {}
}
```

Congrats you have just deployed and ran your hello world function!
