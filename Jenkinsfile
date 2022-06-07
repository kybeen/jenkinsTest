pipeline {
    agent {
        label "demoAgent"
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
//                 build 'SeleniumMaven'
                sh "date"
                echo "UTC 시간이라 한국 기준 9시간 전으로 표시됩니다."
                echo "한국 시간 : 202206071434"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
    post {
    always {
        echo "pipeline job done!!!"
    }
}
}
