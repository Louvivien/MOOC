<h1>MOOC </h1>



Réalisé par C. Avronsart et v.Richaud

<p>On veut créer une plateforme d'apprentissage en ligne. Il y a plein de cours. Chaque cours a un titre et une description. Enfin, chaque cours a plusieurs leçons, qui ont un titre et un body.</p>

<p> Pour ce faire nous avons créé le modèle suivant: 
	<ul>
		<li> <strong>Cour</strong> qui a comme attributs 'title' et 'description'.<br/>
			- <em>has_many</em> : Un Cour a plusieurs leçons</li>
		<li> <strong>Leçon</strong> qui a comme attributs 'title' et 'body'.<br/>
			- <em>belongs_to</em> : Un Article appartient à un cours<br/>
		</ul></p>

