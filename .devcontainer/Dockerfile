# Utiliser une image de base avec Ruby préinstallé
FROM mcr.microsoft.com/devcontainers/ruby:2

# Installer les dépendances supplémentaires nécessaires pour Jekyll
RUN gem install jekyll bundler

# Définir le répertoire de travail
WORKDIR /workspace

# Copier le Gemfile et le Gemfile.lock dans le conteneur
COPY Gemfile Gemfile.lock ./

# Installer les gems spécifiés
RUN bundle install

# Copier le reste des fichiers du projet
COPY . .

# Exposer le port par défaut pour Jekyll
EXPOSE 4000
