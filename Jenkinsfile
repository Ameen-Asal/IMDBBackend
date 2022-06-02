pipeline{
  agent any
  
  stages {
    stage("build"){
      steps {
        echo 'building the application'
        sh 'ls -lt'
        sh 'pwd'
      }
    }
    
    
    stage("test"){
      steps {
        echo 'testing the application'
      }
    }
    
    
    stage("deploy"){
      steps {
        echo 'deploying the application'
      }
    }
    
     stage("script"){
      steps {
        echo 'add sctipt to application'
        script {
            def test = 2>3 ? " cool" : "not cool"
            echo test
        }
      }
    }
  }
}
