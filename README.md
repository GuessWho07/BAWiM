# Wstęp do Cross Site Scripting
**Uwaga** - Wymagane jest konto na PortSwigger
> [Link](https://portswigger.net/users/register)
## Kolejność zadań
### Zadanie1
Reflected XSS into HTML context with nothing encoded
> [Link](https://portswigger.net/web-security/cross-site-scripting/reflected/lab-html-context-nothing-encoded)
> <details>
  <summary>Podpowiedź</summary>
	Poszukaj miejsca w którym możnaby umieścić Payload jak np. jakiś formularz, komentarz itd.    
</details>
## Zadanie2
Stored XSS into HTML context with nothing encoded
> [Link](https://portswigger.net/web-security/cross-site-scripting/stored/lab-html-context-nothing-encoded)
### Zadanie3
Stored DOM XSS
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-dom-xss-stored)
### Zadanie4
Reflected XSS into attribute with angle brackets HTML-encoded
> [Link](https://portswigger.net/web-security/cross-site-scripting/contexts/lab-attribute-angle-brackets-html-encoded)
### Zadanie5
DOM XSS in innerHTML sink using source location.search
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-innerhtml-sink)
### Zadanie6
DOM XSS in document.write sink using source location.search
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-document-write-sink)
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
  Spróbuj dodać <i>&storeId=skrypt</i> do URL na ekranie produkut i zobacz co się stanie 
</details>
<details>
  <summary>Podpowiedź</summary>
    placeholder
</details>
<details>
  <summary>Duża podpowiedź</summary>
    placeholder 
</details>

### Zadanie9
Reflected XSS in canonical link tag
> [Link](https://portswigger.net/web-security/cross-site-scripting/contexts/lab-canonical-link-tag)

## Stored XSS
## Zadanie1 Bardzo łatwe komentarz
Stored XSS into HTML context with nothing encoded
> [Link](https://portswigger.net/web-security/cross-site-scripting/stored/lab-html-context-nothing-encoded)
### Zadanie2 Średnie komentarz
Stored DOM XSS
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-dom-xss-stored)
<br/><br/>

## Reflected XSS
### Zadanie1 Bardzo łatwe searchbox
Reflected XSS into HTML context with nothing encoded
> [Link](https://portswigger.net/web-security/cross-site-scripting/reflected/lab-html-context-nothing-encoded)
### Zadanie3 Średnie Searchbox
Reflected XSS into attribute with angle brackets HTML-encoded
> [Link](https://portswigger.net/web-security/cross-site-scripting/contexts/lab-attribute-angle-brackets-html-encoded)
### Zadanie4 Bardzo trudne URL
Reflected XSS in canonical link tag
> [Link](https://portswigger.net/web-security/cross-site-scripting/contexts/lab-canonical-link-tag)
<br/><br/>

## DOM-based XSS
### Zadanie1 Średnie HTML
DOM XSS in document.write sink using source location.search
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-document-write-sink)
### Zadanie2 Średnie Searchbox
DOM XSS in innerHTML sink using source location.search
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-innerhtml-sink)
### Zadanie3 Trudne HTML
DOM XSS in document.write sink using source location.search inside a select element
> [Link](https://portswigger.net/web-security/cross-site-scripting/dom-based/lab-document-write-sink-inside-select-element)
### Zadanie4 Bardzo Trudne HTML
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
<br/><br/>

## Artykuł o technicznych aspektach Samy
> [Link](https://samy.pl/myspace/tech.html)

<br/><br/>
