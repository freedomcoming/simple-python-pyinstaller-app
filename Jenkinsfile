pipeline {
    agent none
    stages {
        stage('Build') {
            agent {
                none
            }
            steps {
                sh 'python --version'
            }
        }
        // stage('Test') {
        //     agent {
        //         docker {
        //             image 'qnib/pytest'
        //         }
        //     }
        //     steps {
        //         sh 'py.test --verbose --junit-xml test-reports/results.xml sources/test_calc.py'
        //     }
        //     post {
        //         always {
        //             junit 'test-reports/results.xml'
        //         }
        //     }
        // }
        // stage('Deliver') {
        //     agent {
        //         docker {
        //             image 'cdrx/pyinstaller-linux:python2'
        //         }
        //     }
        //     steps {
        //         sh 'pyinstaller --onefile sources/add2vals.py'
        //     }
        //     post {
        //         success {
        //             archiveArtifacts 'dist/add2vals'
        //         }
        //     }
        // }
    }
}
