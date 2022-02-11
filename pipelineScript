node {
    stage('Create file') {
        sh 'touch myFile.txt'
    }
    stage('Write') {
        sh 'echo "First pipeline" > myFile.txt'
    }
    stage('Print') {
        sh 'cat myFile.txt'
    }
}
