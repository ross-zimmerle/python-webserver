# Use the specified image as the base
FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Update the package lists
RUN apt-get update 

# Install poetry using pipx
RUN pipx install poetry

# Expose port 3000
EXPOSE 3000

# Set the user to appuser
USER appuser

# Healthcheck
# HEALTHCHECK CMD curl --fail http://localhost:3000 || exit 1