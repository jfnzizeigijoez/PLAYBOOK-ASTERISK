# PLAYBOOK-ASTERISK

# Ansible Playbook pour Déploiement Asterisk

Ce playbook Ansible automatise l'installation et la configuration d'Asterisk.

## Description

Le playbook installe Asterisk, incluant les dépendances et la configuration de base.

## Prérequis

*   Ansible installé.
*   Accès SSH avec sudo.
*   Connexion Internet.

## Inventaire

Configurez votre fichier `inventory` avec les détails du serveur cible.

## Utilisation

1.  Clonez le playbook.
2.  Modifiez l'inventory avec l'ip de la machine cliente.
3.  Exécutez le playbook :

    ```
    ansible-playbook -i inventory deploy.yml
    ```


    Après l'exécution du playbook, connectez-vous a la machine cliente via SSH et exécutez :

        ```
        asterisk -vvvvc
        ```        
## Contribution

Les contributions sont les bienvenues.
