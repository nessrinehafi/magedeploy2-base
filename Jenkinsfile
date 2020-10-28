node{
 deleteDir()
    stage('clone')
        checkout scm
    stage('Composer')
        sh "composer update"
    stage('Root directory')
        sh"ls"
 stage('DEV'){
   sh" sudo php bin/magento  cache:clean"
   sh" sudo php bin/magento  setup:upgrade"
 }
 



}
