---


---

<h1 id="lamp">LAMP</h1>
<p><strong>Mariana Vargas benavides</strong><br>
<strong>Curso:</strong> APLICACIONES WEB UTILIZANDO SOFTWARE LIBRE<br>
<strong>Codigo:</strong> ISW-811<br>
<strong>Profesor:</strong> Bladimir Arroyo</p>
<p>En el siguiente documento realizaremos la documentacion de los comanados necesario para poder subir un archivo php al localhost</p>
<h2 id="requerimientos">REQUERIMIENTOS</h2>
<h3 id="instalacion-apache">INSTALACION APACHE</h3>
<blockquote>
<p><strong>Apache</strong> un poderoso servidor web, cuyo nombre proviene de la frase inglesa “a patchy server” y es completamente libre, ya que es un software Open Source y con licencia GPL. Una de las ventajas más grandes de Apache, es que es un servidor web multiplataforma, es decir, puede trabajar con diferentes sistemas operativos y mantener su excelente rendimiento.</p>
</blockquote>
<p><strong>sudo apt-get install apache2</strong><br>
Luego validamos que este correctamente instalado abriendo un navegador y escribiendo en la barra url “localhost” y nos debe aparecer un mensaje de bienenida</p>
<h3 id="instalalcion-mysql">INSTALALCION MYSQL</h3>
<blockquote>
<p><strong>MySQL</strong>, es un sistema de gestión de base de datos relacional o SGBD. Este gestor de base de datos en multihilo y multiusuario, lo que le permite ser utilizado por varias personas al mismo tiempo, e incluso, realizar varias consultas a la vez, lo que lo hace sumamente versátil.</p>
</blockquote>
<p><strong>sudo apt-get install mysql-server mysql-client php-mysql</strong></p>
<h3 id="instalacion-de-php">INSTALACION DE PHP</h3>
<blockquote>
<p><strong>PHP</strong> es un lenguaje de código abierto muy popular especialmente adecuado para el desarrollo web y que puede ser incrustado en HTML.</p>
</blockquote>
<p><strong>sudo apt-get install php libapache2-mod-php php-mysql</strong></p>
<p>Una de las formas de saber si es proceso de instalacion es correcto es crear un archivo php en la sigueinte direccion<br>
<em>$ sudo nano /var/www/html/info.php</em><br>
estado en el archivo agregamos el siguiente codigo</p>
<blockquote>
<p><strong><code>&lt;?php phpinfo() ?&gt;</code></strong></p>
</blockquote>
<p>Guardamos y con el nombre que le ayamos puesto a la carpeta vamos a ir al localhost/nombre, de ser todo corrcto saldra una pagina informativa de php.</p>
<h2 id="publicar-pagina">PUBLICAR PAGINA</h2>
<p>es necesario mover nuestro <strong>cv</strong> a la carpeta de php para que pueda ser leida, es por eso que la moveremos, en mi caso esta en la carpeta escritorio asi que usare el siquiente comando</p>
<p><strong>mv cvs /var/www/html</strong></p>
<p>en el momento en que momemos la carpeta ya podemos acceder desde nuestro navegador, utilizando el siquiente link  [<a href="http://localhost/cvs/index.php">http://localhost/cvs/index.php</a>]</p>

