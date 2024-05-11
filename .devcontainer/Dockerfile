# Use the specified image as the base
FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Set the working directory
WORKDIR /app

# Update the package lists
RUN apt-get update

# Install poetry using pipx
RUN pipx install poetry

# Copy the current directory contents into the container at /app
COPY ../ /app

# Set environment variables
ENV MY_NAME="John Doe"

# Expose port 3000
EXPOSE 3000

# Define the command to run your app using CMD which keeps the container running.
CMD ["poetry", "run", "dev"]

# Set the user to appuser
USER appuser

# Healthcheck
HEALTHCHECK CMD curl --fail http://localhost:3000 || exit 1