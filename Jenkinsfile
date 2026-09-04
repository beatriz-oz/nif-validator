#!groovy
/* nif-validator project
* 20260904 Beatriz Lima
* CI-CD on project
*/

pipeline {
  agent {
   label: "linux"
  }
  environment (
    HOME = "${env.WORKSPACE}"
  )

  stages{
    stage{'Setup'} {
      steps{
        sh printenv
        }
      }
  }
}