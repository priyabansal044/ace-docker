def workspace
def serviceName =  "Communications";
    node()
    {
     
 // Define extra variables here
   stage('Code Commit')
        {
            checkout scm;
            workspace = pwd ();  // Workspace path
         // checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, userRemoteConfigs: [[credentialsId: 'e9c0d3d6-2ed6-423c-be9c-89dd25602b0d', url: 'https://github.ibm.com/sispoc/pipeline-test.git']]])
           fileExists 'Jenkinsfile'
            echo 'Verified that the jenkins file exists, proceeding for next stages'  
        }
