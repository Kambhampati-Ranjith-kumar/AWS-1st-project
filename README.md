# AWS 1st project
# AWS Bastion + Auto scaling + load balancer

## Architecture
- Bastion Host (public subnet)
- Auto Scaling Group (Private subnets)
- Application Load Balancer
- SSH via Bastion only

## Steps Implemented
- Created EC2 instance using ubuntu
- Configured Bastion Host
- Set uo Auto Scaling Group
- Configured Application Load Balancer
- Connected instances using SSH
- Managed source code using git
- Pushed project to GITHUB using Personal Access Token

## Features
- Secure SSH Access
- High Availability
- Scalable backend
- No public IPs on app instance

## Security
- SSH keys ignored via .gitignore
- Private instances accessed only via Bastion
