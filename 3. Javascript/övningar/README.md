# Övningar

## 1.1 Variabler
### Övningsuppgifter
**Övning 0 - Jobba med variabler**
  1. Deklarera 3 variabler **name**, **age**, **hasDriverLicense** med värden **"Kalle Kula"**, **18**, **true**.
  2. Skriv sedan ut alla variabler till konsolen.

**Övning 1 - Jobba med variabler**
Skapa en variabel som heter <b>radie</b> som tilldelas värdet 5.<br>
Skapa sedan en variabel <b>omkrets</b> som tilldelas omkretsen av en cirkel med hjälp av radie variabeln.<br>
Formeln för omkrets är <i>O = 2&pi;r</i> och värdet på &pi; kan du sätta till 3.14

Skriv ut värdet på omkretsen med <i>alert()</i>.

**Övning 2 - Rätt namngivning på variabler**
   1. Skapa en variabel med namnet på vår planet. Hur skulle du namnge en sådan variabel?
   2. Skapa en variabel för att lagra namnet på en aktuell besökare på en webbplats. Hur skulle du namnge den variabeln?

**Övning 3 - Jobba med konstanter**
   1. Skapa en konstant `pi` med pi-värdet och 3 decimaler.
   2. Tilldela `pi` ett annat värde.
   3. Skriv ut `pi` med `alert()`, vad händer och varför?
   
## 1.2 Datatyper
### Övningsuppgifter
**Övning 1 - Skriv ut datatyperna** <br>
Fundera över vad du tror följande har för datatyper, skriv det på ett papper 

1. `0`
2. `3.14`
3. `"3.14"`
4. `true`
5. `"foo"`
6. `null`
7. `5 > 4`

Skriv sedan ut med `console.log()` typerna med `typeof()` konstruktionen.
Blev utskrifterna det du förväntade dig?
  
## 1.3 Operatorer
### Övningsuppgifter

**Övning 0 - addera, subtrahera, multiplicera**
  1. Skapa 2 variabler med valfria tal (tex tal1 = 5).
  2. Skriv sedan ut *addition*, *subtration* och *multiplikation* av talen med variablerna och *console.log()*

**Övning 1 - Postfix**  
Vilka är de slutliga värdena för alla variabler a, b, c och d efter koden nedan?
```
let a = 1;

let b = a++; // ?
```

Bekräfta det sedan genom att skriva ut `b` med `console.log()`.

## 1.4 Jämförelser
### Övningsuppgifter
**Övning 1. Vad blir resultatet för dessa uttryck?**
``` 
1. 5 > 4
2. "apple" > "pineapple"
3. "2" > "12"
```
Bekfräfta det med `console.log()`.

## 1.5 If-satser
### Övningsuppgifter

**Övning 0. If sats**
1. Ta en ett namn från användaren med *prompt* och tilldela det till en variabel name.
2. Används if-sats för att kontrollera om namnet är "Kalle". Stämmer det skriv ut "Du heter Kalle".
3. Utöka sedan med else del där du skriver du skriver ut "Du heter inte Kalle!".

**Övning 2. Skriv om "if"-satserna till "if-else-if-else"-sats**<br>
Skriv om koden nedan med hjälp av `if-else-if-else`-sats:
```
let a = +prompt('a?', '');

if (a == 0) {
  alert( 0 );
}
if (a == 1) {
  alert( 1 );
}

if (a == 2 || a == 3) {
  alert( '2,3' );
}
```

**Övning 2. Visa tecknet**<br>
Använd `if..else` och skriv koden som tar in ett nummer med `prompt()` och visar sedan med `alert()` beroende på värdet:

- `1`, om värdet är större än noll,
- `-1`, om mindre än noll,
- `0`, om det är lika med noll.

I denna uppgift antar vi att vi alltid får in ett nummer.

## 1.6 Loopar: for
### Övningsuppgifter

**Övning 1. Vilka värden visas av for-loopen?**<br>
Skapa en for-loop som loopar igenom talen 1 till 21 och skriver ut talet till konsolen.  

**Övning 2. Skriv ut jämna siffror i loopen**<br>
Använd `for`-loopen för att skriva ut jämna siffror från `2` till `10`.

## 1.7 Funktioner
### Övningsuppgifter
**Övning 1. Skriv om "switch"-satsen till "if"-satser**<br>
Följande funktion returnerar sant om parametern `age` är högre än 18.
Annars skriver den ut "Du är för ung tyvärr!":
```
function checkAge(age) {
  if (age > 18) {
    return true;
  } else {
    // ...
    alert('Du är för ung tyvärr!');
  }
}
```
Fungerar funktionen annorlunda om `else` delen tas bort?
```
function checkAge(age) {
  if (age > 18) {
    return true;
  }
  // ...
  alert('Du är för ung tyvärr!');
}
```

**Övning 2. Funktionen min(a, b)**<br>
Skriv en funktion `min(a, b)` som returnerar det minsta av två siffror `a` och `b`.
Till exempel:
```
min(2, 5) == 2
min(3, -1) == -1
min(1, 1) == 1
```


**Övning 3. Fuktionen pow(x, n)**<br>
Skriv en funktion `pow(x, n)` som returnerar `x` i potens `n`. Eller med andra ord multiplicerar `x` med sig `n` gånger och returnerar resultatet. Funktionen behöver bara stödja positiva värden 1, 2, 3...
```
min(2, 5) == 2
min(3, -1) == -1
min(1, 1) == 1
```

## 1.9 Objekt
### Övningsuppgifter

**Övning 1. Animal Objekt**<br>
1. Skapa ett objekt animal1 som har egenskaperna ,type:"cat" , name: 'Kalle', age: 3
2. Skapa ett till objekt animal2 som har egenskaperna ,type:"dog" , name: 'Nalle', age: 3
3. Skriv ut någon egenskap till konsolen av varje animal objekt.


**Övning 2. ändra och lägga till**<br>
Skriv koden, en rad för varje åtgärd:
Från föregående uppgift gör följande ändringar
1. På animal1 objektet ändra namn till `Nalle`.
2. Lägg till metoden `scream` med värdet `John`.
3. Lägg till egenskapen `surname` med värdet `Smith`.
4. Ändra på värdet av `name` till `Pete`.


**Övning 3.Summera objekt egenskaper**<br>
Vi har ett objekt som lagrar löner för vårt team:
```
let salaries = {
  John: 100,
  Ann: 160,
  Pete: 130
}
```
Skriv koden för att summera alla löner och lagra den variabelb `sum`. Bör vara `390` i exemplet ovan.

## 1.10 Listor (Array)
### Övningsuppgifter
**Övning 1. Loopa igenom array med namnen i er grupp**<br>
1. Skapa en array med namn på alla gruppmedlemmar.
2. Använd en for-loop och loopa igenom alla gruppmedlemmar i arrayen/listan.
3. För varje medlem skriv ut namnet med `alert()`.

**Övning 2. Blir listan (arrray) kopierad**<br>

Vad kommer den här koden att visa?

```
let fruits = ["Apples", "Pear", "Orange"];

// push a new value into the "copy"
let shoppingCart = fruits;
shoppingCart.push("Banana");

// what's in fruits?
alert( fruits.length ); // ?
```

**Övning 3. Listor med objekt**<br>

Vad kommer den här koden att visa?

```
let fruits = ["Apples", "Pear", "Orange"];

// push a new value into the "copy"
let shoppingCart = fruits;
shoppingCart.push("Banana");

// what's in fruits?
alert( fruits.length ); // ?
```

## Övning 4 - For-loop på lista med objekt

Du har en lista nedan med objekt som innehåller information om städer.

```
[{id: 1, name: 'Västerås', county: 'Västmanland'},
{id: 2, name: 'Karlstad', county: 'Värmland'},
{id: 3, name: 'Borlänge', county: 'Dalarna'},
{id: 4, name: 'Malmö', county: 'Skåne'},
{id: 5, name: 'Helsingborg', county: 'Skåne'},
{id: 6, name: 'Kiruna', county: 'Lappland'}]
```
Tilldela listan till en variabel som heter **cities**.
Loopa sedan igenom listan och skriv ut information om varje list-objekt på följande format:
**name - county**, för första objektet skulle det se ut så här **Västerås - Västmanland**.