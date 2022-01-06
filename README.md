# Dockerfile---Build-image-with-MySQL-schema
The Dockerfile and sql file for the 2nd assignment of Devops
What to do

    1. Create a Dockerfile and test.sql file
    2. Add the code as required in them, I have also uploaded mine. You can use them as reference
    3. Then in the terminal give the following commands

docker build . -t mytest
docker run -itd mytest
docker exec -it <your container id which you can get by giving command docker ps> bash
mysql -upucsd -p
use pucsdStudents
select * from studentData
