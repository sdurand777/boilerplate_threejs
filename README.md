


# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
# En repartant de ce boilerplate ne pas oublier de delete les dossiers dist et nodes_module car il y a des cache dedans ainsi que le fichier package-lock.json
# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

npm init -y

npm install three --save-dev
npm install vite --save-dev

# voir dans le fichier package.json ce que fait la commande dev dans la partie scripts
npm run dev


# exp_threejs


# install modern gui
npm install lil-gui 

# install gh-pages for github hosting
npm install gh-pages --save-dev

# pour le deploiement
# build le dossier dist
npm run build 
# preview le rendering en local
npm run preview
# deploy en ligne
npm run deploy

# aller dans le repo github dans settings puis dans pages et selectionner 
branch :  gh-pages (doit apparaitre en dessous du main apres le deploy)
et garder root et cliquer sur save


# pour les textures ne pas oublier de copier les fichiers images et ply dans le dossier dist cree apres npm run build


# boilerplate_threejs

