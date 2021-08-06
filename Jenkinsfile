pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket20200608cftcreation --template-body file://SampleS3cft_new.json --region 'ap-south-1'"
              }
             }
            }
            }
