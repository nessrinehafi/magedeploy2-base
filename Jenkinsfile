node{
 deleteDir()
    stage('clone')
        checkout scm
    stage('Composer')
        sh "composer update"
 stage('DEV'){
   sh"echo 'a' | sudo php bin/magento cache:clean"
   sh"echo 'a' | sudo php bin/magento setup:upgrade"
 }
 



}
