# Nibble

> ⚠️ Il est vraiment important de cloner le dépôt dans le répertoire utilisateur **au même endroit que le dossier .nuget**

## Installation du poste de développeur
### 1. La base
La base c'est bien sûr : un IDE !!!  
- [Visual Studio Code](https://code.visualstudio.com/) est fortement conseillé.  
- [Visual Studio](https://visualstudio.microsoft.com/fr/) (2019 ou plus récent) est aussi très approprié mais moins léger.
> Dans le cas de l'installation de VS Code, les extensions suivantes sont conseillées : [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) et [C# Extensions](https://marketplace.visualstudio.com/items?itemName=jchannon.csharpextensions)

### 2. Téléchargement des outils MonoGame
Tout d'abord il faut installer le SDK .NET Framework 3.1 (aller à 3.1.0 tout en bas) : [lien de téléchargement](https://dotnet.microsoft.com/download/dotnet/3.1)  
Executer le package pour installer le SDK .NET Core 3.1  
Ensuite, ouvrir une invite de commande **PowerShell** et taper les commandes suivantes :  
```
dotnet tool install --global dotnet-mgcb-editor
mgcb-editor --register
```  

### 3. Démarrage du projet
Cloner le dépôt du projet **dans le répertoire utilisateur** (vous n'avez normalement rien à faire, pas de commande `cd`):  
```
git clone https://github.com/TingeFR/Nibble.git
```  
Ouvrir le projet dans VS Code (ou n'importe quel IDE)  
Pour lancer le jeu, il suffit de presser les touches `Ctrl`+`F5`

### 4. Outils d'animation
Installer tout d'abord le .NET Development Pack 4.7.2 : [lien de téléchargement](https://dotnet.microsoft.com/download/dotnet-framework/net472)  
Cloner le dépôt de SpriteFactory :  
```
git clone https://github.com/craftworkgames/SpriteFactory.git
```  
Builder et lancer :
```
cd SpriteFactory
dotnet run --project SpriteFactory
```  

### 5. (Optionnel) Outils supplémentaires
Pour le dessin pixelisé, nous utiliserons **Pyxel Editor** : [lien de téléchargement](https://fr.freedownloadmanager.org/Windows-PC/PyxelEdit-GRATUIT.html)  
Pour les maps, nous utiliserons **Tiled** : [lien de téléchargement](https://www.mapeditor.org/)  
Pour la musique chiptune, nous utiliserons **FamiTracker** : [lien de téléchargement](http://famitracker.com/)

### 6. On code et on s'enjaille !