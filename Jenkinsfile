node
{

  println "Hello World"
  checkout scm
  environment{
    BINDCREDS = credentials('BindCredentials')
  }
  echo "${env.BINDCREDS}"
  println "${env.BINDCREDS}"
  echo "${env.BINDCREDS_USR}"
  println "${env.BINDCREDS_USR}"
  echo "${env.BINDCREDS_PSW}"
  
  sh 'printenv'
}
