Created a Dockerfile that uses Ubuntu as the build image and scratch as the final image
Installed Go and built the application with CGO disabled
Copied the executable from the build stage to the final stage
Set the entry point to the application executable
Resulting image is minimal and secure, with a size of [X] MB
