# GIT + GITHUB

commit - versões do código

untracked files - arquivos que não foram add ao controle de versão

Branch - são galhos (se imaginar o repositório como uma árvore) lugares diferentes para salvar versões

Branch master - branch principal, onde normalmente são salvos as versões do projetos 

Branchs secundárias - usado para códigos em fase de testes/criando 

merge - quando determinado passo rodar certinho = pronto enviamos a branch master como uma nova versão


# COMANDOS

git init - iniciar repositório (criar pasta oculta)

git status - informa quais arquivos já estão salvos (controle de versão)

git add “NOME ARQUIVO” - adicionar arquivos ao controle de versão

git add . - adicionar todos os arquivos ao controle de versão

git commit -m “NOME DA VERSÃO” - criar versões e enviar ao github

git config –global user.email “EMAIL GITHUB” - configuração, definir endereço do github

git config –global user.name “NOME DO AUTOR” - nomear o autor da versão 

git remote add origin ENDEREÇO DO REPOSITÓRIO - definir para onde será enviado a versão

git push –set upstream origin master - salvar a versão no master

git push - enviar versão para a nuvem

git reflog - mostrar histórico de versões (commits)

git reset –hard IP DA VERSÃO DESEJADA - voltar a versão desejada

git branch - mostrar branch existentes (BRANCH ATUAL FICA VERDE COM *)

git branch NOME NEW BRANCH - criar uma branch nova

git checkout NOME BRANCH - trocar de branch atual

git merge BRANCH QUE ESTOU PUXANDO A VERSÃO - mergiar um código, unir versões estando em brachs diferentes, mandar o commit do branch staging para o branch master

git pull - baixar as atualizações do servidor para a máquina local

git checkout -b sistema-de-login master - criado uma nova branch com nome sistema-de-login a partir da branch master e já selecionando a branch nova 
