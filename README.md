# Infra IA JL

Ce dépôt contient une stack complète pour déployer plusieurs services orientés IA et automatisation :

- **n8n** : Plateforme d’automatisation et d’orchestration de workflows  
- **Qdrant** : Moteur de vectorisation pour la recherche sémantique  
- **Baserow** : Base de données no-code / low-code  
- **Docling** : Parser optimisé pour les LLMs 
- **Ollama** : Serveur local LLM (permet de télécharger et d’héberger des modèles comme Mistral, Llama2, etc.)

## Prérequis

- Un serveur Linux (Ubuntu/Debian conseillé)  
- Docker & Docker Compose installés (ou bien le plugin Docker Compose)  
- Accès SSH au serveur  
- (Optionnel) Un nom de domaine + un reverse proxy si vous souhaitez accéder aux services de manière sécurisée via HTTPS.

## Installation

### 1. Cloner ce dépôt

```bash
git clone https://github.com/Stirito/infra_ia_jl.git
cd infra_ia_jl
