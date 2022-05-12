node
{

  println "Hello World"
  checkout scm
  
 withCredentials([file(credentialsId: '30aa2f8d-7159-46ad-9d10-c6a2943bee91', variable: 'secretFile')]) {
    env.SECRETFILE = secretFile
    powershell " Copy-Item -Path ${secretFile} -Destination ${WORKSPACE} "
}
  echo " ${env.SECRETFILE}"
  
}
