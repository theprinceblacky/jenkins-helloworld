node {
    stage('Clone') {
        git 'https://github.com/theprinceblacky/jenkins-helloworld.git'
    }
     stage('Build') {
        sh label: 'script', script: 'javac Main.java'
    }
     stage('Run') {
        sh label: 'script', script: 'java Main'
    }
}
