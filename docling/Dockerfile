# Choix de l'image de base
FROM python:3.10-slim

# On définit le répertoire de travail
WORKDIR /app

# Installation de docling-serve
RUN pip install --no-cache-dir --upgrade pip \
    && pip install --no-cache-dir docling-serve

# On documente (expose) le port, ici 5001 (par défaut)
EXPOSE 5001

# Commande de démarrage
CMD ["docling-serve", "run"]
