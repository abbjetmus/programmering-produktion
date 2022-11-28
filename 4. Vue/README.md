# VUE

Vue är ett väldigt trevligt javascript ramverk för att utveckla applikationer med.

## Intro

Vue är ett JavaScript bibliotek som används för att på ett smidigt sätt koppla JavaScripten till HTMLen.
Vue ger oss superkrafter och är ett reaktivt bibliotek, vilket innebär att när variabler ändrar på sig i JavaScript syns ändringen direkt i HTMLen, vilket är mycket trevligt. För att använda Vue i er hemsida behövs 3 saker.

1. En script tagg som importerar dvs hämtar vue:  
```html
<script src="https://unpkg.com/petite-vue"></script>
```

2. En script tagg med vår vue kod:

```html
    <script>
      const data = {
        name: "Kalle Kula",
      };
      PetiteVue.createApp(data).mount("#body");
    </script>
```

Vi ska bara göra våra ändringar


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
