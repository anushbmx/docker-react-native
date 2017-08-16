# Docker container for building Android React Native apps


Build on ubuntu 16.10

Contains the following android packages 

### Android SDKs
* android-26
* android-25
* android-24
* android-23
* android-18
* android-16

### Android build tools
* build-tools-26.0.1
* build-tools-26.0.0
* build-tools-25.0.3
* build-tools-25.0.2
* build-tools-25.0.1
* build-tools-25.0.0
* build-tools-24.0.3
* build-tools-24.0.2
* build-tools-24.0.1
* build-tools-23.0.3
* build-tools-23.0.2
* build-tools-23.0.1

### Extras 
* extra-android-m2repository
* extra-google-m2repository
* extra-google-google_play_services

Node Version : 8.3.0

Yarn is added to save 15 precious seconds.

### Pull from Docker Hub
```
docker pull anushbmx/docker-react-native-android:latest
```

### Build from GitHub
```
docker build -t anushbmx/docker-react-native-android github.com/anushbmx/docker-react-native-android
```

### Run image
```
docker run -it anushbmx/docker-react-native-android bash
```

### Use as base image
```Dockerfile
FROM anushbmx/docker-react-native-android:latest
```
