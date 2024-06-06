pipeline {
  agent any
  stages {
    stage("Testing") {
      steps {
          script {
            def imageName = "ehx:${env.BRANCH_NAME}"
            powershell ('Write-Output "$env:imageName "')
          }
        powershell ('Write-Output "Test tag stage"')
        powershell ('Write-Output "$env:BRANCH_NAME"')
      }
    }
  }
}
