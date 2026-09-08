This is complete config to work with this module.

USAGE:
''' 
output "vpc" {
  value = module.vpc.vpc_id
}

output "public_subnets" {
    value = module.vpc.public_subnets
  
}


output "private_subnets" {
    value = module.vpc.private_subnets
  
}


'''