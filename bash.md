# Commandes pour bash

## retirer une partie de nom de fichier de manière récursive:
```
// retirer '_duplicated' dans les noms de fichiers xml : 

for f in *_duplicated.xml; do mv -- "$f" "${f%_duplicated.xml}.xml"; done
```

## Modifier le début de noms de fichiers (mmv)
```
sudo apt-get install mmv

mmv a\* b\#1
```
