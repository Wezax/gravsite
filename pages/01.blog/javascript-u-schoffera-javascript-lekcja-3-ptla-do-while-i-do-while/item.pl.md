---
title: 'JavaScript u Schoffera - JavaScript lekcja 3 (instrukcja warunkowa if...else) '
published: false
date: '19-02-2018 12:40'
taxonomy:
    tag:
        - informatyka
        - 3d
        - html
        - js
author: 'Adam Majewski'
---

Witam w kolejnej części kursu. Dzisiaj poznamy instrukcję warunkową _if...else_.
Zapraszam do czytania :)

===

Składnia tej instrukcji jest następująca:
```js
if(/* warunek do spełnienia */){
	/* kod, który będzie wykonany jeżeli warunek się spełni */
}
else{
	/* kod, który będzie wykonany jeżeli warunek się nie spełni */
}
```

Łatwe, prawda? Warunkiem instrukcji może być na przykład: 
```js
if(10>5){
	document.write('Ten warunek jest prawdziwy');
}
```
W tym przypadku ten warunek zawsze będzie prawdziwym, _ponieważ 5 zawsze będzie mniejsze niż 10_, więc kod w środku się wykona.

Jeżeli zmienimy lekko nasz warunek: 
```js
if(10<5){
	document.write('Ten warunek jest prawdziwy');
}
```

To po wykonaniu skryptu nic nam się nie wyświetli, ponieważ tym razem nasz waruenk nigdy nie będzie _prawdziwy_.

Zmodyfikujmy nasz kod kolejny raz:

if(10<5){
	document.write("Ten warunek jest prawdziwy");
}
else{
	document.write('Ten warunek nie jest prawdziwy');
}

W tym przypadku otrzymamy zdanie _Ten warunek nie jest prawdziwy_, zamiast pustego dokumentu. Dzieję się tak za sprawą naszej instrukcji _else_. Instrukcja ta pozwala nam na wykonanie jakiegoś kodu bloku kiedy warunek w _if_ nie jest prawdziwy.
Tutaj działający przykład.



