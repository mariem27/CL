pipeline {
    agent any
    stages {
        stage ('Checkout Git') {
             steps {
                script{
                    checkout([$class: 'GitSCM' , branches: [[name: '*/mariem']],
                        userRemoteConfigs: [[
	                    url : 'https://github.com/mariem27/CL.git',
                            credentialsId:'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']]])
        }
        }
}
}
}
       