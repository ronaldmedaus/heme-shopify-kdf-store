Pour réaliser le TEST

Pour réaliser l'exercice 1

- Je commence par créer un dossier dans la racine de mon ordinateur (disc->Utilisateur->Création du dossier)
- je crée une boutique de developpement sur https://partners.shopify.com
- Je vais dans Application -> Toutes les applications -> Créer une application manuellement(IMPORTANT: Copier le mot de passe dans un bloc note)

J'initialise le projet en créer mon environnement de travail

- je lance le dossier dans le terminal
- je vais sur le site  de shopify  https://shopify.dev/concepts/apps ) pour la docummentation
- J'initialise le projet Shopify  avec ces lignes de codes (pour macOS)
brew tap shopify/shopify
brew install shopify-cli

info(si le Mac à la puce M1) faut aller chercher la ligne de commande pour le "Xcode 13.4."
Alternatively, manually download them from:
  https://developer.apple.com/download/all/.
You should download the Command Line Tools for Xcode 13.4.

- je crée un theme kit Shopify avec ces lignes de codes : theme new --password=shptka_8ea057724752355c4fc46548480e2256 --store=kdfshop.myshopify.com --name="kdf-store"

-J e retourne sur ma boutique, je vais dans BOUTIQUE en ligne -> clic sur Mon nouveau THEME -> ACTION -> PUBLIER 

- J'initialise un Dépôt Git

- Pour gagner du temps, j'instale PREPOS pour compiler automatiment les fichiers pour pouvoir recharger mes fichiers à chaque modification.
- J'utilise également un RESET_CSS uniform sur tout les navigateurs