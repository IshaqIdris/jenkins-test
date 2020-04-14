pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
                var=$('npm --version')
                echo $var
            }
        }
    }
}
