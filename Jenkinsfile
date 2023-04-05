pipeline {
agent any 
  stages {
    stage('Build eks cluster') {
      steps {
        sh "aws cloudformation create-stack --stack-name laxmiEksStack1 --template-body file://eks-cloudformation.yaml --region 'us-east-1'"
      }
    }
  }

}
