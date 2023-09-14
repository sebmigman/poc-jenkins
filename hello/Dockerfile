# Use the Alpine Linux base image
FROM alpine:latest

# Copy the Bash script into the container
COPY hello.sh /usr/local/bin/

# Set execute permissions on the script
RUN chmod +x /usr/local/bin/hello.sh

# Run the Bash script when the container starts
CMD ["hello.sh"]

