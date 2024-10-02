algo comme une recette de cuisine 
tout les domaines d'application ex math info vie quotidienne 
permet d'obtenir un résultat systématique 
si qqch ne s'exécute pas c'est mort 
logigramme -> chemin menant vers une rep ex meme LOL



Variable = un nom une valeur (ex x en maths)
nom de variable pas de caractères spéciaux, pas d'espace, ne pas commencer par un chiffre 

ex prénom = "John" "dans une variable = chaîne de caractère           le = est une affectation ou déclaration, initialisation 


CONVENTIONS DE NOMMAGE 

camelCase sert a lire plus facilement en mettant une maj en début de chaque mot à part au premier mot 
PascalCase" et même le premier mot 
jesuisresponsabledeformationalametznumericschool
JeSuisResponsabeDeFormationALaMetzNumericSchool
snake_case en mettant un underscore 
kebab-case en mettant un tiret - pour les noms de fichiers ou les URLS
écrire en anglais car pas la possibilité de mettre d'accent en français 
de moins l'infini à plus l'infini = rond 
Entiers (integrer/int)
Décimaux (Float) de - l'infini à plus l'infini
booléen soit vrai soit faux 1 ou 0
décimaux + addition, -soustraction, X multiplication // division 
String + concatenation "Salut"+"ça va"= "Salut ça va" multiplication en python uniquement "A" x 4 = "AAAA"
Bool et Algèbre de Boole
and -> et 
or -> ou       -> opérateurs logiques 
not -> non

ET

| a   | b   | A et B |
| --- | --- | ------ |
| F   | F   | F      |
| V   | F   | F      |
| F   | V   | F      |
| V   | V   | V      |
   
OU

| A   | B   | A OU B |
| --- | --- | ------ |
| F   | F   | F      |
| F   | V   | V      |
| V   | F   | V      |
| V   | V   | V      |
NON


| A   | NON A |
| --- | ----- |
| F   | V     |
| V   | F     |
VALEUR NUMERIQUE 


| A   | B   | A ET B |
| --- | --- | ------ |
| 0   | 0   | 0F     |
| 0   | 1   | 0F     |
| 1   | 0   | 0F     |
| 1   | 1   | 1V     |
Opérateurs de comparaison 

a= =b si a est strictement égal à b


a<=b inférieur ou égal
a>=b supérieur ou égal 


utiliser le sinon si l'on veut mettre des conditions 
if else 

Boucles d'instructions 

for -> compté (variable de comptage)
Permet de répéter une nouvelle fois une action 
Ex
for i in range(start,end):             end est exclu
	instruction
For i in range(0,5):                     incrémentation de 1 la variable de comptage
	print("hello")

Deuxième type de boucle
while (tant que)
Boucle conditionnelle 

Boucle tant que la condition est vérifié 

n=1
while n!= 100
print(n)
n = n+1



mot= "hello"
mot.lower() -> "hello"
mot.upper() -> "HELLO"
h=mot[0] -> "h"
l = len(mot) -> 5
d = mot [:-1]

jour="Mardi"

message = f "nous sommes {jour}"
print(message)