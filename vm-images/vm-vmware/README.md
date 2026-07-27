# VM de base — VMware (l1 fondamentaux)

Image OVA prête à l'emploi pour démarrer les labs l1 sans étape d'installation manuelle du système.

## Contenu
- OS : Debian 12
- Outils préinstallés : git, curl, wget, uv, dsoxlab
- Utilisateur par défaut : user / MotDePasse  (à changer au premier boot)
- Utilisateur root : root / MotDePasse123!  (à changer au premier boot)

## Import
1. Télécharger l'OVA : https://github.com/cedric-ribier/linux-dsoxlab-training/releases/download/v1.0-base-vm-vmware/linux-dsoxlab-training-vmware.ova
2. VMware Fusion/Workstation : Fichier → Ouvrir → sélectionner le .ova
3. Démarrer la VM, se connecter avec les identifiants ci-dessus

## Vérification
dsoxlab doctor

## Notes
- Image générée avec ovftool
- Testée sur VMware [version]
