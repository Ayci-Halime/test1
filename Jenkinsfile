pipeline {
   agent any
   stages {
       stage('Hello') {
           steps {
               echo "Hello world"
                   }
           }
       }
   post{
       always{
           mail to: "hlmmonder@gmail.com",
           subject: "Test Email",
           body: "Test"
       }
   }
}
