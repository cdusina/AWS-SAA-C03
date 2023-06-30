# AWS-SAA-C03  
## Cloud computing provides

1. On-Demand Self-Service: Provision and terminate using a UI/CLI without human interaction.
2. Broad Network Access: Access services over any networks on any devices using standard protocols and methods.
3. Resource Pooling: Economies of scale, cheaper service.
4. Rapid Elasticity: Scale up and down automatically in response to system load.
5. Measured Service: Usage is measured. Pay only for what you consume.

# COURSE FUNDAMENTALS AND AWS ACCOUNTS

## AWS ACCOUNTS
1. AWS accounts are a container for identities and AWS resources
2. The email address initialy used for setup will be the Root user which will have unrestricted access.
3. Other users can be added within the account which you can limit what access they have throughout the account. These are refered to as IAM users.

## IAM ACCOUNT BASICS

IAM has 3 basic jobs
1. Allows you to create, modify, and identities such as users and roles.
2. Authenticates Identities.
3. Authorize - Allows or denies access to certain resources.

Only give necessary access to IAM accounts. (Least privileged access).
IAM Is a globally resilient service meaning any data is secure over all AWS Regions (Can be used anywhere)<- On exam

IAM lets you create 3 different types of identity objects:
1. Users - Humans or applications that need to access your account.
2. Groups - Collection of related users. ex: Dev team, finance, HR.
3. Roles - Can be used by AWS Services, or for granting external access to your account.

IAM POLICY - Allows or Denies access to AWS Services. These can be attached to users, Groups, or Roles. 
   
