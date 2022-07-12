node{
    stage('Clone') {
    git 'https://github.com/taiebmehrez/Jenkins.git'
}
  stage('Build') {
    sh '''javac Main.java
'''
}
  stage('Run') {
    sh '''java Main
'''
}
}
