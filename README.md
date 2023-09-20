# :page_facing_up: Comandos Uteis 
# :arrow_up: Subir para o git pela primeira vez 
   >`abra o terminal dentro do seu diretorio`
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
---
$$\space$$
>`Coloque a descrição que preferir no lugar entra aspas:"commit"`
```
git commit -m "commit"
```

---
$$\space$$
>`Cole o link do seu repositorio depois de "origin", desta forma:`

>`git remote add origin https://github.com/HenriqueHyonemoto/repositorio.git`
```
git remote add origin 
```
---

```
git branch -M main
```
```
git push -u origin main
```
# :heavy_plus_sign: Fazer atualizações em repositorios 
```
git add .
```
```
git commit -m "descrição"
```
```
git push -u origin main
```

# :arrow_down: Deslogar do Git 
>`apenas cole os comandos.`
```
git config --global --unset user.name
```
```
git config --global --unset user.email
```


# :hammer: Caso erro de conflito em commit 
```
git config pull.rebase false
```
---
$$\space$$
>`Cole o link do seu repositorio depois de "pull", desta forma:`

>`git pull https://github.com/HenriqueHyonemoto/repositorio.git`
```
git pull
```
---

```
git push -u origin main
```

# :pencil2: Renomear arquivos com sequencia numerica (Linux) 
```
ls -v | cat -n | while read n f; do mv -n "$f" "$n.ext"; done
```
>`mude esta parte: "$n.ext" (exemplo: "Nome$n.png", o resultado sera: Nome1.png,Nome2.png,Nome3.png,)`

>`$n é o número (mantenha desta forma)`

>`.ext é para especificar a extensão (.png .jpg .pdf)`
