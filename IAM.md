# IAM

Identity and Access Management
Service in security 
grant access to users to use aws services

Manage access to users
create users and assign permission policy
users can also belong to groups, users inside a group inherit all policies assigned to the group

root user has access to all AWS resources


## IAM role:
  give application access to services
  if you need to grant access but dont want to create permanent permissions
  Eg. If security auditors need to do audit your AWS environment,
  create a role and assign it to the AWS account of that auditor
  
## IAM policies
  explicit deny always overrides explicit allow
  
## IAM Users
    can have max of 2 keys
    if no permission policy then it will get no access to services
    MFA can be enabled
  

    
