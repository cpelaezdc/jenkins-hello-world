pipeline {
          agent any
          stages {
              stage('Build') {
                  steps {
                      script {
                          // Choisissez la commande en fonction de votre script
                          sh "ls -l"
                          sh 'python3 hello.py' // Pour Python
                          sh 'java HelloWorld.java' // Pour Java
                      }
                  }
              }
          }
      }
