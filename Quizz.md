## Qu'est ce qu’un navigateur ?

```
C'est un moteur de recherche qui permet de récupérer des informations sur internet. 



```

________________________________________________________________________________________

## Définissez l’ensemble HTML/CSS/JavaScript et leur utilités.


```
Il s'agit de différents languages informatiques qui servent au développement web. 
Le html sert à placer les éléments du sites grâce à des balises (squelette du site).
Le CSS sert à styliser les balises du html afin de donner un meilleur aspect au site. 
Le Javascript permet d'apporter des fonctionnalités supplémentaires au html en particulier 
en créant des animations dynamiques. Le Javascript sert également à trouver des informations
dans des tableaux/chaînes de caractères grâce à une logique algorithmique.


```
________________________________________________________________________________________


## Qu’est-ce qu’un élément HTML ? Un attribut ?

```
Un élément HTML est le contenu qui se trouve dans une balise (l'attribut). 
Ex : <p> Hello World </p>



```
________________________________________________________________________________________


## Dans quels cas utilisez-vous des id au lieu des classes (et vice-versa) ?


```
Les id sont des balises individuelles, on ne peut donc pas retrouver deux id de même nom.
On utilise une id pour rendre une balise utilisée plusieurs fois, afin de la rendre spécifique. 
Ex : <p> Hello World </p>
     <p id = "unique" > Bonjour </p>

Les classes sont utilisées pour regrouper plusieurs balises en les spécifiant avec une même classe. On s'en sert principalement pour stylisé plusieurs balises qui ne sont pas les mêmes principalement. 
Ex : <h1 class="regroupe"> Hello World </p>
     <p class="regroupe"> Bonjour </p>	



```
________________________________________________________________________________________


## Qu’est-ce que EcmaScript ?

```




```

________________________________________________________________________________________

## Pourquoi est-il important de bien indenter vos fichiers ?

```
L'indentation permet une lecture facile du code, cela permet de mieux s'y retrouver lorsqu'on a un fichier d'édition avec plusieurs centaines lignes de code.



```
________________________________________________________________________________________


## Quelle est la différence entre margin et padding ? 

```
margin permet d'agrandir ou réduire l'espace en dehors d'un block.
padding permet d'agrandir ou réduire l'espace à l'intérieur d'un block.


```

________________________________________________________________________________________


## Citez au moins 3 types de positionnement en CSS et expliquer leurs rôles.

```
h1 {
position : fixed = le titre ne bougera pas et restera à la même place. 
	   absolute = le titre sera toujours visible devant les autres éléments (comme une image par exemple)
	   relativ = le titre ne sera pas toujours visible devant les autres éléments (comme une image par exemple) 
}



```
________________________________________________________________________________________

## Qu’est-ce qu’une variable ?

```

une variable (var / let / const) est une valeur (nombre, chaînes de caractères, tableau etc) qui permet d'être appelée dans une fonction.


```
________________________________________________________________________________________


## Citez le plus de types JavaScript possible et définissez les rapidement.


```
Jquery
Nodejs
React



```
________________________________________________________________________________________


##  À quoi sert le mot-clef “if” ?

```
"if" sert à créer une condition qui pourra alors renvoyer à un état si la condition est vrai ou fausse. 



```

________________________________________________________________________________________

##  Définissez l’objet XHR en JavaScript, son abréviation. À quoi sert-il ?


```
XmlHttpRequest : permet de récupérer des données d'un serveur grâce au Javascript.



```

________________________________________________________________________________________

## Qu’est-ce qu’une requête HTTP ? 

```
Une requête HTTP est une demande d'un client vers un serveur. Le client fait une demande à un serveur, ce serveur lui renvoie alors la réponse sous différents états (grossièrement 100, 200, 300, 400 ou 500).



```
________________________________________________________________________________________


## Quelle sont les deux types de requêtes permettant de récupérer et d’envoyer de la donnée sur un serveur HTTP ?

```
Une requête API permet de récupérer de la donnée sur un serveur HTTP grâce à une clée spécifique.



```

________________________________________________________________________________________

## À quoi sert le Header d’une requête ? Le “Content-Type” ?

```

Le header d'une requête permet de savoir si la liaison entre le client et le serveur s'est faite.
Le "Content-Type" permet de définir les codes de réponse.


```
________________________________________________________________________________________


## Donnez au moins 3 codes de réponse HTTP et définissez les.


```
200 : l'état du serveur est "ok"
300 : la demande du client n'a pas aboutie ou n'a pas pu être trouvée
400 : l'état du serveur n'est pas "ok". Le serveur bug, il peut être en maintenance ou la page n'est pas disponible (réponse 404 dans ce dernier cas). 



```
________________________________________________________________________________________


## Définissez les rôles de Scrum Master et Product Owner.


```
Le Scrum Master est le manager du Scrum, il doit s'assurer que les objectifs sont respectés ainsi que leurs délais.
Le Product Owner est celui qui annonce les "users stories" , il doit faire le compte rendu des sprint au client. 



```
________________________________________________________________________________________


## Citer 4 commandes utilisées avec GIT et expliquer leurs rôles.
```
git checkout -b  : permet de créer une branche.
git checkout "branche" : permet de se déplacer dans les différentes branches créés.
git add . : ajoute les fichiers modifiés ou créés à la branche actuelle. 
git commit -m "message" : permet d'enregistrer les modifications apportés à la branche en ajoutant un message au commit.  



```
________________________________________________________________________________________


## Expliquer le code suivant et indiquer le résultat retourné par la fonction.

```
function counter(){
        const sentence = "Validation de la première phase";
        const words = sentence.split(' ');
        let count = 0;


        for (let i = 0; i < words.length; i++) {
            var word = words[i];
            count += word.length;
        }
        return count;
}
```
```

V a l i d a t i o n  d e  l a  p r e m i è r e  p h a s e


```
________________________________________________________________________________________


## Algo 

Ecrire l’algorithme d’une fonction prenant en paramètre 2 arguments : le premier est une chaîne de caractère et le second correspondant au caractère recherché. Cette fonction retourne le nombre de fois que le caractère recherché est rencontré dans la chaîne de caractères.
Ex. 
   * chaîne : ‘examen’, caractère : ‘x’ => 1
   * chaîne : ‘wild code school’, caractère : ‘w’ => 1



```
function reg () {
go = "World"
chaine = /o/.exec(go)
 
	if (chaine=/[a-z]/) {
	return count
	}
	
}

```


