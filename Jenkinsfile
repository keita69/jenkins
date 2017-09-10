pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                parallel (
                    "tomcat" : {
                        echo 'done'
                    },
                    "postgres" : {
                        echo 'done'
                    }
                )
            }
        }  
    }
}
