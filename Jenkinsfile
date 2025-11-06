pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Сборка приложения'
      }
    }
    stage('Test') {
      steps {
        echo 'Тестирование'
      }
    }
    stage('Deploy') {
      steps {
        echo 'build name is $BUILD_NAME'
        echo 'Деплой и домой'
      }
    }
  }
}
