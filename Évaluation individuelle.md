# Évaluation individuelle

## Programmation - Coaching

```
Nom : LI
Prénom : Hui
URL de votre compte Github : https://github.com/hui2299
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
client vont envoyer un resqest à serveur, serveur va donner une réponse à client.
```



 ### 2. HTML est un langage côté... 	

```
client
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
    <head>
        <link rel="stylesheet" href="style.css">
        <title> évaluation individuelle</title>
    </head>
    <body>
        
    </body>
</html>

```



### 4. Changez la couleur du texte "J'adore la programmation" en vert en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
div{
    color:green;
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est l'ensemble des HTML, CSS,etc, il y a par exemple bouton, formulaire, on peut utiliser cette collection des outils pour designer notre site et application, c'est plus simple et efficace.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
    <head>
         <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css" integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous">
        <link rel="stylesheet" href="style.css">
        <title> évaluation individuelle</title>
    </head>
    <body>
        
    </body>
</html>

```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
 <div class="container">  
<div class="colonne">
<div>
    Google
</div>

<div>
    Microsoft
</div>

<div>
    Apple
</div>
     </div>
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
 <div class="container">  
<div class="colonne">
<div>
    <img scr="https://www.usine-digitale.fr/mediatheque/5/0/0/000305005_homePageUne/logo-google-g.jpg" />
</div>

<div>
    <img scr="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAWlBMVEUFpvD/ugiBvAbzUyXz8/P19PP19Pfz9vb25cR4uADp7uLz5uPzQwD/twAAofDzRgHE4PL07uLzz8jY5sTi7fP/swAAnPDzNABwtQDn7vP07+fzNwDs8Ofz6uiz07nSAAABeElEQVR4nO3cOXKDQBRFUWx3oxE0D572v00ngKpEpOBb1ejcDTxO1ES/SlOvevYHhEdYfoTl90rCWXzDVh3fWPi7jy93W/kQ38+9cLb/3kR3WXVjy+siuuuhHgk3H9GtB+HiPboFISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISHhA8LLOrrn3qBNeRVfv5WW8fU3i1/q2vVUIyw/wvK7CXN8TxYe4xu2dvGN3sO8PbfRnY/d7O7URHea3//T5G1bRdcOwuYtuoaQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkPAB4dRv0KbPbXz9Vp7H95Xuhf96C7qOL42FU42w/AjLj7D8/gB4KyYtuuM1qgAAAABJRU5ErkJggg==" />
</div>

<div>
    <img scr="https://image.freepik.com/free-icon/apple-logo_318-40184.jpg" />
</div>
     </div>
    </div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
 <div class="container">  
<div class="colonne">
    
<div>
    <a href="http://www.google.fr">
    <img scr="https://www.usine-digitale.fr/mediatheque/5/0/0/000305005_homePageUne/logo-google-g.jpg" />
        </a>
</div>

<div>
    <a href="http://www.microsoft.com">
    <img scr="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAWlBMVEUFpvD/ugiBvAbzUyXz8/P19PP19Pfz9vb25cR4uADp7uLz5uPzQwD/twAAofDzRgHE4PL07uLzz8jY5sTi7fP/swAAnPDzNABwtQDn7vP07+fzNwDs8Ofz6uiz07nSAAABeElEQVR4nO3cOXKDQBRFUWx3oxE0D572v00ngKpEpOBb1ejcDTxO1ES/SlOvevYHhEdYfoTl90rCWXzDVh3fWPi7jy93W/kQ38+9cLb/3kR3WXVjy+siuuuhHgk3H9GtB+HiPboFISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISHhA8LLOrrn3qBNeRVfv5WW8fU3i1/q2vVUIyw/wvK7CXN8TxYe4xu2dvGN3sO8PbfRnY/d7O7URHea3//T5G1bRdcOwuYtuoaQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkPAB4dRv0KbPbXz9Vp7H95Xuhf96C7qOL42FU42w/AjLj7D8/gB4KyYtuuM1qgAAAABJRU5ErkJggg==" />
    </a>
</div>

<div>
    <a href="http://www.apple.com">
    <img scr="https://image.freepik.com/free-icon/apple-logo_318-40184.jpg" />
    </a>
</div>
     </div>
    </div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```
my_num = 3 # c'est numbers
my_boolean = true # c'est boolean, true ou false
my_string = "Hui LI" # c'est string, les mots, les phrases
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
my_firstname = "Hui"
my_lastname = "LI"
my_github = "https://github.com/hui2299"

puts my_firstname
puts my_lastname
puts my_github
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
    a = 674
    b = 311
    c = a % b
    puts c
# Le résultat attendu est 52. 

```



### 14. Qu'est-ce qu'une gem ? 

```texte
RubyGems nous permet de télécharger, d'installer et d'utiliser facilement ruby dans notre système. Ce paquet s'appelle "Gem" et contient une application ou une bibliothèque de paquet Ruby.
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
API est interface de programmation, elle nous permets d'avoir les services d'un site hors l'interface graphique.
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur
prenom = "Anthony"
hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom
if hour < 12
    puts "Bonjour #{prenom}"
else 
    puts "Bonsoir #{prenom}"
end
# sinon
	# j'écris mon code permettant de dire Bonsoir prénom
  

```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]
client.follow("@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra")


```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

