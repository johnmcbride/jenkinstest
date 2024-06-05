pipeline {
  agent any
  stages {
    stage("Testing") {
      when { buildingTag() }
      steps {
        powershell ('Write-Output "Test tag stage"')
        powershell ('Write-Output "$env:TAG_NAME"')
      }
    }
  }
}
