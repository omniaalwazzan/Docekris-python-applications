# Docekris-python-applications
The folder pytorch dataloder docker is an example of using docker with Pytorch dataloder 

To run this example you should have a path similar to the follwing:
```
main_dir -----|rps
              |rps_val
              |Dockerfile
              |csv files 
              |python scripts 

```
To make your docker:

cd to the main_dir in the CMD then run the follwing command

>>docker build -f Dockerfile -t [your_docker_image_name] .

>>docker run --name [your_docker_container_name] -v C:\Users\main_dir:/usr/src/app [your_docker_image_name]


              
              
