---
layout: post
title: "What you need to know about AWS CloudFormation?"
date: 2015-02-28 15:27:57 +0800
comments: true
categories: [AWS, DevOps]
---

1. CloudFormattion is free to use;
1. You supply a template and any required parameters to CloudFormation to create or update a stack;
1. A template is a JSON-formatted text file ([example](https://s3.amazonaws.com/cloudformation-templates-us-east-1/WordPress_Single_Instance_With_RDS.template));
1. Parameter can be used to specify sensitive information which you don't want to store in the template;
1. If not all resources are created or updated successfully, CloudFormation will rollback every change;
