# Nova Tools

Un ensemble d'outils pour modifier les fichiers dans Nova, afin que nous puissions obtenir une traduction!


##AIF to GXT (aif_to_gxt.py) [Developed by Nagato]
Convertit les fichiers AIF en fichiers GXT, à utiliser avec GXTConvert. (Fonctionne uniquement avec Python 2!)

Cela convertira un fichier AIFF en TXT, puis automatiquement en PNG.

##GXT Convert (GXTConvert.exe) [Developed by [xdaniel](https://twitter.com/xdanieldzd)]
Cela convertit les fichiers GXT en PNG.

##psnova-texteditor [Developed by Nagato]
Comprend deux parties: psnova-texteditor et psnova-textinserter.  
  
psnova-texteditor est un programme GUI qui vous permet d'afficher n'importe quel fichier .rmd situé dans le dossier "scripts" du même dossier que le fichier EXE. Cet outil peut également être utilisé pour transférer toutes les chaînes dans des fichiers PNG distincts pour les afficher en dehors de l'application.. NOTE: Vous devez aussi avoir BasicCharSet.rmd ET BasicRubySet.rmd disponible dans le dossier scripts pour une compatibilité maximale.    
  
psnova-textinserter est un programme CLI qui utilise le fichier translations.json de psnova-texteditor pour générer de nouveau fichier .rmd. Les fichiers .rmd d'origine doivent être situés dans le dossier "scripts" du même dossier que le fichier EXE.
  
##NovaParse [Developed by [Kyle873](https://github.com/Kyle873)]
Cet outil utilise les fichiers JSON comme entrée pour insérer les données de traduction dans le fichier JSON maître afin de créer le correctif final.
