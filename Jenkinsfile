pipeline {
    agent any

       stages{
           stage("Server Details"){
            steps{
                sh 'uname -a'
            }
          }

          stage('Server Date'){
            steps{
                sh 'date'
            }
          }

          stage("Server Memeory usage"){
            steps{
                sh 'free -h'
            }
          }

          stage("Server disk usage"){
            steps{
                sh "df -h"
            }
          }

       }
    }
