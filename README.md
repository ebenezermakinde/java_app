##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t testjava-app .
    
##### push image to repo 

    docker tag testjava-app java-app-demo:0.1
    
