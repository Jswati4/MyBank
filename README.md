# Jenkins Agent personnalisé avec Composer

Cette image Docker sert d'agent Jenkins personnalisé, incluant Composer pour gérer le backend PHP.

## Utilisation

- Construire l'image : `docker build -t jenkins-agent-composer .`
- Pousser vers un registre : `docker push ton-utilisateur/jenkins-agent-composer:latest`
- Configurer Jenkins pour utiliser cette image comme agent.

## Repository

[Voir le code source ici](https://github.com/Jswati4/MyBank.git)
