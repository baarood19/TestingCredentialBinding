node
{

  println "Hello World"
  checkout scm
  
 withCredentials([usernamePassword(credentialsId: 'BindCredentials', passwordVariable: 'PasswordVar', usernameVariable: 'UsernameVar')]) {
    sh '''
      set +x
      echo "$PasswordVar"
    '''
  }
  
}
