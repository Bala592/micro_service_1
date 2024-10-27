@Library('shared-library') _
pipeline {
    agent any

    stages {
        stage('Git clone') {
            steps {
                    gitClone('main', 'Git_hub_user_Name_and_password', 'https://github.com/Bala592/micro_service_1.git')
            }
        }
    }
}
