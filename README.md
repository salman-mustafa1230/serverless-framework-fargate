# serverless framework ecs fargate

This yml file will provision the ECS fargate on amazon server using serverless framework. It is using serverless-fargate-tasks plugin.

### Prerequisites

If you dont have serverless framework please install it

```
npm i -g serverless
```

install [serverless-fargate-tasks](https://www.npmjs.com/package/serverless-fargate-tasks) plugin

```
npm i -D serverless-fargate-tasks
```

## Deployment

Simply run serverless framework deploy command

```
sls deploy
```
