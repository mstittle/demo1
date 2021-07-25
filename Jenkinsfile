pipeline {
    agent any


    stages { stage('install') {
            steps {
                // Get some code from a GitHub repository
             //   git 'https://github.com/mstittle/demo1'

                // Run Maven on a Unix agent.
                bat "npm install"
echo "hello"
            }

        stage('Build') {
            steps {
                // Get some code from a GitHub repository
             //   git 'https://github.com/mstittle/demo1'

                // Run Maven on a Unix agent.
                bat "npm run build"
echo "hello"
            }
         
        }
    }
}
