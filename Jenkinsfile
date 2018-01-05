pipeline {
  agent any
  stages {
    stage('Parameter') {
      steps {
        input 'Ready to go?'
      }
    }
    stage('Hello') {
      steps {
        bat 'Echo Hello world'
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