node(){
  stage("1"){
   sh "echo Hello World"
   gir "git url" 
  }
  stage("2"){
  echo "I am in Second Pipe"  
    mvn clean install
  }

}
