# Cloud.Oracle_Aws-Nginx-Terraform
Deployment auto d'une portal captif sur Oracle-cloud &amp; Aws avec Nginx (Pour la partie Web) et Terraform (Pour l'automatisation)

##Technologies & Competences
### Infrastructure Cloud
- Fournisseurs :
    * Amazon Web Service
    * Oracle Cloud Infrastructure
- Instances : EC2 et AD1
- Serveur Web : Nginx

### Outils Utilises
- Git
- Bash
- SSH/MobaXtrem
- Nginx

## Architecture du projet
- `infrastructure/` : Configuration du cloud
- `portal_captif/` : Code source HTML, CSS, JS
- `script/` : script d'automatisation Nginx, ...

### Installation 
1. Cloner le repository
```bash
git clone https://github.com/TatumLn/Cloud.Oracle_Aws-Nginx-Terraform.git
```
2. Configuration Nginx
# Script d'installation automatique
```bash
./script/nginx-install.sh 
```
ou
```bash
sh /script/nginx-install.sh 
```

### Ameliorations Futures
 * Ajout de monitoring
 * Implementation de CI/CD (Jenkins, ...)
 * Conteneurisation Docker

### Contact
 * Email: zafiniainahermaprosper@gmail.com
