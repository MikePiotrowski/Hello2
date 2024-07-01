# These are comments
# I'm learning Java

FROM openjdk:21

# I will create a new directory for my application files
RUN mkdir /app

# Copy the app files from the host machine to the image filesystem
COPY src /app

# Set the directory for executing future commands \
WORKDIR /app

#Compile the Main clas
RUN javac Main.java

# Run the Main class
CMD java Main

