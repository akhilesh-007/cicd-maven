pipeline{
    agent any
    stages{
        stage("1. git checkout")
        {
            steps{
                    git 'https://github.com/akhilesh-007/cicd-maven.git'
                 }
          }
stage("maven build"){
steps{
sh "mvn -f /root/project/src/main/java/ clean package"
}
}
      
    }
}
