# INFRA//LAB — Network Engineer Simulator

Un jeu original d'apprentissage réseau fonctionnant dans un navigateur moderne. Il est inspiré du thème des simulateurs réseau, sans reprendre le code, les assets ou la marque d'un jeu commercial.

## Fichiers
- `index.html` : structure de l'application.
- `style.css` : interface responsive Cyber Tech.
- `script.js` : topologie interactive, terminal simulé, configuration IP/VLAN, missions et progression.

## Lancer en local
Ouvrez `index.html` dans un navigateur moderne. Aucun serveur, aucune installation et aucune dépendance externe ne sont nécessaires.

## Publier sur GitHub Pages
1. Créez un dépôt GitHub public, par exemple `infra-network-lab`.
2. Cliquez sur **Add file → Upload files** et importez les trois fichiers à la racine du dépôt.
3. Cliquez sur **Commit changes**.
4. Allez dans **Settings → Pages**.
5. Sous **Build and deployment**, choisissez **Deploy from a branch**.
6. Sélectionnez `main` et `/(root)`, puis **Save**.
7. Attendez le déploiement et ouvrez l'URL affichée dans Settings → Pages.

## Contrôles
- Cliquez sur PC / Switch / Router / Server pour ajouter des équipements.
- Activez **Cable mode**, puis cliquez sur deux équipements pour créer un lien.
- Glissez les équipements pour changer leur position.
- Cliquez sur un équipement pour modifier son IP, masque et VLAN.
- Terminal : `help`, `show devices`, `show ip`, `show vlan`, `ping PC-02`, `connect PC-01 SW-01`, `mission status`, `clear`.
- Cliquez sur **Validate mission** quand l'objectif est rempli.

## Important
C'est une simulation pédagogique exécutée côté navigateur. Les pings, VLANs, l'état des ports et les commandes ne pilotent pas de vrais équipements et n'envoient pas de paquets réseau réels. La progression est gardée en mémoire uniquement pendant la session, et un rechargement réinitialise le lab.
