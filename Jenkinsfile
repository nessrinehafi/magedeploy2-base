node{
 deleteDir()
    stage('clone')
        checkout scm
    stage('Composer')
        sh "composer update"
 stage('DEV'){
   sh"sudo php bin/magento cache:clean"
   sh"sudo php bin/magento setup:upgrade"
 }
 



}
