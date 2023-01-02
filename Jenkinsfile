node {
   stage('clone java project') {
   git branch: 'main', url: 'https://github.com/laxmikant7007/jenkin.git'
}
stage('build maven project') {
    sh 'mvn install'
}
}
