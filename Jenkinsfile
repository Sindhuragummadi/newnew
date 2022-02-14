pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                checkout scm

                sh 'javac Sample.java'
                sh 'java Sample'
                sh '''#!/bin/sh'''


                

            }
        }
    }
