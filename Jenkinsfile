pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket2020060888888 --template-body file://SampleS3cft.json --region 'ap-south-1'"
              }
             }
            }
            }
