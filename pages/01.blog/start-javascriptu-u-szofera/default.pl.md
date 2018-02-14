---
title: 'JavaScript u Schoffera - JavaScript lekcja 1 (podstawy składni i zmienne)'
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

Dzisiaj (14.02.2018) zaczeliśmy wspaniałą naukę javascriptu u ukochanego nauczyciela Schoffera (nazwizko zmienione, żeby nie było problemów). Dowiedz się czego się nauczyliśmy!

===

**Zaczęliśmy od** wyjaśnienia co to w sumie jest JS. Żeby zaoszczędzić wam nudnej definicji zapamiętajmy to:
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
Człon _document_ odowiada za odwołanie się do strony (czyli naszego kodu HTML). Mówiąc prościej mówimy skryptowi, że chcemy się dostać do kodu strony.Część _write_ służy nam do dopisania tekstu do już istniejącgo kodu HTML. Oczywiście znakiem _;_ informujemy skrypt, że jest to koniec tej funkcji.

> <span style="color: #d84843"><b>Uwaga!</b></span>
> _write_ dopisuje te wartości do kodu HTML, więc powinniśmy stosować tagi typu:
> ```html 
> 	<p></p>
> ```

Tutaj działający, poprawny przykład:

<p data-height="265" data-theme-id="0" data-slug-hash="QQMzJz" data-default-tab="js,result" data-user="Wezax" data-embed-version="2" data-pen-title="Post-1" class="codepen">See the Pen <a href="https://codepen.io/Wezax/pen/QQMzJz/">Post-1</a> by Wezax (<a href="https://codepen.io/Wezax">@Wezax</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

### Zmienne w JS

Poznaliśmy również składnie zmiennych.
>Zmienne w  java scripcie

>możesz zwać jak chcesz

>mogą być cyniczne

>a mogą też nie :)

> ~Michał Piasecki


W JavaScriptcie zmienne inicjuje sie przy użyciu słowa _var_ i użyciem nazwy zmiennej: 
```js
var zwierze = 'kot';
```

Zmienne w js same dostosowuja swój typ do przechowawywanych danych (zmienna _zwierze_ przechowuje dane typu string).

Żeby włączyć zmienne do tekstu, używamy znaku "+":
```js
var zwierze = 'kot';
document.write('<p>Moje zwierze to: ' + zwierze + '.</p>');
```
Oto działający przykład: 

<p data-height="265" data-theme-id="0" data-slug-hash="XZawVp" data-default-tab="js,result" data-user="Wezax" data-embed-version="2" data-pen-title="Post-1.2" class="codepen">See the Pen <a href="https://codepen.io/Wezax/pen/XZawVp/">Post-1.2</a> by Wezax (<a href="https://codepen.io/Wezax">@Wezax</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

I oto skończyliśmy lekcję pierwszą. Lekcja druga pojawi się niebawem :)
