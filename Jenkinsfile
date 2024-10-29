pipeline{
    agent any

    tools {
         maven 'maven 3.9.9'
    }

    stages{
        stage(github){
            steps{
                git branch:'master', url: 'https://github.com/Prakashreddy14306/java-hello-world-with-maven.git
            }
        }
        stage('build'){
            steps{
               sh 'mvn clean package'
            }
        }
    }
}
