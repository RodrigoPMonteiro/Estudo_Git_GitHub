# Estudo_Git_GitHub
Repositório criado para estudo de versionamento via linha de comando do Git local e envio para o GitHub.

<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Aprendizado - versionando no Git + GitHub através de linha de comando no Windows
</h3>

<blockquote align="center">
  “Conhecimento não é aquilo que você sabe, mas o que você faz com aquilo que sabe.” Aldous Huxley
</blockquote>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

## Conceitos básicos: 
Devemos inicialmente compreender a diferença entre Git e GitHub:

<I>"A diferença entre git e github é que o git é só uma ferramenta para versionar projetos, enquanto o github
é o site no qual você colocará esses projetos versionados. 
Uma analogia válida seria que o git é seu pincel e tintas enquanto o github é um museu. </I>

## Instalações e configurações necessárias

GitHub:
<ul>
  <li>É necessário se cadastrar para utilização do GitHub pessoal ou corporativo</li>
</ul>

Git:
<ul>
  <li>Instalar o software <I>git</I> no seu computador: <a href="https://git-scm.com/downloads">https://git-scm.com/downloads</a></li>
</ul>

Softwares necessários:
<ul>
  <li><I>Visual Studio Code</I> no seu computador: <a href="https://code.visualstudio.com/">https://code.visualstudio.com/</a></li>
  <li>Instalar o gerenciador de pacotes <I>Chocolatey</I>: <a href="https://chocolatey.org/install">https://chocolatey.org/install</a></li>
  <li>Instalar <I>Yarn</I> através do Chocolatey :<a href="https://classic.yarnpkg.com/en/docs/install/#windows-stable">https://classic.yarnpkg.com/en/docs/install/#windows-stable</a></li>
  <li>Iniciar o <I>PowerShell</I> : clicar no menu Iniciar, digitar <I>PowerShell</I> e com o botão direito do mouse clicar em "Run as administrator"</li>
</ul>


### Inicializando um repositório no diretório onde a aplicação será construída

<p>
  No <I>PowerShell</I>, navegar até o diretório da sua aplicação. Caso ainda não exista o diretório, criá-lo através do comando <I>mkdir</I> ou 
  <I>Windows Explorer</I>.
</p>

<p>
  Para inicializar um repositório deve ser utilizado o comando <I>git init</I>. Após execução do comando, será criado um novo
  diretório <I>.git</I>, o qual o <I>git</I> utilizará para gerenciar o versionamento do seu projeto.
  
  <p>
    <b>Obs.:</b> este diretório só pode ser visualizado se as configurações de visualização de diretórios ocultos do seu Windows estiverem habilitadas.
  </p>
</p>

### Criando um novo arquivo 

<p>
  Para criar um novo arquivo "index.js" no nosso projeto podemos utilizar o comando <b><I>echo > index.js</I></b> no <I>PowerShell</I>
  
  Criar um novo arquivo "package.json" com configurações padrão: <b><I>yarn init -y </I></b>
</p>

### Instalando o express
<p>
  Através do comando <b><I>yarn add express</I></b>, será instalado o express para o projeto. <br>Criaremos um app simples com uma rota de teste e um retorno <b><I>"Hello world"</I></b> na porta 3333.
</p>

### Abrindo Visual Studio Code 

Para abrir a ferramenta de desenvolvimento, bastar digitar <b><I>Code .</I></b> no <I>PowerShell</I>.
O Visual Studio Code será executado e poderemos visualizar os arquivos:
<ul>
  <li><b><I>index.js</I></b></li>
  <li><b><I>package.json</I></b></li>
</ul>

<p>
  Podemos observar que nomenclatura dos arquivos fica verde no Visual Studio Code, pois ainda não foram versionados os arquivos. <br>
  Porém o git vai carregar todos os arquivos, inclusive os arquivos  que só são utilizados para desenvolvimento da aplicação. Para carregar para o versionamento somente os arquivos criados para a aplicação, devemos abstrair a pasta: </p> <ul><li><I>node_modules</I></li></ul>.

<p>
  Através do comando <b><I>echo > .gitignore</I></b>, criaremos um novo arquivo, onde iremos inserir o termo <b><I>echo>node_modules</I></b>. Salve o arquivo.
  <br> Observe que a contagem exibida no Visual Studio Code no menu lateral esquerdo em "Source Control" será reduzido para 4 arquivos:
  <ul>
    <li><I>index.js</I></li>
    <li><I>package.json</I></li>
    <li><I>.gitignore</I></li>
    <li><I>yarn.lock</I></li>
  </ul>
</p>


### Adicionando arquivos trabalhados ao Git 

### <<<<<  Em construção....  >>>>>

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Feito com 💜 by RodrigoMonteiro :wave: [Entre na nossa comunidade!](https://discordapp.com/invite/gCRAFhc)
