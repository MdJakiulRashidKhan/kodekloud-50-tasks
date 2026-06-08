# Task 01 : Create Key Pair

## Task Description
The Nautilus DevOps team is strategizing the migration of a portion of their infrastructure to the AWS cloud. Recognizing the scale of this undertaking, they have opted to approach the migration in incremental steps rather than as a single massive transition. To achieve this, they have segmented large tasks into smaller, more manageable units. This granular approach enables the team to execute the migration in gradual phases, ensuring smoother implementation and minimizing disruption to ongoing operations. By breaking down the migration into smaller tasks, the Nautilus DevOps team can systematically progress through each stage, allowing for better control, risk mitigation, and optimization of resources throughout the migration process.

For this task, create a key pair with the following requirements:

Name of the key pair should be devops-kp.

Key pair type must be rsa

---

## Task Solution

### Commands
```bash
# aws ec2 create-key-pair --key-name devops-kp --key-type rsa
```

---

## Notes
An EC2 key pair named "devops-kp" was created using RSA encryption. This key pair enables secure access to AWS EC2 instances through SSH authentication, ensuring secure and passwordless login for server management.
