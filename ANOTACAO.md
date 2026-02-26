# PRINCIPAS COMANDOS DO GIT 
# Enviando a primeira versão
1. git init -> Inicializar a pasta como repositório local 
2. git branch -M main -> Altera a branch master para main
3. git add . -> Adiciona os arquivos para o repositório local
4. git commit -m "Primeira versão do sistema"
5. git remote add origin https://github.com/gumonteiro39-source/sistema_medico.git
6. git push -u origin main

## Enviando as próximas versões
1. git add . -> Adiciona os arquivos para o repositório local
2. git commit -m "Primeira versão do sistema"
3. git push

## CONFIGURAÇÃO DE USUÁRIO GIT
git config --global user.name "Gustavo Monteiro"
git config --global user.email "gumonteiro39@gmail.com"