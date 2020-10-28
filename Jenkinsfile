node{
 deleteDir()
    stage('clone')
        checkout scm
    stage('Composer')
        sh "composer update"
    stage('Root directory')
        sh"cd magedeploy2-base"
 stage('DEV'){
   sh" sudo php bin/magento  cache:clean"
   sh" sudo php bin/magento  setup:upgrade"
 }
 



}
