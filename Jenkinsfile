[200~pipeline {

agent any

stages { 

stage ('copy-index') {

   steps {
  
   sh 'cp -r index.html /var/www/html/'

    }
}
stage ('copy-qa') {

   steps {
  
   sh 'cp -r qa.html /var/www/html/'

    }
}
stage ('restart-apache') {

   steps {
  
   sh 'service httpd restart'

    }
}

} 

}
