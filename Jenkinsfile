pipeline {
    agent any
    stages {
        
        stage('Build dev accounting-dist') {
            when {
                branch 'main'
                
            }
            steps {
                echo 'preparando construcción en entorno desarollo'
                sh ping 8.8.8.8 -c 5
                }
        }
      
    }
}

