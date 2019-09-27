node{
stage('scm'){
git 'https://github.com/openmrs/openmrs-core.git'
}
stage('build'){
sh 'mvn package'
}
}
