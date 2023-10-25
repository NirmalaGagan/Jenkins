Pipeline{
           stage('Two') {
                          environment {                                       // Declaring at state will allow only that stage to access that variable
                            ENV_URL = "stage2.global.com"
                                      }
                          steps {
                           echo "I am Stage Two Step"
                           echo "ENV_URL is ${ENV_URL}"
                           sh "sleep 300"
                               }
                        }

                stage('Three') {
                    steps {
                        sh '''
                            echo Hello World
                            echo Hai World
                            echo I am using Pipeline Syntax Generator
                            sleep 300
                            env
                        '''
                    }
                }
}