println "______________________"+JOB_NAME
node {
    def files = findFiles(glob: '*.*')
    for (file in files) {
        println '_____'+file
    }
    println "______________________Reading yml file"
    def env = readYaml file: "sample.yml"
    println env.name
    println env.age
    println "______________________Done reading file"
}

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

