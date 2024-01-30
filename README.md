# Build image

```
git clone https://github.com/asapoka/Tomcat5-5Image.git && \
cd Tomcat5-5Image && \
docker image build -f ./tomcat/Dockerfile --tag tomcat:5.5-jdk8-openjdk .
```

# test run

```
docker compose up -d
```

# open url

http://localhost:8080/
