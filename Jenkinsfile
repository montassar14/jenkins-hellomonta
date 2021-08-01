node {
    stage('Clone') {
          git 'https://github.com/montassar14/jenkins-hellomonta.git'
    }
    stage('Build') {
          sh '''javac Main.java'''
    }
    stage('Run') {
          sh '''java Main'''
    }
}

