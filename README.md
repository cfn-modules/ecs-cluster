[![Build Status](https://travis-ci.org/cfn-modules/ecs-cluster.svg?branch=master)](https://travis-ci.org/cfn-modules/ecs-cluster)
[![NPM version](https://img.shields.io/npm/v/@cfn-modules/ecs-cluster.svg)](https://www.npmjs.com/package/@cfn-modules/ecs-cluster)

# cfn-modules: ECS cluster

ECS cluster.

## Install

> Install [Node.js and npm](https://nodejs.org/) first!

```
npm i @cfn-modules/ecs-cluster
```

## Usage

```
---
AWSTemplateFormatVersion: '2010-09-09'
Description: 'cfn-modules example'
Resources:
  Cluster:
    Type: 'AWS::CloudFormation::Stack'
    Properties:
      TemplateURL: './node_modules/@cfn-modules/ecs-cluster/module.yml'
```

## Examples

* [fargate-alb-ambassador-pattern](https://github.com/cfn-modules/docs/tree/master/examples/fargate-alb-ambassador-pattern)
* [fargate-alb-single-container](https://github.com/cfn-modules/docs/tree/master/examples/fargate-alb-single-container)

## Related modules

* [fargate-service](https://github.com/cfn-modules/fargate-service)

## Parameters

none
