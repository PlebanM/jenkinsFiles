def config = [
    PROJECT_NAME: 'mepco-cloud-product-catalog-service',
    PROJECT_TYPE: "backend===========> ${config.PROJECT_NAME}"
]

pipeline {
    agent any

    stages {
        stage ('setup') {
            steps {
                script {
                    echo "echo from setup: ${config.PROJECT_NAME}"
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