node {
   stage('clone java project') {
   git branch: 'main', url: 'https://github.com/laxmikant7007/jenkin.git'
}
stage('build fz maven project') {
    sh 'mvn install'
}
}
