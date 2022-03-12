pipeline
{
    tools{
        jdk 'JAVA_HOME'
        maven 'M2_HOME'
    }
    agent any
    
    stages
    {
        
        //stage("clone gitrepo")
       // {
            
           // steps
           // {
                
              // git 'https://github.com/Ambikake/jenkins.git'
                
           // }
            
        //}
        stage("compile")
        {
            
            steps
            {
                
               sh "mvn compile"
            }
            
        }
        stage("test")
        {
            
            steps
            {
                
                sh "mvn test"
            }
            
        }
        stage("package")
        {
            
            steps
            {
                
                sh "mvn package"
            }
            
        }
        stage("deploy")
        {
            
            steps
            {
                echo "mydeployment"
                //sh "mvn package"
            }
            
        }
    }
    
    
}
