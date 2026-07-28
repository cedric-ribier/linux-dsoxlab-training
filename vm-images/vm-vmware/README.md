# VM de base — VMware (l1 fondamentaux)

Image OVA prête à l'emploi pour démarrer les labs sans étape d'installation manuelle du système.

>Assurée vous que votre machine hôte peut faire de la virtualisation imbriqué.

## Contenu
- OS : Debian 12
- Outils préinstallés : git, curl, wget, uv, dsoxlab
- Utilisateur par défaut : user / MotDePasse  (à changer au premier boot)
- Utilisateur root : root / MotDePasse123!  (à changer au premier boot)

## Import
Télécharger l'OVA : https://github.com/cedric-ribier/linux-dsoxlab-training/releases/download/v1.0-base-vm-vmware/linux-dsoxlab-training-vmware.ova

## Installation
1. Double clic sur le fichier ou VMware Fusion/Workstation : Fichier → Ouvrir → sélectionner le .ova
2. Démarrer la VM, se connecter avec les identifiants ci-dessus

## Vérification
1. Ce placer dans le répertoire linux-dsoxlab-training
   ``` cd ~/linux-dsoxlab-training ```
2. dsoxlab doctor

## Notes
- Image générée avec ovftool
- Testée sur VMware Fusion Version professionnelle 13.6.2 (24409261)
- Testée sur VMware Workstation Professionnel 17.5 
