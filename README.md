# Use Jenkins and AWS CLI from python script to create and configure my AWS EC2 instances

# Configure Jenkins (Docker container)

## Jenkins - https://hub.docker.com/_/jenkins/
### but.. use the latest jenkins docker image
### https://hub.docker.com/r/jenkins/jenkins

docker pull jenkins/jenkins:lts

docker run -p 8080:8080 -p 50000:50000 -v /Users/strangt/jenkins_home:/var/jenkins_home --rm jenkins/jenkins:lts

# Configure Python

## check for boto3

python -m pip list
python -m pip install boto3
