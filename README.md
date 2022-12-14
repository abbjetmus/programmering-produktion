# Programmering Produktion
Välkommen till Programmering på ABB Gymnasiet 2022 för produktion. Under momentets gång kommer vi gå igenom de tre språken som används för att programmera mot webben HTML/CSS/JavaScript. Även om teknikerna oftast används mot webben så går det bygga alla typer av applikationer med dessa.

När vi lärt oss grunderna kommer vi lära oss hur man bygger mer avancerade applikationer med javascript-ramverket Vue.js och Bootstrap CSS.

Vi kommer även lära oss hur man kommunicerar med webbtjänster genom HTTP-protokollet och databaser i form av Firebase om tiden räcker till.

Dessa tekniker kommer ni få applicera på ett projekt.

![alt text](https://cdn.bamahadigital.com/q:i/r:1/wp:1/w:372/u:https://bamahadigital.com/wp-content/uploads/2021/03/wa2.png "Web Anatomy")

## HTML
Kort så är **HTML** en webbsidas struktur och innehåll på samma sett som vårt skelett är för kroppen.

## CSS
**CSS** Är det som ger en webbsida utseende och design i form av färger och positionering. På samma sätt som huden, färgen och kläderna på människan.

## JavaScript
**JavaScript** är det som ger funktionalitet till en webbsida, att något ska hända när man klickar på en knapp osv. Motsvarande för människokroppen är nervsystemet och härnan som tillsammans får kroppen att röra på sig.

## Övergripande resurser för denna modul:
Undervisningen kommer bestå av lärarledda genomgångar av olika koncept i kombination med övningar.
För den som vill (inte obligatoriskt) så kan man titta på en utbildningsserie på Youtube.

* Vi kommer börja i ordningen HTML -> CSS -> JavaScript -> Vue.
* Det finns mappar för varje del, man klickar på en mapp och där finns innehållet, beskrivning och länkar för den delen.
* I mapparna finns det i sin tur en undermapp med övningsuppgifter. När läraren har gått igenom vissa delar eller man själv läst på så gör man övningar på det enligt instruktionerna.

Kursens resurser kommer finnas här på Github och följande länkar för detaljer. 

- [W3School HTML](https://www.w3schools.com/html/)
- [W3School CSS](https://www.w3schools.com/css/default.asp) 
- [W3School Javascript](https://www.w3schools.com/js/default.asp) 

Föredrar man video istället finns dessa från Youtube:  

- [HTML/CSS av The Net Ninja på Youtube](https://www.youtube.com/playlist?list=PL4cUxeGkcC9ivBf_eKCPIAYXWzLlPAm6G)
- [Modern Javascript av The Net Ninja på Youtube](https://www.youtube.com/playlist?list=PL4cUxeGkcC9haFPT7J25Q9GRB_ZkFrQAc)


# Testmiljö att komma igång med

**Visual Studio Code** är programmerings-editor, dvs ett program som vi använder för att skriva kod i.
1. Installera Visual Studio Code från länken: [https://code.visualstudio.com/download](https://code.visualstudio.com/download)

2. Skapa en mappstruktur som tex C:/programmering/HTML  
För JavaScript skapar du en under-mapp med namnet JavaScript istället för HTML.
Från Visual Studio Code öppnar du mappen du skapade **File->Open Folder...**. 
Från Visual Studio Code skapar du en fil tex **test.html**.
I filen **test.html** lägger du in mallkoden:  
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

Innanför body-taggen lägger vi in taggarna som kommer synas på hemsidan.
För att se resultatet från koden öppnar du filen från mappen i webbläsaren.

När man gör ändringar i sin fil så måste man ladda om sidan i webbläsaren. 
Men genom ett tillägg som heter LiveServer i Visual Studio Code kan man öppna filen så att den uppdateras live. Båda sätten fungerar lika bra.

**Grattis du har skapat din första HTML sida!**

Följ nu mapparna i ordningen när du går igenom innehållet.

1. HTML
2. CSS
3. JavaScript
4. Vue
5. Bootstrap
#### Om tiden räcker
6. HTTP och APIer
7. Git-Github

## Checklista HTML/CSS
* Känna till de vanligaste HTML-taggarna h1-h6, p, div, span, a, img, form, button, input...
* Förstå skillnaden mellan inline och block element i HTML
* Hur man skapar listor
* Vad som menas BOX-modellen och hur man ändrar margin, padding, border, width and height
* Positionering static, relative, absolute, fixed...
* Hur man jobbar med färger och bakgrundsfärger i CSS
* Hur man jobbar med text i CSS
* Vad flexbox är och hur man jobbar med det för att designa en layout
* Olika sätt att inkludera CSS i HTML

## Checklists JavaScript
* Variabler
* Datatyper
* Operatorer
* Villkor
* loopar
* Object
* Listor - Array

## Checklista Vue
* Interpolation
* attribute-binding
* v-if villkor
* v-model två-vägs-bindning
* v-for loop igenom lista och generera taggar

## Checklista Bootstrap
* Hur man inkluderar Bootstrap
* Hur man använder Bootstrap för att skapa enkel hemsida
