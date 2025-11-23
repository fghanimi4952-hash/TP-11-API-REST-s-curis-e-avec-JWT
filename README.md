#  TP 11 : TERMINÉ ET FONCTIONNEL

## Objectif
Le but de ce TP est de sécuriser une API REST à l’aide du mécanisme JWT (JSON Web Token).
À la différence des sessions classiques, cette approche est stateless :
aucune donnée d’authentification n’est stockée sur le serveur.
Chaque requête contient un jeton signé qui prouve l’identité de l’utilisateur.

À l’issue du TP, on saura :

Créer un endpoint d’authentification REST qui génère un token JWT.
Mettre en place un filtre d’autorisation personnalisé.
Comprendre comment Spring Security intègre le modèle stateless.
Sécuriser les endpoints selon les rôles et droits.


## tester chaque point
1. MySQL installé et démarré
 <img width="885" height="277" alt="Capture d’écran 2025-11-23 à 22 05 29" src="https://github.com/user-attachments/assets/f5bd0fb7-1ab8-47a3-ae61-56bb46ff6417" />
2. Base de données créée
![WhatsApp Image 2025-11-23 at 10 40 10 PM](https://github.com/user-attachments/assets/813dc800-918d-4d06-a85a-9677fddf2277)


3. Application Spring Boot compilée
   <img width="921" height="90" alt="Capture d’écran 2025-11-23 à 22 08 08" src="https://github.com/user-attachments/assets/9187c6ec-7d4d-46fc-b327-a5f391203f5d" />

4. Application lancée et fonctionnelle

<img width="921" height="90" alt="Capture d’écran 2025-11-23 à 22 09 20" src="https://github.com/user-attachments/assets/50f63925-15b6-4036-bed7-c82b8e11bc4a" />

5. Endpoint public testé avec succès

<img width="909" height="769" alt="Capture d’écran 2025-11-23 à 21 42 25" src="https://github.com/user-attachments/assets/be9be26a-a083-45ce-b448-4238b325f55b" />

6. Authentification JWT opérationnelle
   <img width="921" height="140" alt="Capture d’écran 2025-11-23 à 22 29 53" src="https://github.com/user-attachments/assets/edc75165-b00f-45c2-9f31-dcf0d3405bc4" />
