# Guia de comandos LINUX


Este guia contém 30 comandos diferentes para para o GNU/Linux, a lista abrange comandos de Gerenciamento de arquivos, Leitura e edição, Permissões e usuários e Comandos de energia e reinicialização. 


**Gerenciamento de arquivos**
 ## cd 
**Função:** Esse comando faz com quem vc acesse um diretório caso você tenha a permissão para acessá-lo, serve para alterar o diretório atual de trabalho para o destino informado.

**Exemplo:** 
```bash
cd /picles
```
---
## kill
**Função:** Esse comando, é usado para encerrar processos, ele pode ser útil para interromper operações criadas pelo usuário ou iniciadas automaticamente.

**Exemplo:**
```bash
kill
```
---
## su
**Função:** permite mudar a identidade atual para um outro usuario sem deslogar.

**Exemplo:**
```bash
su - (muda para o superusuário root com o ambiente dele)
```
---

## mkdir 
**Função:** Cria um diretorio(pasta) novo para organizar arquivos no sistema. 

**Exemplo:**
```bash
mkdir /picles /teste
```
---

## rmdir
**Função:** Exclui permanentemente um diretório que esteja vazio.(

**Exemplo:**
```bash
rmdir -p
``` 
---

## find
**Função:** Encontrar arquivo e diretório específico de acordo com um critério selecionado, como tipo ou tamanho.

**Exemplo:**
```bash
find [diretório] [opção] [ação]
```
---
## stat
**Função:**

**Exemplo:**
```bash
stat picles.txt
```
---

## locate
**Função:** Semelhante ao comado find, o locate é mais menos preciso e mais rápido, pois para funcionar ele necessita de um banco de dados alimentado.

**Exemplo:**
```bash
locate arquivo teste.txt
```
---

## head
**Função:** Permite que as 10 primeiras linhas de um arquivo sejam exibidas e visualizadas, pode ser alterado para exibir uma quantidade diferente de linhas.

**Exemplo:**
```bash
head picles/teste
```
---
## tail
**Função:** Semelhante ao comando head, o comando tail mostra as últimas 10 linhas, e também pode mostrar um nú
## pwd
**Função:** Mostra o caminho atual para o diretório atual e seu nome.

**Exemplo:**
```bash
pwd -L
```
---  

## cat
**Função:** Mostra o conteúdo de um arquivo do tipo binário e em texto diretamente no terminal.  

**Exemplo:**
```bash
cat letra_da_musica_do_chitaozinho_e_chororo.txt
```
--- 

## cp
**Função:** Copia arquivos ou diretórios de um destino para o outro.  

**Exemplo:**
```bash
cp letra_da_musica_do_chitaozinho_e_chororo.txt /picles
```
--- 

## mv
**Função:** Transporta o arquivo para outro local ou altera seu nome.  

**Exemplo:**
```bash
mv receita_de_bolo_antiga.txt receita_de_bolo_novo.txt
```
---

## rm 
**Função:** Remove arquivos ou diretórios permanentemente.  

**Exemplo:**
```bash
rm -rf /picles /teste
```  
---

## touch
**Função:** Cria arquivos novos ou atualiza a data/hora de modificação.  

**Exemplo:**
```bash
touch receita_de_bolo_da_vovo.txt
```

---
**Leitura e edição**
---
## less
**Função:** Exibe grandes arquivos página por página

**Exemplo:**
```bash
cat picles.txt
```
---

## df
**Função:** Mostra os detalhes do armazenamento de cada partição montada.  

**Exemplo:**
```bash
df -h
```
---  

## free 
**Função:** Mostra detalhes sobre o uso da memória ram( mostra o uso, quanto está livre e total do sistema). 

**Exemplo:**
```bash
free
```
---  

## os
**Função:** Lista os processos que estão em execução no momento.  

**Exemplo:**
```bash
ps
```
---

## grep
**Função:** Filtra linhas que contenha a palavra ou frase pesquisada,  

**Exemplo:** 
```bash
grep "erro" sistema.log
``` 
---
## kill
**Função:** Esse comando, é usado para encerrar processos, ele pode ser útil para interromper operações criadas pelo usuário ou iniciadas automaticamente.

**Exemplo:**
```bash
kill
```
---
**Permissões e usuários**
---

## chmod
**Função:** Define quem pode ler, gravar ou executar um arquivo ou diretório.

**Exemplo:** 
```bash
chmod 755 roteiro.sh
```  
---

**Sistema (energia e reinicialização)**

---

## reboot 
**Função:** Reinicia o computador.  

**Exemplo:** 
```bash
reboot
```  

## shutdown 
**Função:** Encerra todos os processos e desliga a máquina.

**Exemplo:** 
```bash
shutdown -h now
```
---
## uptime
**Função:**Mostra quanto tempo o sistema permanece em execução, a carga e quantos usuários estão logados no momento.

**Exemplo:**
```bash
uptime
```
---

