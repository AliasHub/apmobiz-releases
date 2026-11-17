# AppMobiz – installateurs

Ce dépôt contient uniquement les installateurs publiés d'AppMobiz (aucun code source).

## API Sage (Windows)

Dernière version, lien permanent :

https://github.com/AliasHub/apmobiz-releases/releases/latest/download/AppMobizSageApi-Setup.exe

Avant de lancer l'installateur, comparez son empreinte avec le SHA-256 indiqué dans les notes de la release :

```powershell
Get-FileHash .\AppMobizSageApi-Setup.exe
```

L'exécutable n'est pas signé : Windows SmartScreen affiche un avertissement (« Informations complémentaires » puis « Exécuter quand même »). À lancer en administrateur.
