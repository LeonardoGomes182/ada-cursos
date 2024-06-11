//-----------------COMANDO BÁSICO DO GIT-------------------

git diff -  Informa a modificação realizada. 
//---------------------------------------------------

Observação: Apósa plica o "git add .", o comando "diff" não irá informar as alterações realizada. Para mostrar, será necessário adicionar outro complemento ao comando:

git diff --staged - Informa alterações após o "git add", mostrando o arquivo na área de staged. 

//--------------------------------------
Mudar do estado "staged" quando realizado "git add" e retornar para o "Modified"

git restore --staged .\NomeDoArquivo

//----------------------------------------------------------
git log - histórico de commit 

git fetch - informa o que tem de alteração(diferente) do repositório com a local. Não 

