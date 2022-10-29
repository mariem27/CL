pipeline {
    agent any
    stages {
        stage ('Checkout Git') {
             steps {
                script{
                    checkout([$class: 'GitSCM' , branches: [[name: '*/mariem']],
                        userRemoteConfigs: [[
	                    url : 'https://github.com/mariem27/CL.git',
                            credentialsId:'59ba01ab-9df5-485e-bb56-c2c8c6b29cd6']]])
        }
        }
}
}
}
       