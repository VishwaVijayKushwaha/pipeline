println "______________________"+JOB_NAME
println "______________________Reading yml file"
def env = readYaml file: "sample.yml"
println env.name
println env.age
println "______________________Done reading file"


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

