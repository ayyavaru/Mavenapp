node{
stage('SCM Checkout')
{
git 'https://github.com/ayyavaru/Mavenapp'
}
stage('Compile-Package'){
sh 'mvn package'
}
}
