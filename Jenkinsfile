pipeline {
agent any 
  stages {
    stage('Build eks cluster') {
      steps {
        sh "aws cloudformation create-stack --stack-name laxmiEksdemo5 --template-body file://eks-cloudformation.yaml --region 'us-east-1'"
      }
    }
  }

}
