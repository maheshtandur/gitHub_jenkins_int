pipeline {
    agent any

    stages {
        stage('ENV') {
            steps {
                echo 'Display ENV Variables'
                sh 'env | sort'
            }
        }
        stage('Integration') {
            steps {
                echo "Jenkins and GitHub Integration works.!!!"
            }
        }
    }
}
