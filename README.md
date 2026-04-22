# Guia de comandos LINUX

Este guia contém 30 comandos diferentes para para o GNU/Linux, a lista abrange comandos de Gerenciamento de arquivos, Leitura e edição, Permissões e usuários e Comandos de energia e reinicialização


**Gerenciamento de arquivos**
 ## cd 
**Função:** esse comando faz com quem vc acesse um diretório caso você tenha a permissão para acessá-lo, serve para alterar o diretório atual de trabalho para o destino informado  
**Exemplo:** 
```bash
cd /picles
```
---

## mkdir 
**Função:** Cria um diretorio(pasta) novo para organizar arquivos no sistema.  
  **Exemplo:** 
```bash
mkdir /picles /teste
```
---

## pwd
**Função:** Mostra o caminho atual para o diretório atual e seu nome.  
  **Exemplo:**
```bash
pwd
```
---  

- **cat** – Exibe o conteúdo de arquivos.  
  Exemplo: `cat letra_da_musica_do_chitaozinho_e_chororo.txt`  

- **cp** – Copia arquivos ou diretórios.  
  Exemplo: `cp letra_da_musica_do_chitaozinho_e_chororo.txt /picles`  

- **mv** – Move ou renomeia arquivos/diretórios.  
  Exemplo: `mv receita_de_bolo_antiga.txt receita_de_bolo_novo.txt`  

- **rm** – Remove arquivos ou diretórios.  
  Exemplo: `rm -rf /picles /teste`  

- **touch** – Cria arquivos novos ou atualiza a data/hora de modificação.  
  Exemplo: `touch receita_de_bolo_da_vovo.txt`  

---

##Leitura e edição
- **df** – Mostra detalhes do armazenamento das partições.  
  Exemplo: `df -h`  

- **free** – Exibe informações sobre uso da memória RAM.  
  Exemplo: `free`  

- **ps** – Lista processos em execução.  
  Exemplo: `ps`  

- **grep** – Filtra linhas em arquivos com base em palavras/frases.  
  Exemplo: `grep "erro" sistema.log`  

---

##Permissões e usuários
- **chmod** – Define permissões de leitura, escrita e execução.  
  Exemplo: `chmod 755 roteiro.sh`  

---

##Sistema (energia e reinicialização)
- **reboot** – Reinicia o computador.  
  Exemplo: `reboot`  

- **shutdown** – Desliga o computador.  
  Exemplo: `shutdown -h now`  
