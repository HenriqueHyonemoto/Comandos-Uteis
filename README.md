# ComandosUteis
# Subir para o git pela primeira vez
_>abra o terminal dentro do seu diretorio_
```
git config --global user.name "HenriqueHyonemoto"
```
```
git config --global user.email "henrique.hyonemoto@aluno.ifsp.edu.br"
```
```
git init
```
```
git add .
```
```
git commit -m "Colocar uma descricao"
```
_>Cole o link do seu repositorio depois de origin, desta forma:_

_>git remote add origin https://github.com/HenriqueHyonemoto/repositorio.git_
```
git remote add origin 
```
```
git branch -M main
```
```
git push -u origin main
```
# Fazer atualizações em repositorios
```
git add .
```
```
git commit -m "Colocar uma descricao"
```
```
git push -u origin main
```

# Deslogar do Git
_>apenas cole os comandos._
```
git config --global --unset user.name
```
```
git config --global --unset user.email
```


# Caso erro de conflito em commit
```
git config pull.rebase false
```
```
git pull
```
```
git push -u origin main
```

# Renomear arquivos com sequencia numerica
```
ls -v | cat -n | while read n f; do mv -n "$f" "$n.ext"; done
```
>mude esta parte: "$n.ext" (exemplo: "Nome$n.png", o resultado sera: Nome1.png,Nome2.png,Nome3.png,)

>$n é o número (mantenha desta forma)

>.ext é para especificar a extensão (.png .jpg .pdf)
