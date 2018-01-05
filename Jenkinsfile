pipeline {
  agent any
  stages {
    stage('Hello world') {
      steps {
        bat 'echo Hello ABCD'
      }
    }
  }
  parameters {
    choice(name: 'door_choice', choices: '''one
two
three
four''', description: 'What door do you choose?')
  }
}