# ComandosUteis

# Renomear arquivos com sequencia numerica
```
ls -v | cat -n | while read n f; do mv -n "$f" "$n.ext"; done
```
mude esta parte: "$n.ext" (exemplo: "Nome$n.png", o resultado sera: Nome1.png,Nome2.png,Nome3.png,)

$n é o número (mantenha desta forma)

.ext é para especificar a extensão (.png .jpg .pdf)
