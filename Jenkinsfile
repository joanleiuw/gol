  //start of pipeline
  pipeline{
    //where pipeline job will run
agent any
tools {
  maven 'Default'
}
    //start of stages: build, test, deploy...
stages{
      //start of stage: build
  stage('build'){
      //start of running steps inside one stage
    steps:{
          //invoke command to build maven
      bat 'mvn clean install'
  }
}
  }
}
