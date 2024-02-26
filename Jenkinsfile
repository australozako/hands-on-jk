node {
    stage('Clone') {
    // some block
        git 'https://github.com/australozako/hands-on-jk.git'
    }
    stage('Build') {
        sh label: '', script: '''
        javac MainT.java
        '''
    }
    stage('Run') {
        sh label: '', script: '''
        java MainT
        '''
    }
}