FROM ruby:3.2

# Update the system and install necessary tools
RUN apt-get update && apt-get install -y \
    build-essential \
    libpq-dev \
    nodejs

# Install Bundler
RUN gem install bundler

# Set the default work directory
WORKDIR /workspace

# Any other environment setup you want can go here
