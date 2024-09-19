# CI-CD-Project-w-Jenkins-Pipeline
Instead of using the previous free style method and creating 3 jobs we will combine all the jobs in one pipeline 

## we will copy the pipeline stages into jenkins to make all stages in one groovy file
in order to overwrite the data in teh volume for teh old container 
docker cp /var/lib/jenkins/workspace/project-w-pipeline/index.html cont_1:/usr/local/apache2/htdocs/index.html
note that you need to stop the container and run it again
docker stop cont_1
docker start cont_1

hence you will see the new index file displayed to your website 
