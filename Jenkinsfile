node 
{

    stage('checkout') {
        git credentialsId: 'git', url: 'https://github.com/Raksham7/nodejs.git'
    }
      stage('Build') {
        sh "npm install"
    }
      stage("Build") {
       nodejs(nodeJSInstallationName: 'nodejs15.2.1') {
        sh 'npm install'
       }
    }  


}
