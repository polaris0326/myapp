pipeline {
  agent any
  stages {
    stage('input') {
      steps {
      	input message: '123', parameters: [credentials(credentialType: 'com.cloudbees.plugins.credentials.impl.CertificateCredentialsImpl', defaultValue: '', description: '', name: 'param_name', required: true)], submitter: 'gerald'
      }
    }
  }
}