node('nodejs') {
    stage('Checkout') {
        git branch: 'master', url: 'https://github.com/parasharsingh8086/do400-pipelines-control'
    }
    stage('Backend Tests') {
        sh 'node ./backend/test.js'
    }
    stage('Frontend Tests') {
        sh 'node ./frontend/test.js'
    }
}
