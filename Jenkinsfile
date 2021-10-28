pipeline{ 
    agent any

    stages { 
        
        stage("build") {
            steps {
                sh pwd
            }
        }

        stage("test") {
            steps {
                sh 'git clone https://github.com/ehddnr301/test-jenkins'
            }
        }

        stage("deploy") {
            steps {
                sh 'echo deployy'
            }
        }
    }
}