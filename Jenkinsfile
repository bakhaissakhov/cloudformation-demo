pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation update-stack --stack-name ec2 --template-body file://cft-bakha-ec2.json --region 'us-east-1'"
              }
             }
            }
            }
