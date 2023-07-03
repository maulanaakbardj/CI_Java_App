# GitHub Actions Docker Build And Push #
### Basic Demo CI/CD Pipeline with Docker using Github Actions

![Untitled Diagram](https://user-images.githubusercontent.com/67249292/201534930-25fe655a-7f7b-4d3e-b52c-be3ffab60612.jpg)

## build the Java project

    ./gradlew build

## build Docker image called java-app, execute from root

    docker build -t java-app .
    
## push image to repo 

    docker tag java-app demo-java-app:java-1.0
    
