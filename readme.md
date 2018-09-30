kubectl create clusterrolebinding default-admin --clusterrole cluster-admin --serviceaccount=default:default
1. mvn clean install
2. build docker image
 ex. docker build -t piomin/employee:1.0 .