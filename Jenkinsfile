pipeline {
  agent any
    stages {
    
      stage('BUILD') {
        steps {
         echo "this is a Build stage" 
        }
      }
      
      stage('test') {
        steps {
         echo "this is a run test cases" 
        }
      }
      
       stage('deploy') {
         parallel{
           
           stage('server1') {
              steps {
               echo "this is a server1" 
                  }
                 }
           
           stage('server2') {
              steps {
               echo "this is a server2" 
                  }
                 }
           
           stage('server3') {
              steps {
               echo "this is a server3" 
                  }
                 }
           
                }
               }
      
    }
}
