pipeline {

    agent any

    stages{

        stage ("Git checkout"){

            steps {
                script{
                    git branch: 'main', url: 'https://github.com/Sushant-vikas/Jenkins_java_app.git'
                }
            }
        }

        stage ("Mave Unit test"){

            steps {
                script{
                    sh 'mvn test'
                }
            }
        }
    }


}