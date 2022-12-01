pipeline {
    agent any

    stages {
        stage('Hello')    {
            steps {
                echo 'Hello World'
            }
        }

        stage('Master-only') {
            // Stage nur ausführen, wenn auf master Branch
            when {
                branch  'master'
            }

            steps {
                echo 'Auf Master Branch'
            }
        }
    }
}
