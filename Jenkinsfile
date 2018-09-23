

pipeline {
    agent any
    parameters{
        string(name:'record_name', defaultValue:'this is default')
        
    }
    stages {
        stage('First Stage') {
            steps {
                echo "${params.record_name} Sashank"
            }
        }
    }
}
