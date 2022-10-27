pipeline {
    agent any 
    stages {
        stage('clone') { 
            steps {
            sh "git clone https://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@github.com/ajmalpld/pipeline3.git"   // 
            }
        }
        stage('cd') {
            steps {
            sh '''
            #!/bin/bash
            cd pipeline3
            echo mkdir data > mkdir.sh
            chmod +x mkdir.sh
            ./mkdir.sh
            '''
            }
        }
    }
}
