pipeline {
    agent  {  label "julio-jenkin" }

    stages {
        stage('Mon Monde A moi DIAM') {
            steps {
                echo 'Hello World  pousser vous on arrive en speed '
            }
        }
    }
    post 
    {
        always
        {
           mail bcc: '', body: 'Encore toi pr ca pour ca jenkins', cc: '', from: '', replyTo: '', subject: 'OK OK mon email jenkins server setup', to: 'jeanphilippepersonaluse@gmail.com'
        }
        
    }
}
