## Lista de Comandos - CheetChead

##### Rotina básica

- git add: para adicionar na staging área
  
  - posso adicionar mais de um arquivo para fazer commit de todos juntos.

- git commit -m "descrição que eu quiser"
  
  - commit: salva a informação de que houve uma alteração. Salvar um ponto na linha do tempo referente ao repositório local.

- git status: vai rever todo o meu projeto (todas as áreas conceituais) e identificar a situação dos meus arquivos (arquivos que não foram feitos commit, ou não foram feitos staging etc.)

- git remote add <name> <ssh>
  
  - Cria uma ponte entre o repositório local e o github. A "ponte" não envia os arquivos. É preciso enviar os arquivos.
    
    Para enviar: git push
    
    Para receber atualizações do remoto: git pull
    
    Git clone recupera todo o repositório remoto a partir do endereço ssh. Diferentemente do git pull, ele traz todo o repositório criando a ponte ao mesmo tempo e não apenas as alterações como o git pull faz.

Bom trabalho!!!!

Valeu!
