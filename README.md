# GCC-Docker-Image

Usage: Clone this repo, then add C files you want to compile to the test_files folder. 

Then, run the following commands to build and run the image:

docker build -t gccshell .
docker run -it gccshell

In this shell you can use gcc and cat to view the output of files
To exit the container, type exit
