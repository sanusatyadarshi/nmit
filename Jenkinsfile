node('master') {
    // Init stage - get source code from Github
    stage('Init')  {
        git branch: 'master', changelog: true, url: 'https://github.com/sanusatyadarshi/nmit.git'
    }
    stage('Deploy to Nginx') {
        sh "pwd"
        sh "cd nmit"
    }
}
