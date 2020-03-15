# gokit

This is a sample goKit service with prometheus and logging enabled
It has Hashicorp consul integration enabled.

After you compile the service, just run main.go and you should be able
to hit the localhost:8080/healthcheck endpoint and see true as response

you can see the basePath and serverOptions printed on the console, those 
variables are used to create new endpoints. You can delete the 
println statements after using those variables.