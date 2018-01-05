pipeline {
  agent any
  parameters{
    choice(name: 'door_choice',
          choices: 'one\ntwo\nthree\nfour',
          description:'What door do you choose?')
    booleanparam(name: 'CAN_DANCE',
                 defaultvalue: true,
                 description: 'checkbox parameter')
    string(name: 'sTrangeparam',
           defaultvalue: 'Dance!',
           description: 'Do the Funky chicken!')           
  }
  stages {
    stage('Hello world') {
      steps {
        bat 'echo Hello EF'
      }
    }
  }
}
