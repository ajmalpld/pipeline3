pipeline {
    agent any 
    stages {
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
