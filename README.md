## This is a sample config files to use kkubernetes config map as config server
A sample rest service is exposed to check the value 


i.e.  below get request

<ip>:<port>/kube/
  
 Now change the config Map
 
 Then 
 
 curl -X POST <ip>:<port>/actuator/refresh -d {} -H "Content-Type: application/json".
  
 Then check again without restart
 
 <ip>:<port>/kube/



