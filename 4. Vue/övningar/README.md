# Övningar

Kopiera följande kod som mall för övningarna. Skapa en ny html-fil och lägg in koden.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body id="body">
    <div>
      <h1>{{name}}</h1>
    </div>
    <script src="https://unpkg.com/petite-vue"></script>
    <script>
      const data = {
        name: "Kalle Kula",
      };

      PetiteVue.createApp(data).mount("#body");
    </script>
  </body>
</html>
```

#### Övning 0.1 - Interpolering

1. Skapa en data variabel _message_ med värdet "Hello Vue!" och visa värdet i HTML koden genom interpolering {{}}.
2. Hitta på lite fler variabler med olika typer och visa dem med.

#### Övning 0.2 - Attribut bindning

1. Skapa en data variabel _link_ med värdet på en valfri Youtube video. Skapa sedan en länk-tagg <a>a</a>-tagg som binder till länk variabeln, verifiera så att länken fungerar när du klickar på den.
2. Skapa en data variabel _image_ med värdet på en bildaddress på en valfri bild från nätet.
   Skapa sedan en img-tagg vars src-attribut binder till image variabeln och visar bilden på skärmen.

#### Övning 0.3 - HTML Villkor

1. Skapa en data variabel _age_ med värdet på en ålder som du själv bestämmer.
2. Använd sedan _v-if_ direktivet i HTML section för att kontrollera ifall age variabeln är större än 18. Stämmer villkoret ska en p-tagg visas med texten "Du får ta körkort! annars visas texten "Tyvärr du får inte ta körkort!".

#### Övning 0.4 - Loopar i HTML med v-for

1. Skapa en data variabel som är en lista med talen _1 till 10_.
2. Använd sedan _v-for_ direktivet i HTML section för att loopa/gå igenom listan med talen och skriv ut dem med hjälp av interpolering och en oordnad lista ul/li.

#### Övning 0.5 - Eventhantering med knappar

1. Skapa en data variabel som heter _name_ och som innehåller ert förnamn. Visa namnet med interpolering på skärmen.
2. Skapa sedan en knapp med texten "byt namn", koppla på ett klick event/metod som körs när man klickar på knappen så att _name_ variabeln uppdateras till ditt efternamn istället. Du kan döpa metoden till vad du vill tex changeName().

### Övning 0.6 - Två-vägs bindning och computed (beräknade variabler)

1. Skapa två data-variabler för firstName och lastName.
2. Skapa två input-fält som har två-vägbindning med lastName och firstName dvs **v-model**.
3. Visa för och efternamn brevid varandra med interpolering {{firstName}} {{lastName}}.

#### Övning 0.7 - API anrop för att hämta ett objekt och presentera det

1. Skapa en variabel som heter _photo_ som är null från början.
2. I _created()_ metoden gör ett API-anrop med _fetch()_ som hämtar ett photo objekt och tilldelar det till _photo_ data variabeln.<br>
   <https://jsonplaceholder.typicode.com/photos/1>
3. Presentera sedan photo objektets värden i html med interpolation.

#### Övning 0.8 - API anrop för att hämta en lista av objekt

1. Skapa en variabel som heter _photos_ som är null från början.
2. I _created()_ metoden gör ett API-anrop med _fetch()_ som hämtar ett photo objekt och tilldelar det till _photo_ data-variabeln.<br>
   <https://jsonplaceholder.typicode.com/photos/1>
3. Presentera sedan photo objektets värden i html med interpolation.

### Övning 0.9 - Computed & Watchers

Skapa Computed och Watch exemplen i powerpoint presentationen och försök förstå vad dem gör.

### Övning 0.10 - Class-bindning

1. Skapa en div.
2. Skapa två klasser innanför style taggen som heter green-background och red-background.
   Som ger diven följande egenskaper, men ska ha olika färger dvs grönt och rött.

```
  width: 200px;
  height: 200px;
  background-color: green;
```

3. Skapa en variabel isGreen som bestämmer vilken klass som appliceras på diven med hjälp av class-bindning.
4. Skapa en knapp som ändrar på isGreen och sedan på klassen.
