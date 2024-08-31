pipeline{
    agent any
    environment {
        name = "Rakesh"
        course = "devops"
    }
    stages{
        stage("DevEnv"){
            environment {
                GitHub_Credential = credentials('java-slave-user')
            }
            steps{
               echo "My name is ${name}"
               echo "enrolled course for ${course}"
               echo "Username ${GitHub_Credential_USR}"
               echo "password ${GitHub_Credential_PSW}"
            }
        }
    }
}
