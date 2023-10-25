Pipeline{
           stage('One') {
                          
                          steps {
                           echo "I am Stage Two Step"
                                }
                        }

                stage('Two') {
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