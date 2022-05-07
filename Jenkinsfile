node
{

  println "Hello World"
  checkout scm
  
  withCredentials([string(credentialsId: 'BindCredentials', variable: 'TOKEN')]) {
    sh '''
      set +x
      echo "$TOKEN"
    '''
  }
  
  
}
