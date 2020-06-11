pipeline {
  agent any
  stages {
    stage('Get Jenkins Node') {
      steps {
        node(label: 'YT') {
          sh '''bat label: \'\', script: \'\'\'python .\\\\getJenkinsNode.py "1_Trex"\'\'\'
script{load(\'jenkinsNode.properties\')}'''
        }

      }
    }

  }
}