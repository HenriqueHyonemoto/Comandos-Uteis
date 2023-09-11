# ComandosUteis

# Renomear arquivos com sequencia numerica
```
ls -v | cat -n | while read n f; do mv -n "$f" "$n.ext"; done
```
mude esta parte: "$n.ext" (exemplo: Nome$n.png)

$n é o número (mantenha desta forma)

.ext é para especificar a extensão (.png .jpg .pdf)
