node
{

  println "Hello World"
  checkout scm
  environment{
    BINDCREDS = credentials('BindCredentials')
  }
  echo "${BINDCREDS}"
  println "${BINDCREDS}"
  echo "${BINDCREDS_USR}"
  println "${BINDCREDS_USR}"
  echo "${BINDCREDS_PSW}"
  
}
