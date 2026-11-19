node{
    stage('clone'){
        sh "rm -rf *"
        sh "git clone https://github.com/IssamMestari/ishello.git"
    }
    stage('build'){
        sh "ls"
        sh "javac Main.java"
    }
    stage('test'){
        sh "java Main"
    }
}