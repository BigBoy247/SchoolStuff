pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        cd "C:\Program Files\Unity\Hub\Editor\2019.2.12f1\Editor",
	'.\Unity -batchmode -projectPath C:\Users\Youuuuu\Downloads\unityProjects\aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaahhh\Runner -runTests -testPlatform editmode -logfile - -testResults ./unit-tests.xml | Out-Default'
      }
    }

    stage('build') {
      steps {
        echo 'Building...'
      }
    }

  }
}
