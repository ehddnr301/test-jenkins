pipeline{ 
    agent any

    stages { 
        
        stage("build") {
            steps {
                echo 'hihi'

                script {
                    def test  = 2 + 5 > 3 ? 'true' : 'false'
                    echo test
                }
            }
        }

        stage("test") {
            steps {
                sh 'echo testest'
            }
        }

        stage("deploy") {
            steps {
                sh 'echo deployy'
            }
        }
    }
}