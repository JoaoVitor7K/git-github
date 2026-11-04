# Aula prática com Git e Github.

## Configurando o Git

  git config --global user.name "JoaoVitor7K"
  git config --global user.email "jv18.76767@gmail.com"

  ## Validando as configurações 
  git config --list

  ## Inicializando o repositório
  git init

  ##Verificar arquivos
  git status
  
  ## Commit
  git add . ou <nomeDoArquivo>
  git commit -m "Primeiro commit"

  ## Definir a ramificação
  git branch -M main

  ## Conectar ao repositório do Github (somente na primeira vez)
  git remote add origin https://github.com/JoaoVitor7K/git-github.git

  ## Enviar para o Github
  git push -u origin (apenas no primeiro envio)
  git push (nos demais envios)

  ## Atualizar o Github
  git pull