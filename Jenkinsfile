pipeline {
    agent any
    stages {
        stage('create ec2') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2 --template-body file://cft-bakha-ec2.json --region 'us-east-1'"
              }
             }
            }
            }
