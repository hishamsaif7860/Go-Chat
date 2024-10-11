# Go-Chat
A distributed messaging system enables multiple components to send, receive, and manage messages, distributing workload across nodes for scalability, reliability, and fault tolerance. Used in business messaging, real-time communication, and IoT. Examples include Apache Kafka, RabbitMQ, and Apache Pulsar.

# Running the Application 
docker-compose up -d
docker exec -it testcass cqlsh

# web socket Connection 
wscat -c ws://localhost/chat?id=Saif

# private chat - WebSocket 

{"msg":"hello saif, how are you ? ","receiver":"2fuzqIfui2g05IRH5vu5WNOxBLV","is_group":false}
{"msg":" Im good, Thank you mark","receiver":"  ","is_group":false}

# group chat - webSocket 

{"msg":"hello everyone","is_group":true, "Group_name":"Facebook"}
{"msg":"everyone is here, lets start","is_group":true, "Group_name":"Facebook"}


