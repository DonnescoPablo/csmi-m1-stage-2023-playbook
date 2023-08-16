# csmi-m1-stage-2023-playbook
Projet playbook - rapport de stage pour le Master 1 Calcul Scientifique et Mathématiques de l'Information (CSMI) - 2023

## Cloner ce repository

`git clone git@github.com:DonnescoPablo/csmi-m1-stage-2023-playbook.git`

## Installer localement Antora

En supposant `Node.js` installé, installer localement Antora en exécutant

```
node -e "fs.writeFileSync('package.json', '{}')" && npm i -D -E @antora/cli@3.1 @antora/site-generator@3.1
```

Vérifier que la commande `antora` fonctionne:

`npx antora -v`

## Générer le site

`npx antora --fetch antora-playbook.yml`

## Ouvrir le site

`open build/site/index.html`