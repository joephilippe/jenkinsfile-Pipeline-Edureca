pipeline {
    agent  {  label "julio-jenkin" }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post 
    {
        always
        {
           mail bcc: '', body: 'tout ca pour ca jenkins', cc: '', from: '', replyTo: '', subject: 'tester mon email jenkins server setup', to: 'jeanphilippepersonaluse@gmail.com'
        }
        
    }
}
