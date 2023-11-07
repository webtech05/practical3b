# practical3b
.docker practical steps:
 2.cd to your directory
 3.cheack docker version
 4.start the docker desktop app
 5.open crome and open docker hub website and search for open idk to insatall java
 6.copy the commands and past it the you working dirctory "docker pull openjdk"
 7.use: "docker ps" commmand to cheack which container is running on that pc
 8.use :"docker images" command to cheack availabe images on the pc
 9.use :"docker run --name java -it -d openjdk" to name the conatiner as java  
 **.use : "docker exec -it java jshell" to run the container
10.run java code like int a=2;int b=4; System.out.println(a+b);
11. Then to exit from the container use command: "/exit"
12 use :"docker ps" to show running containers
13.To  stop the container use "docker stop ID"(id of the container)
14.To remove the container use: "docker conatainer rm ID"(id of the container)
15.Then use: "docker images" to see immages
16.And the use :"docker images prune" to remove all images running
