# Docekris-python-applications
Python application examples in Docker containers
The folder pytorch dataloder docker is an example of using docker with pytorch dataloder 
To run this example you should have a path similar to the follwing:
```
main_dir -----|rps
              |rps_val
              |Dockerfile
              |csv files 
              |python scripts 

```
To make your docker:

>>docker build -f Dockerfile -t [your_docker_image_name] .

>>docker run --name rsp-docker-cont -v C:\Users\rsp_docker:/usr/src/app rsp-docker


              
              
