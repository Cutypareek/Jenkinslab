pipeline {
    agent any
    stages{
    stage ('sample1'){
        echo 'Building...'
        bat 'python part.py'
            }
    stage ('sample2'){
        echo 'Using maven'
        bat 'mvn'
    }
}
}
