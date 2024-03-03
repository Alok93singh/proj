pipeline{
  agent any
  stages{
    stage("firststage"){
      steps{
        script{
          echo "hello"
          gitCheckout(
                branch: "main",
                url: "https://github.com/Alok93singh/proj.git"
            )
        }
      }
    }
  }
}
