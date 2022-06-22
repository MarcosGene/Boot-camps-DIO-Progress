# Comandos Básicos do GIT

###  git config

 - Um dos comandos git mais usados é o git config que pode ser usado 
   para definir valores de configuração específicos do usuário como e-mail, algoritmo 
   preferido para diff, nome de usuário e formato de arquivo etc.

               Exemplos : git config --global user.email sam@google.com

### git init 

- Este comando é usado para criar um novo repositório GIT. Uso:

      Exemplos    : git init

### git add

- O comando git add pode ser usado para adicionar arquivos ao índice. 
  Por exemplo, o seguinte comando irá adicionar um arquivo chamado temp.txt 
  presente no diretório local para o índice:

              Exemplos: git add temp.txt

### git clone

- O comando git clone é usado para fins de verificação de repositório.
  Se o repositório estiver em um servidor remoto, use:

             Exemplos: git clone alex@93.188.160.58:/path/to/repository

  Por outro lado, se uma cópia de trabalho de um repositório local for criada, use:

                  Exemplos: git clone /path/to/repository

### git commit

- O comando git commit é usado para confirmar as alterações na cabeça.
  Tenha em atenção que quaisquer alterações efetuadas não irão para o repositório
  remoto. Uso:     
                  Exemplos : git commit –m “coloque sua mensagem aqui”

### git status

- O comando git status exibe a lista de arquivos alterados juntamente com 
  os arquivos que ainda não foram adicionados ou confirmados. Uso:
                 

               Exemplos : git status

### git pull

- Para mesclar todas as alterações presentes no repositório remoto para o 
  diretório de trabalho local, o comando pull é usado. Uso:
         

               Exemplos : git pull





# windowns

`cd`- Entra em uma pasta

`cd ..`- Retorna para a pastar anterios

`cd /`- Rireciona para a home

`dir` - Listando arquivos e pastas

`del` - Exclui arquivos e pastas

`md ou mkdir` - Cria uma pasta

`copy` - Copiar os arquivos 

`move` - mover arquivos ou renomear pastas

# unix

`cd`- entra em uma pasta

`cd ..`- retorna para a pastar anterios

`cd /`- direciona para a home

`cd ~`- colocará o usuário no diretório inicial do nome de usuário.

`cd ..`- retorna para a pastar anterios

`mkdir`- criar pasta

`rm ou rm -rf` - exclui uma pastagit status

## Comandos mais usados !



### git add (nome da pasta)

`git add *` (tudo q foi modificado e adicionar ao status para comitar)

`git commit -m` "adiciona index"

`git config --list `(verificar configuração esta iqual git config --list)

`git remote add origin`https://github.com/MarcosGene/livro-receitas.git (enviar arquivo adicionando origem a eles)

`git remote -v`  (Mostrar lista remota cadastrada)

`git pull origin master` (resolver error)

`git clone " http" ` (cópia de trabalho de um repositório local for criada)

`git push origin master` ( fazer o push)