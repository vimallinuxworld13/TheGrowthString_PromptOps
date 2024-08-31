pipeline {
    agent any

    stages {
        stage('Trigger CodeBuild') {
            steps {
                {
                    sh "aws codebuild start-build --project-name TGSweb123 --region ap-south-1"
                }
            }
        }
    }
}