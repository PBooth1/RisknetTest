pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('Git Clone') {
            steps {
                git url: \
                'https://github.com/petervdtoorn/atradiusrisknet.git'
            }
        }
        stage('Compile') {
            steps {
                sh """find . -name '*.py' -print0|xargs -0  -L python2 -m py_compile"""
            }
        }
        stage('build') {
            steps {
                //
            }
        }
        stage('test') {
            steps {
                //
            }
        }
        stage('deoploy') {
            steps {
                //
            }
        }
    }
}
