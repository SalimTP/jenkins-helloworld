node {
    stage('Clone') {
        git branch: 'main', credentialsId: 'token_salim', url: 'https://github.com/SalimTP/jenkins-helloworld.git'
    }
    
    stage('Build') {
       sh '''javac Main.java'''
    }
    
    stage('Run') {
        sh 'java Main'
    }

}
