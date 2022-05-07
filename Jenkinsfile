node
{

  println "Hello World"
  checkout scm
  
  withCredentials([string(credentialsId: 'BindCredentials',usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD')]) {
    sh '''
      set +x
      echo "$USERNAME"
    '''
  }
  
}
