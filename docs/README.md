# Documentation

This docs section will include documentation relevant to understand how Serverless works.

You may want to start with the [concepts](/docs/concepts) of Serverless to understand the how Serverless is architected and works behind
the scenes.

After that you should take a look at the different [plugins](/docs/plugins) which are used to deliver the functionality
Serverless provides (such as service creation, deployment, removal, function invocation etc.).

## Table of contents

- Concepts
  - [plugins](/docs/concepts/plugins.md) - How plugins work
  - [services](/docs/concepts/services.md) - Understanding Serverless services
- Plugins
  - Core plugins
    - [create](/docs/plugins/core/create.md) - Creates a new Serverless service
    - [deploy](/docs/plugins/core/deploy.md) - Deploy your resources to your provider
    - [invoke](/docs/plugins/core/invoke.md) - Invoke your function
    - [remove](/docs/plugins/core/remove.md) - Remove a deployed service
  - AWS plugins
    - [awsCompileFunctions](/docs/plugins/aws/awsCompileFunctions.md) - Compiles the functions to CloudFormation resources
    - [awsCompileS3Events](/docs/plugins/aws/awsCompileS3Events.md) - Compiles the S3 events to CloudFormation resources
    - [awsCompileScheduledEvents](/docs/plugins/aws/awsCompileScheduledEvents.md) - Compiles the Scheduled events to CloudFormation resources
