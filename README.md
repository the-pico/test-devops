# Test 

Pour mener ce test à bien, vous recevrez les accès à une machine virtuelle (2CPU, 4Go RAM, 80 Go Disk, Ubuntu, Docker préinstallé).
Cette machine virtuelle dispose d'une adresse adresse fixe (**IP-VM**).

Ce test devrait être finalisé au plus tard le **vendredi 11/12**.

### Ce qui est attendu


- [ ] *Toutes les installations/configurations* doivent se faire dans le dossier `opt` 
- [ ] Une installation fonctionnelle de GitLab CI avec un agent local
- [ ] L'accès à **http://IP-VM/ci** doit permettre de consulter l'interface Gitlab
- [ ] Build d'un projet Java + Dockerfile 
- [ ] Build d'un projet NodeJS + Dockerfile
- [ ] Déploiement en local de l'application Java avec un accès en utilisant l'URL **http://IP-VM/apis**
- [ ] Déploiement en local de l'application NodeJS avec un accès en utilisant l'URL **http://IP-VM/app**

Pour exposer les URLs mentionnées précédemment il est nécessaire de déployer une instance **NGINX**

Pour toute question ou demande de clarification, créez une **Issue** pour ouvrir la discussion.
