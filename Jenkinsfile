node {
    stage('Preparation') { 
        git branch: 'master', url: 'https://github.com/adhavishal/helloworld.git'
    }
    stage('Build') {
                sh 'mvn clean package'
            }
