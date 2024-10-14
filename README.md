# Elasticache Valkey (*Serverless*) with *Amazon Linux 2023*
This is a Repository that contains YAML CloudFormation template to create an ElastiCache Valkey (Serverless) cluster with an Amazon Linux 2023 EC2 instance and connect to it. 

### NOTE: Only to be used in AWS CLOUD.

#### This is a CloudFormation YAML template. 

This template can be used to create an ElastiCache Valkey (Serverless) cluster with an Amazon Linux 2023 EC2 instance and connect to the Redis cluster.

1. Download the template to your local machine from GitHub repository.

    ```sh
    wget https://raw.githubusercontent.com/sattyagrah/Serverlessredis-ec2/main/serverless-redis-ec2.yaml
    ```
2. Use the template to [create the Stack](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-console-create-stack.html) through AWS Console. 

3. After creating the stack [connect to Ec2 instance](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/connect-linux-inst-ssh.html#connect-linux-inst-sshClient) and run the command -
    ```sh 
    sudo /home/ec2-user/valkey.sh
    ```

4. You will be connected to the Redis serverless cluster.