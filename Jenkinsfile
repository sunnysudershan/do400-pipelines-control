node('nodejs') {
    stage('Checkout') {
       git branch: 'main', url: 'https://github.com/sunnysudershan/do400-pipelines-control'
  }

    stage('Backend Tests') {
       sh 'node ./backend/test.js'
  }


    stage('Frontend Tests') {
       sh 'node ./fronend/test.js'
  }
}
