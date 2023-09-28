node {
    stage('Compile and Run') {
        checkout scm
        sh 'git checkout feature1'
        sh 'javac Sample.java'
        sh 'java Sample'
    }
}
