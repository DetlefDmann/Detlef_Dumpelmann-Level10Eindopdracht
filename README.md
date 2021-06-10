# Detlef_Dumpelmann-Level10Eindopdracht

Ik heb bij dit project de "Live Sass Compiler" extensie verruild voor "DartJS".

>Dit heeft meerdere redenen: 

1. DartJS geeft de mogelijkheid om CSS-grid op een moderne manier te gebruiken.
2. DartJS maakt het mogelijk om @use te gebruiken i.p.v. @import. Op [de website van Sass-lang.com](https://sass-lang.com/documentation/at-rules/import#importing-css) staat dat @import ontmoedigd wordt.
3. Live Sass Compiler van Ritwick Dey word al een tijdje niet meer onderhouden (11.07.2018 was de laatste keer).

Nadat er veel mensen in de opleiding problemen hadden met de "Live sass compiler" extensie van Ritwick Dey, besloot ik uit te gaan zoeken hoe het zit.
Zo ontdekte ik dus dat die versie niet onderhouden werd. Medestudent Glenn raadde mij DartJS aan en die werkte goed.
Uit de documentatie bleek dat "DartJS" het nieuwere "dart Sass" gebruikt in tegenstelling tot "Live sass compiler" dat het oudere "lib Sass" gebruikt.
Uiteindelijk bleek de "live sass compiler" van Glenn Marks ook "Dart Sass" te gebruiken, daarom werkt die ook correct.

M.v.g. Detlef Dumpelmann.

```javascript
  const endOfStory;
```
