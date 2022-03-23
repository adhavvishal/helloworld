node {
    stage('Preparation') { 
        git 'https://github.com/adhavvishal/helloworld'
    }
    stage('Build') {
                sh 'mvn clean package'
            }
    stage('ArchiveResults') {
        archiveArtifacts 'target/*.war'
    }
}
