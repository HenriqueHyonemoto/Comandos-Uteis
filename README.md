# ComandosUteis

#Renomear arquivos com sequencia numerica
```
ls -v | cat -n | while read n f; do mv -n "$f" "$n.ext"; done
```
