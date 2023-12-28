#Task-1
   ● Trigger a pipeline using Git when push on Develop branch 
   ● Pipeline should pull git content to a folder
     
#Task-2
   ● Add 2 nodes to Jenkins master 
   ● Create 2 jobs with the following jobs: 
         ○ Push to test 
         ○ Push to prod 
   ● Once a push is made to test branch copy git files to test server 
   ● Once a push is made to master branch copy git files to prod server
  
#Task-3
   ● Create a pipeline in Jenkins 
   ● Once push is made to “develop” branch in git, trigger job “test”. This will  
       Copy git files to test node
   ● If test job is successful, then prod job should be triggered 
   ● Prod jobs should copy files to prod node
