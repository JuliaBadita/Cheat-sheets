# CSS 
## Styling links
a:link = Styliser un lien pas encore visité  
a:visited = Styliser un lien que l'utilisateur a visité  
a:hover = Styliser quand on passe la souris sur le lien  
a: active = Styliser le lien au moment où l'on clique dessus  

> Se place dans le head et à relier dans le body avec un <  a href="default.asp" target="blank"  > Lien ici (ceci est un exemple) </  a  >  


> Il y a des règles d'ordre à respecter : d'abord a:hover se place après a:link et a:visited ; ensuite a:active vient après a:hover

## Text Decoration 
> Cette propriété est principalement utilsé afin d'enlever l'underline des liens.  

Exemple : a:link {  
    text-decoration: none;  
}

## Background Color
> Cette propriété est utilisé afin de choisir la couleur de fond des liens.  

Exemple : a:visited {  
    background-color: lightgreen;  
}


## Les Pseudos-classes
> Elles sont utilisées afin de définir l'état spécifique d'un élément, par exmple cela peut-être utilisé afin de :  
>> Styliser un element quand un utilisateur passe sa souris dessus  
>> Styliser de manière différente les liens visités et non-visités  
>> Styliser un élément quand on clique dessus par exemple  

