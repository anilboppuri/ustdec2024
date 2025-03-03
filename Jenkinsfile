pipeline {
    agent any
    parameters {
        choice(name: 'VERSION', choices: ['1.1.0', '1.2.0', '1.3.0'], description: '')
        booleanParam(name: 'executeTests', defaultValue: true, description: '')
    }
    stages {
        stage("init") {
            steps {
                script {
                    echo "doing init  ...." 
                }
            }
        }
        stage("build") {
            steps {
                script {
                   echo "Building ...."
                }
            }
        }
        stage("test") {
           
            steps {
                script {
                    echo "testing.......                }
            }
        }
        stage("deploy") {
            steps {
                script {
                    echo "deploying ....."
                }
            }
        }
    }   
}
