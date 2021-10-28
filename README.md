# Goal

- You can start jenkins!!!


```groovy

pipeline{ // top level
    agent any // where to execute

    stages { // where the work happens
        // 내부에는 stage 와 steps로 구성
        stage("build") {
            steps {
                sh 'echo hihi'
            }
        }

        stage("test") {
            steps {
                sh 'echo testest'
            }
        }

        stage("deploy") {
            steps {
                sh 'deployy'
            }
        }
    }
}
```