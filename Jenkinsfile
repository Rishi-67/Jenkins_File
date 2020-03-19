node{
    stage('SCM Checkout'){
    git 'https://github.com/Rishi-67/Jenkins_File'
    
    }
    stage('Compile-Package'){
        def mvnHome = tool name: 'Maven_3_6_3', type: 'maven'
        bat (/"${mvnHome}\bin\mvn" package/)
    
    
    }
    
}
