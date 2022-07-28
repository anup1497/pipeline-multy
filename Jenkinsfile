pipeline {
agent any
stages {
stage ('copy-dev') {
steps {
sh 'cp -r dev.html /var/www/html/'

}

}
stage ('copy-QA') {
steps {
sh 'cp -r qa.html /var/www/html/'

}

}
stage ('restart-Apache') {
steps {
sh 'service httpd restart'

}

}
}

}
