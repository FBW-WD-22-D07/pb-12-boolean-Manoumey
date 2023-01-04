# Grundlagen der Programmierung: Logische Operatoren
# Wahr oder Falsch?

### Anweisungen
- Arbeite in `solution.js`
#### 1. Welcher Typ?
* Prüfe, ob `3` gleich `"3"` ist, indem du den "einfachen" Vergleich verwendest. Prüfe dann, ob sie gleich sind, indem du den strengen (strict) Vergleich verwendest.
**Fragen: Gib die Nummer der richtigen Antwort im Terminal aus (eine nach der anderen)**
* Welche der folgenden Möglichkeiten wird verwendet, um den WERT von zwei Variablen/Werten zu vergleichen?
1. =
2. ==
3. ===
4. alle der oben genannten
* Welche der folgenden Möglichkeiten wird verwendet, um den WERT und den TYP von zwei Variablen/Werten zu vergleichen?
5. =
6. ==
7. ===
8. keine der oben genannten
* Welche der folgenden Möglichkeiten wird verwendet, um einer Variablen einen Wert zuzuweisen?
9. =
10. ==
11. ===
12. const

#### 2. Nicht
* Vervollständige den folgenden ternären Code, um "good evening" mit "myVar" auszudrucken:
```javascript
let myVar = true;

console.log( .............. ? 'good morning' : 'good evening' );
```

#### 3. Kurzer Kreislauf
* Vervollständige den folgenden Code, indem du die Leerräume mit '&&' oder '||' ausfüllst, um den Wert zu erhalten, der zum Namen der Variablen passt:
(PS: diese Werte geben immer false zurück: `false` , `0`, `''`)

```javascript

let firstName = '' .... 'John' .... 0
let emptyStr = '' .... false .... 'Hello World'
let zero = '' .... false .... 0
let seven = 75 .... 'nine' .... 7

console.log(firstName,zero,emptyStr,seven);
```
