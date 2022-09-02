# docker-project-of-hello-world-python

 This is a personal project, in which we can print hello-world-python in a localhost using DOCKER


 Command to use :
  1. docker build -t in28min/hello-world-python:0.0.2.RELEASE .
  // this will build an image in docker and this last is very important so do no  t forget to put it

  2. run -p 5000:5000 -d in28min/hello-world-python:0.0.2.RELEASE

  3. go and search the local host in browser by typing "localhost:5000"
