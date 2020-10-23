# WEBINAR GIT & GITHUB

Transmitido no canal da [Pontifícia Universidade Católica de Goiás](https://www.youtube.com/user/PUCGOIAS) pelo VI CONGRESSO DE CIÊNCIA E TECNOLOGIA *Inteligência Artificial: A nova fronteira da ciência brasileira*, o webinar foi produzido afim de compartilhar uma breve introdução teórica e prática do Git & GitHub.
<p>Agradeço muito a todos que participaram. E se você ainda não viu, corre lá e descubra como os Devs viajam no tempo!</p>

<a href="http://www.youtube.com/watch?feature=player_embedded&v=JQeFvtjWk5U
" target="_blank"><img src="capa/capa.png" 
alt="IMAGE ALT TEXT HERE"  border="1" /></a>

## Instalação Git

https://git-scm.com/downloads

- `git --version` // verifica versão do Git
- `git config --global user.name "Seu nome"` // identifica nome no Git
- `git config --global user.email "seu-email@example.com"` // identifica email no Git


## Tarefas

- [X] Você deseja controlar versões do seu projeto.
    - `git init` // inicia a linha do tempo
    
- [X] Você deseja criar pontos na história do seu projeto.
    - `git add .` // adiciona ou atualiza todas as mudanças para irem a linha de tempo
    - `git commit -m "mensagem"` // adiciona um ponto na linha do tempo

- [X] Você deseja verificar mudanças feitas no seu projeto.
    - `git log` // visualiza os pontos na linha do tempo/commit
    - `git status` // informa o estado das alterações do nosso projeto
    - `git show` // apresenta determinado ponto na história
    
- [X] Você começa uma nova funcionalidade, sem estragar o que ja foi feito.
    - `git branch "nome da branch"` // cria uma nova linha de tempo
    - `git checkout "nome da branch"` // alterna entre as linhas de tempo
    
- [X] Você adiciona as novas funcionalidades ao seu projeto de em produção.
    - `git merge "nome da branch"` // unifica uma linha de tempo bifurcada
    
- [X] Você quer deletar a branch da nova funcionalidade, depois de aplicar emp produção.
    - `git branch -D "nome da branch"` // deleta uma linha de tempo
    
- [X] Você quer colocar seu projeto na nuvem.
    
    - https://github.com

    - `git remote add origin "link repositorio remoto"` // adiciona um repositorio remoto
    - `git remote -v` // lista os repositorios remotos
    - `git push -u origin master` // empurra repositorio local para repositorio online
    - `git clone "link repositorio"` // clona um repositorio
