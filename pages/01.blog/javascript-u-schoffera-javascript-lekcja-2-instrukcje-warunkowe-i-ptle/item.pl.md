---
title: 'JavaScript u Schoffera  - Javascript lekcja 2 (pętla for)'
published: true
date: '15-02-2018 23:15'
taxonomy:
    tag:
        - informatyka
        - 3d
        - html
        - js
jscomments:
    active: true
author: 'Adam Majewski'
---

Kontynuując poprzednią lekcję omówimy niezbędne instrukcje potrzebne do stworzenia bardziej zaawansowanych skryptów. Dzisiaj omówimy działanie pętli _for_. Zapraszam do wspólnej nauki!

===

W **zdjęciu** umieszczonym na górze postu, już możemy zauważyć parę nowych rzeczy. Uprośćmy nasz przykład z obrazka na potrzeby dzisiejszej lekcji:
```js
for(var i=0; i<10; i++){
	document.write('<p>Nigdy nie będę denerwował Schoffera!</p>');
}
```
Żeby opisać co się dzieje w uproszczonym skrypcie najpierw musimy omówić składnie pętli _for_.
<h2 style="text-align: center">Pętla <i>For</i></h2>
```js
for(/*przypisanie wartosci do zmiennej, która będzie inkrementowana/dekrementowana*/; /*ustalenie warunku pętli(dopóki warunek jest prawdziwy powtazraj)*/; /*inkrementacja/dekrementacja/*){
 	// Kod do powtarzania   
}
```
Wygląda skomplikowanie? W praktyce to nic skomplikowanego. Odwołując się do uproszczonego przykładu uzupełnijmy naszą pętlę:
```js
for(var i = 0; /*ustalenie warunku pętli(dopóki warunek jest prawdziwy powtazraj)*/; /*inkrementacja/dekrementacja/*){
 	// Kod do zapętlania 
}
```
Tutaj zadeklarowaliśmy zmienną _i_ i nadaliśmy jej wartość 0. Zmienna ta jest używana do wprowadzenia danych do pętli, które pomogą nam zbudować warunek.

> <span style="color: #a5f259">Ciekawostka</span>
> Nazwa zmiennej w tym miejscu może być dowolna ale przyjęło się, że powinno się używać liter _i_, _j_ itd.

***

> <span style="color: #a5f259">Ciekawostka</span>
> Zadeklarować zmienną można też poza nawiasem:
> ```js
> var i = 0;
> for(i; /*ustalenie warunku pętli(dopóki warunek jest prawdziwy powtazraj)*/; /*inkrementacja/dekrementacja/*){
>  //Kod do zapętlania
>}
> ```

Dalej mamy warunek:
```js
for(var i = 0; i<10; /*inkrementacja/dekrementacja/*){
	//Kod do zapętlania
}
```
Tutaj mówimy pętli, że dopóki zmienna _i_ jest mniejsza niż 10, powinna powtarzać _kod w klamrach_.

Na samym końcu mamy _inkrementacje_ i _dekrementacje_.
> <span style="color: #619bf9;">Definicja</span>
> **Inkrementacja/Dekrementacja** polega na zwiększaniu/zmniejszaniu wartości zmiennej o **jeden**.

Inkrementacje w JavaScript zapisujemy w następujący sposób:
```js
for(var i = 0; i<10; i++){
	//Kod do zapętlania
}
```
Jeżeli chodzi o dekrementację musimy zmienić nasza pętle, ponieważ jeżeli zamienimy _i++_ na _i--_ pętla będzie się wykonywać w nieskończoność. Powód tego jest taki, że zmienna i będzie się zmieniała w liczby -1,-2,-3 itd.Tak wygląda poprawny zapis pętli, która wykorzystuje dekrementacje:
```js
for(var i = 10; i>0; i--){
	//Kod do zapętlania
```
Jak widzimy teraz pętla będzie wykonywała działanie _i - 1_ za każdym razem kiedy pętla zostanie wykonana, aż kiedy zmienna _i_ przestanie spełniać warunek (czyli _i_ będzie się równało zero).

Skoro znamy już działanie pętli _for_, omówmy na szybko dzisiejszy przykład: 
```js
for(var i=0; i<10; i++){
	document.write('<p>Nigdy nie będę denerwował Schoffera!</p>');
}
```
Nasza pętla, będzie wypisywała zdanie: _Nigdy nie będę denerwował Schoffera!_, dopóki warunek _i<10_ przestanie być _prawdą_.W tym przykładzie pętla wykona się 10 razy, więc będziemy mieli 10 zdań na temat nie denerowania Pana Schoffera.

Tutaj możesz zobaczyć jak to wygląda w praktyce:

<p data-height="265" data-theme-id="0" data-slug-hash="PQJdgE" data-default-tab="js,result" data-user="Wezax" data-embed-version="2" data-pen-title="Post 2" class="codepen">See the Pen <a href="https://codepen.io/Wezax/pen/PQJdgE/">Post 2</a> by Wezax (<a href="https://codepen.io/Wezax">@Wezax</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

To na dziś wszystko, do zobaczenia w następnym poście, gdzie omówimy pętle _do_ i _while_!

***



