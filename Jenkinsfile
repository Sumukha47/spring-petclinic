node {
    stage('git-clone') { 
        git branch: 'main', url: 'https://github.com/Sumukha47/spring-petclinic.git'
    }
    stage('Build generation') { 
        sh 'mvn package'
    }
}
