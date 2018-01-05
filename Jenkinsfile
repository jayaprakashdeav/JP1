pipeline {
  agent any
  parameters{
    choice(name: 'door_choice',
          choices: 'one\ntwo\nthree\nfour',
          description:'What door do you choose?')    
  }
  stages {
    stage('Hello world') {
      steps {
        bat 'echo Hello ABCD'
      }
    }
  }
}
