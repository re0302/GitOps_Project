node {
    sh 'ls -l'
    dir ('foo') {
        writeFile file:'dummy', text:''
    }
    sh 'ls -l'
}
