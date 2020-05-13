pipeline {
    agent {
        label 'muni'
    }
    stages{
        stage("echo"){
           steps{
             git url : 'git@github.com:efsavage/hello-world-war.git'
             sh 'ls -l'
             sh 'mvn package'
           }
        }
    }
}
