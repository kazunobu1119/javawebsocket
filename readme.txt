1. install the jdk-17
2. setting the environment
This PC/ Properties/ Advanced system settings/Environment Variables/System variables/ New/
Variable name: JAVA_HOME
Variable value: C:\Program Files\Java\jdk-17

3. change the address. "complete\src\main\resources\static\app.js"->  
goto line 2: brokerURL: 'ws://192.168.145.121:8080/gs-guide-websocket'
change "192.168.145.121" to your IP address.
4. go to "complete" folder and run the follow command
cmd -> mvnw spring-boot:run
5.go to your browser and input "localhost:8080" in the url


That's all. Thank you!