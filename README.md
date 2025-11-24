# Mini scanner de ports TCP (Bash)

## Description
Outil simple de reconnaissance réseau permettant de vérifier l'accessibilité de ports TCP courants :
- SSH (22)
- HTTP (80)
- HTTPS (443)
- SMB (445)
- FTP, SMTP, MySQL, etc.

## Fonctionnement
Test basé sur /dev/tcp pour mesurer l'ouverture ou la fermeture d'un port.

## Utilisation
```bash
chmod +x portscanner.sh
./portscanner.sh <IP>
