node {
    stage('Clone') {
        git 'https://github.com/airoud/projet_git.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}