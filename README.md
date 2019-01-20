# Customiser son super terminal!

Je me suis inspiré (c'est plus classe que de dire que je l'ai juste traduit en refaisant juste des screens non? 😇) de [ce guide](https://medium.freecodecamp.org/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38) extrèmement bien fait en anglais.

## Le résultat attendu:

Le but est d'obtenir un affichage **plus clair** du *dossier* dans lequel nous sommes mais également de voir constament dans quel *branch* de git nous sommes.
Mais ce n'est pas le seul objectif. Soyons honnête, il est plus agréable de travailler sur un terminale coloré et clair que sur une fenêtre noire et blanche toute moche! Vous verrez, on se sent comme un vrais Hacker avec un terminal comme ça! 😝

Personne ne veut se retrouver à taper des heures sur un terminal que ressemble à ça:

![terminal mac](screen/screen1.jpg)


Voyons le résultat que nous obtiendrons à la fin:
![Résultat attendu ](/screen/screen-presentation.jpg)
Déja mieux non? Alors c'est partit!

## Guide d'installation

### 1. installer ITerm2
Nous allons remplacer notre vieux terminal tout moisi (mais bien meilleur que celui de windows quand même hein 😉) par un super terminal ultra performant! Pour cela, nous allons nous rendre sur le site d'[Iterm 2](https://www.iterm2.com/). cliquer sur download, enregister le fichier .zip et l'ouvrire.
![download iterm2](screen/screen2.jpeg)

Nous nous retrouvons avec l'appliquation super! Sauf que normalement elle se trouve dans nos téléchargement et ce n'est pas vraiment ce qu'on veut... Nous allons donc la déplacer dans le dossier application.
![move iterm2 to apps](screen/screen3.jpg)

Ouvrons **ITerm 2** pour voir ce que ça donne:
![Iterm 2](screen/scree4.jpg)
Pas terrible hein... Et bien customisons notre nouveau super terminal!

### 2. Installer HomeBrew
Nous allons installer HomeBrew. Mais qu'est ce que HomeBrew me demanderez-vous? (et si pas, bah vous êtes vraiment pas curieux!)
Et bien c'est un gestionnaire de paquet. C'est à dire que ça va vous permettre d'installer des programmes directement depuis votre terminale.
Je vais pas m'étendre plus que ça sur les gestionnaire de paquets, si ça vous interesse je vous recommande cette page [Wikipédia](https://fr.wikipedia.org/wiki/Gestionnaire_de_paquets).

Asser discuter, tapons la commande qui permet de l'installer directement depuis le terminal *(nous allons désormais remplacer le terminal par ITerm2, donc quand je parlerai de terminal ça voudra dire Iterm2)* :
`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

![HomeBrew install](screen/screen5.jpg)






