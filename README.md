# http-server
Http server

- curl --request GET -v localhost:8081/something
- curl --request GET -v localhost:8081/status
- curl --request POST -v --data '50,100' localhost:8081/task
- curl --request POST -v --header "X-Test: true"   --data '50,100' localhost:8081/task
- curl --request POST -v --header "X-Debug: true"   --data '50,100' localhost:8081/task
