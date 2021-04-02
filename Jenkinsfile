pipeline {
     agent any
     stages {
          stage("Checkout") {
               steps {
                    git url: 'https://github.com/webandsoft/calculator.git'
               }
          }
          stage("Compile") {
               steps {
                    sh "./gradlew compileJava"
               }
          }
     }
}