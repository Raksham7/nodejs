node 
{

    stage('checkout') {
        git credentialsId: 'git', url: 'https://github.com/Raksham7/nodejs.git'
    }
      stage('Build') {
        sh "npm install"
    }
       stage('build'){
        nodejs(nodeJsInstallationName: 'nodejs19.3.0'){
            sh "npm install"
        }
    }


}
