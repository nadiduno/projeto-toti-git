[![Author](https://img.shields.io/badge/Dev-Nadi%20Duno-blueviolet%20)](https://portfolio-nadi.vercel.app/)
[![Social](https://img.shields.io/twitter/follow/nadiduno?label=%40nadiduno&style=social)](https://twitter.com/nadiduno)
[![Linkedin](https://img.shields.io/badge/in-Nadi%20Duno-blue)](https://www.linkedin.com/in/nadiduno/)
<br />
<br />

# toti-aula-git
Repositório para a aula de git da Toti

## Resolvendo conflitos entre as branch

```bash

# Previo modifica o README no repositório remoto (Git Hub) e commita
# Criando uma branch
$ git checkout -b feature-readme
# Modifica o README no repositório local (tua pc) e commita
$ git add README.md
$ git commit -m 'Update README'
$ git status
$ git push
# Aqui da um erro e recomenda fazer um push da nova branch
$ git push --set-upstream origin feature-readme
$ git push
$ git checkout main
$ git merge feature-readme
$ git push
# Aqui da o conflito, já que previamente tinhamos modificado o README no repositório remoto
$ git pull
$ git config pull.rebase false
$ git pull
# Aqui temos que tomar a decisão de que código conversar, e fazer o merge a mão
$ git add README.md
$ git commit -m 'Solve conflict README'
$ git status
$ git push

```

### No BootCamp

🚀 [Toti Diversidade](https://totidiversidade.com.br/) 
Professor [Jão jpwieland](https://github.com/jpwieland)

<br />

By DevRel <💜 /> [Nadi Duno](https://www.linkedin.com/in/nadiduno/) © 2023


