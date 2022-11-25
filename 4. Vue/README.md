# VUE

Vue är ett väldigt trevligt javascript ramverk för att utveckla applikationer med.

## Intro

- Vue är ett progressivt open-source ramverk för att bygga användargränssnitt, till en början utvecklad av en Google avhoppare som heter Evan You, men underhålls idag av ett team.

- Core delen av ramverket är endast fokuserat på visningsskiktet och är enkelt att komma igång med.

- Vue är också fullt kapabelt att bygga sofistikerade applikationer (Single Page Applications).

- Vue är flexibelt och enkelt.

- Vue tillåter dig att använde det i en del av en befintlig applikation (plugin) eller hantera hela applikationen från start (CLI).

- Vue förser oss med reaktivitet vilket gör att våra vyer/sidor automagiskt uppdateras när vårat data ändras.

## Nytt projekt från start

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
