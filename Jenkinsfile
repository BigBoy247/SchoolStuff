pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        'cd "C:\Program Files\Unity\Hub\Editor\2019.3.0f1\Editor\"',
	'.\Unity -batchmode -projectPath D:\Development_of_games\Simple_Lane_Runner -runTests -testPlatform editmode -logfile - -testResults ./unit-tests.xml | Out-Default'
      }
    }

    stage('build') {
      steps {
        echo 'Building...'
      }
    }

  }
}