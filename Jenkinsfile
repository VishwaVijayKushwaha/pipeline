def jobnameparts = JOB_NAME.tokenize('/') as String[]
def repositoryname = jobnameparts[2]
println "______________________"+repositoryname

pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                println '____test completed__________________'
            }
        }
    }
}

