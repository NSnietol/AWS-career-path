
Tighten the security some services, it's possible to use inner security groups as source of inbound rules. 

- The idea is to use the ID of Security group which is use by the other service to as inbound rule in for instance EC2 instances, in this way instances wouldn't be available to the public but just through the service is using it.
