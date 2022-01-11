# Wstęp do Cross Site Scripting
**Uwaga** - Wymagane jest konto na PortSwigger
> [Link](https://portswigger.net/users/register)
## Kolejność zadań
### Zadanie1
Reflected XSS into HTML context with nothing encoded
> [Link](https://portswigger.net/web-security/cross-site-scripting/reflected/lab-html-context-nothing-encoded)
<details>
  <summary>Podpowiedź</summary>
	Poszukaj miejsca w którym możnaby umieścić Payload jak np. jakiś formularz, komentarz itd.    
</details>

### Zadanie2
Stored XSS into HTML context with nothing encoded
> [Link](https://portswigger.net/web-security/cross-site-scripting/stored/lab-html-context-nothing-encoded)
<details>
  <summary>Podpowiedź</summary>
	Poszukaj miejsca w którym możnaby umieścić Payload jak np. jakiś formularz, komentarz itd.    
</details>

### Zadanie3
Stored DOM XSS
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-dom-xss-stored)

<details>
  <summary>Mała podpowiedź</summary>
     Sprawdź w jaki sposób strona traktuje twój payload, pomocna może być funkcja 'zbadaj element'
</details>
<details>
  <summary>Podpowiedź</summary>
    Napisz komentarz zawierający 2 tagi html, np. "&lttag1&gt&lttag2&gt". Następnie sprawdź jak strona traktuje obydwa te tagi. 
</details>
<details>
  <summary>Duża podpowiedź</summary>
    Gdy napiszesz komentarz zawierający 2 tagi html, pierwszy jest traktowany jako tekst i jest umieszczany w "", z kolei drugi jest traktowany jako zwykły tag html. 
</details>

### Zadanie4
Reflected XSS into attribute with angle brackets HTML-encoded
> [Link](https://portswigger.net/web-security/cross-site-scripting/contexts/lab-attribute-angle-brackets-html-encoded)
<details>
<summary>Podpowiedź</summary>
    Zauważ że treść w searchboxie umieszczana jest w cudzysłowie, zastanów się jak to obejść
</details>
<details>
  <summary>Duża podpowiedź</summary>
   Spróbuj umieścić kod JS po wpisaniu "onmouseover="
</details>

### Zadanie5
DOM XSS in innerHTML sink using source location.search
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-innerhtml-sink)
<details>
<summary>Podpowiedź</summary>
    Spróbuj wykorzystać znacznik &ltimg&gt
</details>
<details>
  <summary>Duża podpowiedź</summary>
   Wywołaj kod JS event handlerem onerror
</details>

### Zadanie6
DOM XSS in document.write sink using source location.search
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-document-write-sink)
<details>
  <summary>Mała podpowiedź</summary>
	Przydatnym narzędziem będzie 'zbadaj element'    
</details>
<details>
  <summary>Podpowiedź</summary>
	Wyszukaj coś i zbadaj jak napis, który wyszukałeś, jest przechowywany w kodzie źródłowym strony   
</details>
<details>
  <summary>Duża podpowiedź</summary>
	Musisz uciec z tagu &ltimg src="..."&gt
</details>
<details>
  <summary>Bardzo duża podpowiedź</summary>
	Musisz uciec z tagu &ltimg src="..."&gt, aby to zrobić, poprzedź swój payload znakami "&gt
</details>

### Zadanie7
DOM XSS in jQuery anchor href attribute sink using location.search source
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-jquery-href-attribute-sink)
<details>
  <summary>Mała podpowiedź</summary>
    Kliknij w link do strony 'Feedback' i przyjrzyj się URL
</details>
<details>
  <summary>Podpowiedź</summary>
    Zastanów się do jakiego elementu strony odnosi się URL i jak dane tam zawarte są używane w kodzie źródłowym strony.
</details>
<details>
  <summary>Duża podpowiedź</summary>
    URL podstrony 'Feedback' definiuje co się stanie gdy wciśniemy przycisk 'Back'. Adres do którego mamy się cofnąc zawarty jest w tagu 'href'. Sprawdź jak można użyć javascript w tagu 'href' 
</details>

### Zadanie8
DOM XSS in document.write sink using source location.search inside a select element
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-document-write-sink-inside-select-element)
<details>
  <summary>Mała podpowiedź</summary>
  Spróbuj dodać &storeId=skrypt do URL na ekranie produkut i zobacz co się stanie 
</details>
<details>
  <summary>Podpowiedź</summary>
    Zamknij zacznik za pomocą "&gt&lt/select&gt 
    Spacja zakodowana jest jako %20
</details>
<details>
  <summary>Duża podpowiedź</summary>
    Spróbuj przy pomocy znacznika &ltimg&gt sprawić aby wykonywał się kod JS przy błędzie 
</details>

### Zadanie9
Reflected XSS in canonical link tag
> [Link](https://portswigger.net/web-security/cross-site-scripting/contexts/lab-canonical-link-tag)

## Artykuł o technicznych aspektach Samy
> [Link](https://samy.pl/myspace/tech.html)

<br/><br/>
