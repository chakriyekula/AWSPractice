pipeline{
  agent any
  stages{
    stage('submit stack'){
      steps{
        sh "sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://simplests3cft.json --region 'ap-south-1'"
        }
       }
    }
  }
