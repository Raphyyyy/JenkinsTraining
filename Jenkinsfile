node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/Raphyyyy/JenkinsTraining'
    }
    stage('Run') {
        sh 'javac Main.java'
    }
    stage('Build') {
        sh 'java Main'
    }
}