# VM de base — VirtualBox (l1 fondamentaux)

Image OVA prête à l'emploi pour démarrer les labs sans étape d'installation manuelle du système. 

>Assurée vous que votre machine hôte peut faire de la virtualisation imbriqué.

## Contenu
- OS : Debian 12
- Outils préinstallés : git, curl, wget, uv, dsoxlab
- Utilisateur par défaut : user / MotDePasse (à changer au premier boot)
- Utilisateur root : root / MotDePassFort123! (à changer au premier boot)
## Import
1. Télécharger l'OVA : https://github.com/cedric-ribier/linux-dsoxlab-training/releases/tag/v1.0-base-vm
2. VirtualBox : Fichier → Importer une application virtuelle → sélectionner le .ova
3. Démarrer la VM, personnalisé l'interface réseau, se connecter avec les identifiants ci-dessus

## Vérification
dsoxlab doctor

## Notes
- Image générée avec VBoxManage export --ovf20 --manifest
- Testée sur VirtualBox Version 7.1.6 r167084 (Qt6.5.3) / Version 7.2.10 r1741663 (Qt6.8.0 on windows) / Version 7.2.8 r173730 (Qts6.8.0 on Windows)
