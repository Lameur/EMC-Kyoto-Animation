# Utilisez une image de base
FROM mcr.microsoft.com/devcontainers/universal

# Installez les dépendances supplémentaires
RUN apt-get update && apt-get upgrade -y

# Install mise
RUN curl https://mise.run | sh

# Exposez le port 4000
EXPOSE 4000
