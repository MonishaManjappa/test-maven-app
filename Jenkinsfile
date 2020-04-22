node('Linux_Slave1')
{
	stage('Clone repo')
	{
		echo "Checkout from Github"
	}

	
	stage('Building the source code')
	{
		echo "Building war"
		sh "mvn compile install"
		
	}
	
	stage('copying to local')
	{
	   //def source= '/var/lib/jenkins/workspace/sample_pipeline_Script/target/jpetstore.war'
	   //def filename= '/home/$user/builds'
	   
	   //sh 'cp -f "${source}" "${filename}"'
	   //sh '''cp -f /var/lib/jenkins/workspace/sample_pipeline_Script/target/jpetstore.war /home/$user/builds''' 
	   echo "copy"
	   //sh "cp /home/jenkins/.m2/repository/com/example/hello/0.1-SNAPSHOT/hello-0.1-SNAPSHOT.jar /home/ubuntu/builds"
	   }
}



