# CAT
Cette commande, écrit en Pascal (Turbo Pascal ou Free Pascal), permet d'afficher le contenu d'un/des fichiers.  C'est commande est inspiré de la commande Unix ou Linux.

<h3>Syntaxe</h3>

CAT [option] [fichier]

<h3>Paramètres</h3>

<table>
  <tr>
    <th>Nom</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><i>fichier</i>
    <td>Ce paramètre permet d'indiquer le nom du fichier à afficher.</td>
  </tr>
  <tr>
    <td><b>-A</b></td> 
    <td>Ce paramètre est équivalent de -vET.</td>
  </tr>
  <tr>
    <td><b>-b</b></td> 
    <td>Ce paramètre permet d'afficher les numéros de ligne si la ligne n'est pas vide</td>
  </tr>
  <tr>
    <td><b>-E</b></td>
    <td>Ce paramètre permet d'afficher un caractère $ à la fin d'une ligne.</td>
  </tr>
  <tr>
    <td><b>-e</b></td>
    <td>Ce paramètre est un équivalent de -vE.</td>
  </tr>
  <tr>
    <td><b>-n</b></td>
    <td>Ce paramètre permet d'afficher les numéros de ligne.</td>
  </tr>
  <tr>
    <td><b>-s</b></td>
    <td>Ce paramètre permet d'enlever les duplications de ligne blanche.</td>
  </tr>
  <tr>
    <td><b>-T</b></td>
    <td>Ce paramètre permet d'afficher un ^I à la place d'une tabulation.</td>
  </tr>
  <tr>
    <td><b>-v</b></td>
    <td>Ce paramètre permet d'utiliser des notations ^ et M- pour les caractères non imprimable.</td>
  </tr>
  <tr>
    <td><b>--c</b></td>
    <td>Ce paramètre permet d'afficher chacune des lignes en chaîne de caractères C.</td>
  </tr>
  <tr>
    <td><b>--help</b></td>
    <td>Ce paramètre permet d'afficher l'aide de cette commande.</td>
  </tr>
  <tr>
    <td><b>--hex</b></td>
    <td>Ce paramètre permet d'afficher chacune des lignes en hexadécimal.</td>
  </tr>
  <tr>
    <td><b>--html</b></td>
    <td>Ce paramètre permet d'afficher chacune des lignes en HTML.</td>
  </tr>
  <tr>
    <td><b>--lower</b></td>
    <td>Ce paramètre permet de mettre en minuscule chacune des lignes.</td>
  </tr>
  <tr>
    <td><b>--number</b></td>
    <td>Ce paramètre permet d'afficher les numéros de ligne.</td>
  </tr>
  <tr>
    <td><b>--number-nonblank</b></td>
    <td>Ce paramètre permet d'afficher les numéros de ligne si la ligne n'est pas vide.</td>
  </tr>
  <tr>
    <td><b>--pascal</b></td>
    <td>Ce paramètre permet d'afficher chacune des lignes en chaîne de caractères Pascal.</td>
  </tr>
  <tr>
    <td><b>--show-all</b></td>
    <td>Ce paramètre est équivalent de -vET.</td>
  </tr>
  <tr>
    <td><b>--show-nonprinting</b></td>
    <td>Ce paramètre permet d'utiliser des notations ^ et M- pour les caractères non imprimable.</td>
  </tr>
  <tr>
    <td><b>--show-tabs</b></td>
    <td>Ce paramètre permet d'afficher un ^I à la place d'une tabulation.</td>
  </tr>
  <tr>
    <td><b>--squeeze-blank</b></td>
    <td>Ce paramètre permet d'enlever les duplications de ligne blanche.</td>
  </tr>
  <tr>
    <td><b>--trim</b></td>
    <td>Ce paramètre permet d'enlever les espaces au début à la fin de chacun des lignes.</td>
  </tr>
  <tr>
    <td><b>--uniq</b></td>
    <td>Ce paramètre permet d'afficher une fois les lignes dupliqué.</td>
  </tr>
  <tr>
    <td><b>--upper</b></td>
    <td>Ce paramètre permet de mettre en majuscule chacune des lignes.</td>
  </tr>
  <tr>
    <td><b>--version</b></td>
    <td>Ce paramètre permet de demander la version de la commande.</td>
  </tr>
</table>

<h2>Quoi de neuf</h2>

<h4>Version 2.0</h4>
<ul>
  <li>Ajout d'un support à multiple langages : francais, anglais</li>
  <li>Ajout des paramètres --c, --hex, --html, --lower, --pascal, --trim, --uniq et --upper.</li>
</ul>

<h4>Verion 1.0.1</h4>
<ul>
  <li>Rend le code compilable avec le Turbo Pascal</li>
</ul>

<h4>Verion 1.0</h4>
<ul>
  <li>Première version</li>
</ul>


<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> CAT.PAS</pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> CAT.PAS</pre>
	
<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/CAT/blob/main/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/CAT/blob/main/LICENSE">MIT</a>.</li>
</ul>
