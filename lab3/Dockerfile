FROM openjdk

#creating working dir
WORKDIR /app 

# copy from source-current-dir(.) to destination(/app)
COPY . /app

#compile java file
RUN javac DockerTesting.java

# execute class file
CMD ["java", "DockerTesting"]
