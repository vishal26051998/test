pipeline{
      agent{
	      label{
          label'built-in'
          customWorkspace"/mnt/data"		  
	  
	  
	      }
}
 stages{
   stage('stage-1'){
       steps{
	       sh"yum install httpd -y"
	       sh"service httpd start"
	       sh"cp -r index.html /var/www/html"
	     sh"chmod -R 777 /var/www/html/index.html"
	   
	   
   }
   
   }
   stage('stage-2'){
      steps{
	     sh"touch vishal nilesh dinesh"
	  
	  }
   
   }
}
}
