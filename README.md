			
			
			TUTORIAL - COMO EXECUTAR O PROGRAMA


Versão do Eclipse: Neon
MySql Server 5.7
Versão do Java: 1.8.0_31



---------------------------------------------------------------						DOWNLOAD DO MYSQL

Se não posuir e não saber instalar o Mysql, aqui segue os links de tutoriais:

Vídeo
https://www.youtube.com/watch?v=ME1tWqVoOwA

Sites
http://protocoloti.blogspot.com.br/2012/03/instalando-e-configuurando-o-mysql-no.html


Link para download:
http://dev.mysql.com/downloads/mysql/

---------------------------------------------------------------

Baixe o projeto no link:
http://dropcanvas.com/r4h1r

---------------------------------------------------------------

Extraia o projeto para uma pasta qualquer (aconselho que o faça em uma pasta na sua área de trabalho)


PARA RODAR O BANCO:


Abra o workbench (editor de scripts do mysql)
Crie uma nova conexão (o programa está configurado com o padrão - usuário: root e senha: system).

Em seguida importar o arquivo "museupoo.sql" em
"File > Open Sql Script..." e selecione o arquivo "museupoo.sql" que baixou através do link do dropcanvas (mesmo local do projeto).

Execute todos os scripts (Criará e populará as tabelas);

---------------------------------------------------------------

					EXECUTAR O PROGRAMA


Abra o eclipse (A versão utilizada no desenvolvimento foi o Neon)


* IMPORTE O PROJETO



ALTERAR O DBUTIL PARA ACESSAR O SEU BANCO DE DADOS:

Entre no pacote "edu.museu.instrastructure" e em seguida na classe "JDBCUtil.java"
verifique na linha 12 e 13 se os nomes de usuário e senha que estão entre aspas correspondem aos da conexão que criou acima com seu banco de dados (ou o banco que já tinha anteriormente), se não, altere as linhas 12  13 (referentes a usuário e senha, respectivamente) com as informações do SEU ACESSO AO BANCO;



OBS: 

Se tiver executando nos computadores da FATEC, onde a senha para o banco é "aluno", a única alteração a ser feita é na linha 13, mudando o que está entre aspas ("system") para "aluno".


Entre no pacote "edu.museu.boundary", e em seguida na classe "TelaPrincipal.java"

Execute a classe e teste o programa à vontade.

