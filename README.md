# WEBNAR GIT & GITHUB

## Instalação Git

https://git-scm.com/downloads

- `git --version` // verifica versão do Git
- `git config --global user.name "Seu nome"` // identifica nome no Git
- `git config --global user.email "seu-email@example.com"` // identifica email no Git


## Tarefas

- [] Você deseja controlar versões do seu projeto.
    - `git init` // inicia a linha do tempo
    
- [] Você deseja criar pontos na história do seu projeto.
    - `git add .` // adiciona ou atualiza todas as mudanças para irem a linha de tempo
    - `git commit -m "mensagem"` // adiciona um ponto na linha do tempo

- [] Você deseja verificar mudanças feitas no seu projeto.
    - `git log` // visualiza os pontos na linha do tempo/commit
    - `git status` // informa o estado das alterações do nosso projeto
    - `git show` // apresenta determinado ponto na história
    
- [] Você começa uma nova funcionalidade, sem estragar o que ja foi feito.
    - `git branch "nome da branch"` // cria uma nova linha de tempo
    - `git checkout "nome da branch"` // alterna entre as linhas de tempo
    
- [] Você adiciona as novas funcionalidades ao seu projeto de em produção.
    - `git merge "nome da branch"` // unifica uma linha de tempo bifurcada
    
- [] Você quer deletar a branch da nova funcionalidade, depois de aplicar emp produção.
    - `git branch -D "nome da branch"` // deleta uma linha de tempo
    
- [] Você quer colocar seu projeto na nuvem.
    
    - https://github.com

    - `git remote add origin "link repositorio remoto"` // adiciona um repositorio remoto
    - `git remote -v` // lista os repositorios remotos
    - `git push -u origin master` // empurra repositorio local para repositorio online
    - `git clone "link repositorio"` // clona um repositorio