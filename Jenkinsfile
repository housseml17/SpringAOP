pipeline {
    agent any

   
    stages {
        stage('checkoutGIT') {
            steps {
                
                echo 'puling...';
                git branch : 'main',
                url:'https://github.com/housseml17/SpringAOP.git';
               
            }
        }
    }
}
