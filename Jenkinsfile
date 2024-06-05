pipeline {
  agent any
  stages {
    stage("Testing") {
      steps {
        powershell ('Write-Output "Test tag stage"')
        powershell ('Write-Output "$env:TAG_NAME"')
      }
    }
}
