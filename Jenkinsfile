node('master')
{
  stage('Continuous Download')
  {
    git 'https://github.com/keshavr21/maven_test.git'
  }
  stage('Continuous Build')
  {
    sh 'mvn package'
  }
} 
