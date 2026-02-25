# MDD
Développez une application full-stack complète

### 🔄 Téléchargement 🔄
1. Téléchargez ou clonez le projet.
2. Nécessite les éléments suivants :
    - Angular 18
    - Apache Maven
    - Java 24
    - NodeJS
    - PHP
    - PHPMyAdmin

### 💻 Installation 💻
1. Effectuez la commande : `npm install` dans le répertoire front
2. Effectuez la commande : `maven clean install` dans le répertoire back

### ⚙️ Configuration ⚙️
1. Créez vos variables d'environnements :
1.1 `P6_OC_API__JWT` ayant pour valeur une clé de cryptage de 256bits
1.2 `SPRING_DATASOURCE_USERNAME` ayant pour valeur l'identifiant d'accès à votre base de données
1.3 `SPRING_DATASOURCE_PASSWORD` ayant pour valeur le mot de passe d'accès à votre base de données
2. Configurez le fichier `application.properties`:
2.1 Mettez vos informations de base de données (pensez à la créer sur PhpMyAdmin)
2.2 Choississez le répertoire où seront stockés vos photos (vous pouvez laissez tel quel)
3. Importez sur votre base de données le fichier SQL présent à la racine `mdd.sql`
4. Modifier le fichier `proxy.conf.json` dans front/src, mettez la bonne URL pour l'API dans le back

### ✅ Démarrage ✅
1. Effectuez la commande : `npm run start` dans le répertoire front
2. Effectuez la commande `mvn spring-boot:run` dans le répertoire back

### Compétences acquises
- Intégrer le front-end et le back-end d'un programme en utilisant une API
- Valider une documentation des outils de développement choisis dans le contexte d'un projet
