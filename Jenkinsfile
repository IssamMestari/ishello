node{
    stage('clone'){
        sh "git clone https://github.com/IssamMestari/ishello.git"
    }
    stage('build'){
        sh "javac Main.java"
    }
    stage('test'){
        sh "java Main"
    }
}