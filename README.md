# Generator
This program gives an example of how to take as input a Service Name with a Resource Definition and then generate a full gRPC client and gRPC server that communicate with one another. There is also support for pushing the server code into a Docker container which can then be deployed and become the gRPC server. This simulates a client communicating with a remote server.

The program sits on top of JavaFx and hence gives a nice (but basic) user interface to play with.

Note: this project doesn't use Maven and hence all the libraries were copied locally. There is also a dependency on the proto compiler executable. Perhaps a pom.xml file will be added in the future to show the libraries that are needed.
