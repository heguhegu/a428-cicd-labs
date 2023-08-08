node {
        docker.image('node:16-buster-slim').withRun('-p 3000:3000')

        {

        docker.image('node:16-buster-slim').inside{

        stage('Build'){
                echo 'heloooo'
        }
        stage('Test'){
                sh './jenkins/scripts/test.sh'
        }
        }

   }
}
