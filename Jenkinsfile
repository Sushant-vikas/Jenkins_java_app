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

        stage ("Maven Unit test"){

            steps {
                script{
                    set +e
                    sh 'mvn test'
                }
            }
        }
    }


}