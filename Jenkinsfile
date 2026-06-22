pipeline {
    agent any
     tools{
         jdk 'jdk-17'
         maven 'maven3.6'

     }
    stages {
        stage('Adding new jenkisfile'){
              steps {
                  echo "Adding new file"
                              }
                           }
            
        stage('maven install'){
            steps{
                sh 'mvn install'
            }
        }
        stage('mvn package'){
            steps{
                sh 'mvn package'
            }
          }
        }
    }


