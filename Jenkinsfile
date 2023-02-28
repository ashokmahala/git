pipeline {
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'THIS IS TO BUILD AN APP'
            }
        }
        stage('Test') 
        {
            steps 
            {
                echo 'THIS IS TO TEST AN APP'
            }
        }
        stage('Deploy') 
        {
            steps 
            {
                echo 'THIS IS TO DEPLOY AN APP'
            }
        }
    }
    post
  {
    always
    {
      emailext body: 'summary', replyTo: '1ms21mc010@gmail.com', subject: 'pipelien noti', to: '1ms21mc010@gmail.com'
    }
  }
}
