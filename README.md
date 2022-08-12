# Websurfer_12-08-2022
#Ce GitHub contient le code source du Jeu du Websurfeur. Ce travail fait suite à celui de Grégory Hoareau, qui a commencé l'élaboration du jeu.
#J'ai pu continuer son travail dans le cadre d'un stage de 7 semaines à l'INRIA, et j'y ai développé la focntionnalité Jeu Libre.

# TER-TerraNumerica

## Commandes pour lancer le site

Pour lancer le site, vous aurez besoin d'avoir NodeJS installé sur votre machine, pour vérifier s'il est installé exécuté la ligne de commande suivante : `npm -v`.

[Lien de téléchargement de NodeJS](https://nodejs.org/en/download/).

### Commandes pour lancer le back-end :

Ouvrir un terminal de commande dans le dossier *Terra-Numerica-Backend*

1. Installer les dépendances du back-end
```bash
npm install
```

2. Lancer le site
```bash
npm run start
```
Il faut laisser ouvert le terminal de commande qui à servit pour lancer le back-end, pendant tout le temps d'éxécution du front-end.

### Commandes pour lancer le front-end :

Dans un nouveau terminal de commande depuis le dossir *Terra-Numerica*

1. Installer les dépendances du front-end
```bash
npm install
```

2. Lancer le site
```bash
npm run start
```
Après l'exécution de cette commande, rendez-vous dans votre navigateur sur l'url `http://localhost.com:4200`

### Uniquement dans un environnement Windows :
1. Installer les dependances en utilisant `setup.bat`
2. Lancer le site en utilisant `run.bat`
3. Rendez-vous ensuite à l'adresse http://localhost.com:4200
