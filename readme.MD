# VPC module
this module is developed for join devops company. Projects inside joindevops followed this module to create their VPC

## Inputs
* project(required)- User should specify their project name
* Environment(required) - User should specify their env
* cidr_block(Optional) - User can provide their cidr_block, Default is 10.0.0.0/16

## Outputs
*vpc_id - export VPC ID created