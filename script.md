---


---

<h1 id="proyecto-lamp-en-aws">PROYECTO LAMP EN AWS</h1>
<p><strong>Mariana Vargas benavides</strong><br>
<strong>Curso:</strong> APLICACIONES WEB UTILIZANDO SOFTWARE LIBRE<br>
<strong>Codigo:</strong> ISW-811<br>
<strong>Profesor:</strong> Bladimir Arroyo</p>
<p>En el siguiente documento realizaremos la documentacion de los comanados necesario para poder subir un archivo php al localhost</p>
<h3 id="instalacion-apache">INSTALACION APACHE</h3>
<p><strong>sudo apt-get install apache2</strong><br>
Luego validamos que este correctamente instalado abriendo un navegador y escribiendo en la barra url “localhost” y nos debe aparecer un mensaje de bienenida</p>
<h3 id="instalalcion-mysql">INSTALALCION MYSQL</h3>
<p><strong>sudo apt-get install mysql-server mysql-client php-mysql</strong></p>
<h3 id="instalacion-de-php">INSTALACION DE PHP</h3>
<p><strong>sudo apt-get install php libapache2-mod-php php-mysql</strong></p>
<h3 id="publicar-pagina">PUBLICAR PAGINA</h3>
<p>es necesario mover nuestro <strong>cv</strong> a la carpeta de php para que pueda ser leida, es por eso que la moveremos, en mi caso esta en la carpeta escritorio asi que usare el siquiente comando</p>
<p><strong>mv cvs /var/www/html</strong></p>
<p>en el momento en que momemos la carpeta ya podemos acceder desde nuestro navegador, utilizando el siquiente link  [<a href="http://localhost/cvs/index.php">http://localhost/cvs/index.php</a>]</p>

