pipeline {
    agent any

    environment {
        GIT_HOST = 'git.accountor.eficode.io'
        GIT_INFRA_PATH = "git@${GIT_HOST}:accountorhr/mepco-cloud/"
    }
    parameters {
        booleanParam(name: 'Dryrun', defaultValue: true, description: 'If set, echoes the actions to be taken but does not apply them')
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
                echo "Teksy install ${patam.Dryrun}"
            }
        }
    }
}