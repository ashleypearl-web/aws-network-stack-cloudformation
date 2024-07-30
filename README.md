# aws-network-stack-cloudformation
This template deploys a VPC, with a pair of public and private subnets spread   across two Availability Zones. It deploys an internet gateway, with a default   route on the public subnets. It deploys a pair of NAT gateways (one in each AZ),   and default routes for them in the private subnets.
