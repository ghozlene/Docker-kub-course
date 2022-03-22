# Docker-kub-course
#a course About docker and kubernetes

1/Project 1:************************************************************

after initial our porject just run the commande : docker build .  to build and image from the Dockerfile 

to run our container localy: docker run -p 3000:3000 e7f387a34dbe7185c7c52de75e3c496904b81e23e3dd825f7ab9e75905e2538c 

then just go to the browser and localhost:3000 and it will open         

2/project 2:************************************************************

the beginning is the same 

when we change something in our code it does't reflect on the image cz the image is just read only that's why we need to rebuild it everytime we change the code

docker when he recognaize the file changes he rebuild all the file after that change that means he rebuild node modules too that why it takes more time to generate

new image 


