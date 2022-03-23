node {
    stage('Preparation') { 
        git url: 'https://github.com/adhavishal/helloworld.git'
    }
    stage('Build') {
                sh 'mvn clean package'
            }
}
