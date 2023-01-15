###### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repository 

    docker tag java-app demo-app:java-1.0
    
