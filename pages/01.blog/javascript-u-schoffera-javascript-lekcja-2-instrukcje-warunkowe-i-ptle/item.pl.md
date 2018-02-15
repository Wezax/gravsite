---
title: 'JavaScript u Schoffera  - Javascript lekcja 2 (pętle i instrukcje warunkowe)'
media_order: petle.png
published: false
date: '14-02-2018 23:15'
taxonomy:
    tag:
        - informatyka
        - 3d
        - html
        - js
    author:
        - 'Adam Majewski'
jscomments:
    active: true
---

Kontynuując poprzednią lekcję omówimy niezbędne instrukcje potrzebne do stworzenia bardziej zaawansowanych skryptów. Mówimy tutaj o pętlach (for,do,while) i instrukcjach warunkowych (If,else).Zapraszam do wspólnej nauki!

===

W **zdjęciu** postu już możemy zauważyć parę nowych rzeczy. Uprośćmy nasz przykład z obrazka do takiej formy:
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

