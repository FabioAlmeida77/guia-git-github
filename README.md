# guia-git-github

# Guia Prático: Git e GitHub

Este guia tem como objetivo ensinar os comandos básicos de Git e GitHub para iniciantes.

## 📥 Instalação do Git

### Windows:
1. Acesse: https://git-scm.com/download/win
2. Baixe e instale o Git.
3. Durante a instalação, mantenha as opções padrão.
------------------------------------------------------
4. git config --global user.name "Seu Nome"
5. git config --global user.email "seuemail@example.com"
   
# Criar um repositorio Local e conecato ao Github:
git init,
git remote add origin https://github.com/seu-usuario/guia-git-github.git

## Operações Basicas
git add
## Fazer commit:
git commit -m "Mensagem do commit"
## Enviar para o GitHub:
git push origin main
## Atualizar seu repositório local com mudanças do GitHub:
git pull origin main
## Branches
git branch nome-da-branch
## Mudar de branch:
git checkout nome-da-branch
## Clonar Repositório
git clone https://github.com/usuario/repositorio.git

# Criar Pull Request
1.Crie uma nova branch e faça as alterações.

2.Faça push da branch para o GitHub.

3.No GitHub, clique em "Compare & pull request".

4.Escreva uma descrição e envie.

# Dicas e Boas Práticas
1.Escreva mensagens de commit claras.

2.Use um arquivo .gitignore para evitar enviar arquivos desnecessários.

3.Faça commits com frequência, especialmente após concluir partes do projeto.

4.Use branches para testar novas ideias sem afetar a main.

5.Sempre revise antes de criar Pull Requests.

#  Exemplos de Comandos
git init

git add 

git commit -m "Primeiro commit"

git push origin main

