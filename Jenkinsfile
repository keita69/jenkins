pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "NG"
                parallel (
                    "tomcat" : {
                        echo 'done!'
                    },
                    "postgres" : {
                        echo 'done!'
                    }
                )
            }
        }  
    }
}
