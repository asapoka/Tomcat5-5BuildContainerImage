# Build image

```
git clone https://github.com/asapoka/Tomcat5-5BuildContainerImage.git && \
cd Tomcat5-5BuildContainerImage && \
docker image build -f ./tomcat/Dockerfile --tag tomcat:5.5-jdk8-openjdk .
```

```
docker compose up -d
```

# oopen url

http://localhost:8080/
