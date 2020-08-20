node {   def mvnHome
   stage('master checkout') { 
      checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '85dfbf76-ccd6-4e0a-8cde-3b942a82e328', url: 'https://github.com/naveenkhannan/hello-world-war.git']]])
      
        //mvnHome = tool 'M3'
   }
   stage('branch1 checkout') { 
   checkout([$class: 'GitSCM', branches: [[name: '*/branch1']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '85dfbf76-ccd6-4e0a-8cde-3b942a82e328', url: 'https://github.com/naveenkhannan/hello-world-war.git']]])
   
        //mvnHome = tool 'M3'
    }
}
