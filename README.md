# Test 

Pour mener ce test à bien, vous recevrez les accès à une machine virtuelle (Ubuntu + Docker préinstallés).
Cette machine virtuelle dispose d'une adresse **IP_VM** fixe.

### Ce qui est attendu


- [ ] Une installation fonctionnelle de GitLab CI avec un agent local
- [ ] L'accès à **http://IP_VM/ci** doit permettre de consulter l'interface Gitlab
- [ ] Build d'un projet Java + Dockerfile 
- [ ] Build d'un projet NodeJS + Dockerfile
- [ ] Déploiement en local de l'application Java avec un accès en utilisant l'URL **http://IP_VM/apis**
- [ ] Déploiement en local de l'application NodeJS avec un accès en utilisant l'URL **http://IP_VM/app**

Pour exposer les URLs mentionnées précédemment il est nécessaire de déployer une instance **NGINX**
