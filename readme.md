# Terraform AWS VPC

    This module creates following resources:
    1. vpc
    2.Internet Gateway with vpc Association
    3.subnets-public,private,database
    4.RouteTables- public,private,database
    5.Associations and Routes
    6.EIP
    7. NAT GAteway
    8. VPC peeringwith default vpc on condition

## INPUTS
    * project - (Required) string type, user should pass the project name.
    *environment-(Required) string type, user should pass the environment name like dev,prod,uat,qa.
    *is_peering_required- (Rquired) bool type, user should pass the value true or false.



