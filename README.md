## Guia comados linux
Este repositório foi criado como um guia prático de comandos Linux para os alunos do programa AWS re/Start , focado no conteúdo apresentado no módulo de Linux. A proposta é reunir os principais comandos utilizados no dia a dia de quem administra servidores, especialmente servidores baseados em Linux na AWS (Amazon Web Services).

## 🐧 Por que aprender Linux?
A maior parte das instâncias de servidores em nuvem (como as instâncias EC2 na AWS) utilizam o sistema operacional Linux por ser:

> 📦 Leve e eficiente
>
>🔐 Seguro e confiável
>
>🧩 Altamente personalizável
>
>💰 Open Source (gratuito)
>
>💻 Muito utilizado em ambientes de produção e cloud computing

- Com o domínio da linha de comando do Linux, você será capaz de:

- Gerenciar arquivos e pastas

- Monitorar e gerenciar processos

- Instalar aplicações

- Automatizar tarefas

- Controlar permissões e acessos

- Solucionar problemas

## 📁 Navegação

```bash
ls
```
> Lista os arquivos e diretórios do diretório atual.

```
cd nome-do-diretório
```
> Muda para outro diretório.

```
pwd
```
> Mostra o caminho completo (path) do diretório atual.

```
tree
```
> Exibe a estrutura de diretórios e subdiretórios em forma de árvore (pode ser necessário instalar).

## 📦 Gestão de Arquivos e Pastas

```
touch nome-do-arquivo.txt
```
> Cria um novo arquivo vazio.

```
mkdir nova-pasta
```
> Cria um novo diretório.

```
cp arquivo.txt /caminho/de/destino/
```
> Copia um arquivo para outro diretório.

```
mv arquivo.txt nova-pasta/
```
> Move ou renomeia arquivos e pastas.

```
rm arquivo.txt
```
> Remove (deleta) um arquivo.

```
rmdir nome-da-pasta
```
> Remove uma pasta vazia.

## 📄 Leitura de Arquivos

```
cat arquivo.txt
```
> Mostra o conteúdo completo de um arquivo.

```
less arquivo.txt
```
> Exibe o conteúdo com navegação por página (teclas: espaço para descer, q para sair).

```
head arquivo.txt
```
> Mostra as primeiras 10 linhas do arquivo.

```
tail arquivo.txt
```
> Mostra as últimas 10 linhas do arquivo.

## 🔐 Permissões de Arquivos

```
chmod +x script.sh
```
> Modifica permissões de acesso (ex: torna um arquivo executável).

```
chown usuario:grupo arquivo.txt
```
> Muda o dono de um arquivo para um usuário/grupo específico.

```
sudo 
```
> Executa o comando como superusuário (admin/root).

## 🔍 Busca de Arquivos e Conteúdos

```
find / -name "arquivo.txt"
```
> Procura um arquivo pelo nome a partir de um caminho.

```
grep "palavra" arquivo.txt
```
> Procura por uma palavra ou padrão dentro de um arquivo.

## 🌐 Utilidades de Rede

```
ping google.com
```
> Verifica a conectividade com um servidor.

```
curl http://exemplo.com
```
> Faz uma requisição HTTP e mostra a resposta no terminal.

```
wget http://exemplo.com/arquivo.zip
```
> Baixa arquivos da internet pelo terminal.

## ⚙️ Processos do Sistema

```
top
```
> Mostra os processos ativos em tempo real.

```
ps aux
```
> Lista todos os processos em execução.

```
kill PID
```
> Encerra um processo pelo seu ID (PID).

```
df -h
```
> Mostra o uso do disco de forma legível (em GB/MB).

```
du -sh pasta/
```
> Mostra o tamanho total da pasta especificada.

```
uptime
```
> Informa há quanto tempo o sistema está ligado.

```
clear
```
> Limpa a tela do terminal.

## 🛠️ Utilidades do Sistema

```
echo "Olá, mundo!"
```
> Imprime uma mensagem na tela.

```
history
```
> Mostra o histórico de comandos utilizados.

```
man comando
```
> Exibe o manual do comando (pressione q para sair).

```
nano arquivo.txt
```
> Editor de texto simples no terminal (use Ctrl+X para sair).

```
vim arquivo.txt
```
> Editor de texto avançado no terminal (pressione i para editar, Esc, depois :wq para salvar e sair).

## Recomendações

- Sempre teste os comandos em ambientes controlados

- Use sudo com cuidado

- Explore os manuais com man comando

- Pratique usando sua própria instância EC2 no Amazon Linux

## Tecnologias Utilizadas

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/9/93/Amazon_Web_Services_Logo.svg" alt="AWS" width="80" height="60"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux" width="60" height="60"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="Bash" width="60" height="60"/>
</div>

---

### 👨‍🏫 Criado por [Heberton Geovane](https://www.linkedin.com/in/heberton-geovane/)
