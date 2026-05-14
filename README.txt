This is my POS built with VueJS 3 framework-CDN that is running on Docker.

Docker Commands 

Create a file called Dockerfile - This holds the configuration/specification of your computer.
Run the command docker build -t vue-pos . - This is building the computer (image) specified in the Dockerfile. -t means tagname.
Run the command docker run -p 2000:80 -d -t vue-pos - This powers the computer (container). 5000 means the external port (host) 80 exposes the NGINX
in the container -t is the image created above. -d makes the container run in the background even if you close the terminal.
