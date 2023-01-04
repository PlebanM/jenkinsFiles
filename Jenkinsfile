pipeline {
    agent any

    enviroment {
        GIT_HOST: 'git.accountor.eficode.io'
        GIT_INFRA_PATH: "git@${GIT_HOST}:accountorhr/mepco-cloud/"
    }

    stages {
        stage ('setup') {
            steps {
                script {
                    echo "echo from setup: ${env.GIT_INFRA_PATH}"
            }
        }
        }
        stage ('install') {
            steps {
                echo 'Teksy install'
            }
        }
    }
}