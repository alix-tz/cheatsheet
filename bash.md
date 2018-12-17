# Commandes pour bash

## retirer une partie de nom de fichier de manière récursive:
```
// retirer '_duplicated' dans les noms de fichiers xml : 

for f in *_duplicated.xml; do mv -- "$f" "${f%_duplicated.xml}.xml"; done
```
