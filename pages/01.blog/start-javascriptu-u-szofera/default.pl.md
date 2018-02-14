---
title: 'Start JavaScriptu u Szofera'
media_order: headline.png
taxonomy:
    category:
        - blog
    tag:
        - informatyka
        - 3d
        - html
        - js
template: item
username: ''
author: 'Adam Majewski'
---

# JavaScript cz.1

Dzisiaj (14.02.2018) zaczeliśmy wspaniałą naukę javascriptu u ukochanego nauczyciela Szofera (nazwizko zmienione, żeby nie było problemów). Dowiedz się czgo się nauczyliśmy!

===

Zaczęliśmy od wyjaśnienia co to w sumie jest JS. Żeby zaoszczędzić wam nudnej definicji zapamiętajmy to:
 	> JavaScript to język skryptów po stronie klienta. 

Wad i zalet nie będę wypisywał, więc przejdźmy do ciekawszej części czyli pierwszy program. Zanim przejdziemy do programu musimy się zapoznać ze sposobem dodawania skryptu do strony. Możemy to zrobić na dwa sposoby:
1. Wpisując skrypt do kodu HTML:
```html
<script>
    /* Twój kod */
</script>
```
2. Dołączając plik skryptu do kodu HTML
```html
<script src="nazwapliku.js"></script>
```

## Początki mamy za sobą, więc czas na pierwszy program, który wystąpił na lekcji!
Kod tego programu jest następujący: 
```js
document.write("Hello World!");
```
Po uruchomieniu strony zostanie wyświetlony napis _Hello World!_ . Przejdźmy teraz do wyjaśnienia tej funkcji.
Człon _document_ odowiada za odwołanie się do strony (czyli naszego kodu HTML). Mówiąc prościej 

