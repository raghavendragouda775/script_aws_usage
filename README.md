# script_aws_usage
Features
*S3 Buckets: Lists all S3 buckets in your account.
*EC2 Instances: Displays details of all EC2 instances.
*Lambda Functions: Lists all deployed Lambda functions.
*IAM Users: Shows all IAM users in your account.


##Prerequisites
Ensure the following are set up before running the script:

AWS CLI Installed:
Install the AWS CLI if it's not already installed:

#bash
sudo apt update
sudo apt install awscli
AWS Configuration:
Configure the AWS CLI with valid credentials and a default region:

#bash
aws configure



##You’ll need:
AWS Access Key ID
AWS Secret Access Key
Default Region (e.g., ap-south-1)
Executable Permission:
Make the script executable:

#bash
chmod +x aws_resource_tracker.sh

##How to Use

Clone the repository:
#bash
git clone https://github.com/yourusername/aws-resource-tracker.git

Navigate to the directory:
#bash
cd aws-resource-tracker

#Run the script:
bash
./aws_resource_tracker.sh

