pipeline {
	agent any
    stages {
        stage('Build on k8 ') {
            steps {           
                       
                        sh '/usr/local/bin/helm repo add bitnami https://charts.bitnami.com/bitnami'
                        sh '/usr/local/bin/helm install my-jenkins nginx'   
              			
            }           
        }
    }
}
