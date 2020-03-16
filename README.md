# Este repositório contém o código-fonte do painel da Web que usei na minha série de Cursos: Teste de Invasão Web.

Introduçāo:
---------------

Screenshot:
![alt tag](https://raw.githubusercontent.com/romanzaikin/Owasp-TOP-10-Training-Panel/master/panel.PNG)

Se você ainda deseja usar este painel e não possui o curso, siga estas etapas para configurar o painel:

Ferramentas que você precisará fazer o download para resolver os desafios:
-----------------
1. Burp Suit: https://portswigger.net/burp/communitydownload
2. Sqlmap:	https://github.com/sqlmapproject/sqlmap
3. dirbuster: https://sourceforge.net/projects/dirbuster/
4. python: https://www.python.org/downloads/


Instalaçāo:
-----------------
1. Faça Download do xampp no seu windows: https://www.apachefriends.org/download.html
2. Mova todos os arquivos do repositório para a pasta: C:\xampp\htdocs
3. Inicie o xampp mysql e o apache no software xampp.
4. Abra seu browser no http://127.0.0.1/phpmyadmin
   1. Crie uma base de dados chamada "sqli" 
   2. Pressione na nova base de dados "sqli"
   3. Pressione na aba "import"
   4. Selecione o seguinte arquivo: C:\xampp\htdocs\challenge\SQLI\sqli.sql
   5. Pressione "Go"
   6. Crie uma base de dados chamada "forum" 
   7. Pressione na nova base de dados "forum"
   8. Pressione na aba "import"
   9. Selecione o seguinte arquivo: C:\xampp\htdocs\forum\forum.sql
   10. Pressione "Go"

5. Abra os Desafios: http://127.0.0.1/challenge/

Divirta-se