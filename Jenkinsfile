node 
{

    stage('checkout')
    {
        git credentialsId: 'git', url: 'https://github.com/Raksham7/nodejs.git'
    }

    stage('Build')
    {
        sh "npm install"
    }
    stage('ExecuteSonarQubeReport'){
    nodejs(nodeJSInstallationName: 'nodejs18.6.0'){
        sh "npm run sonar"
    }
    }
}
