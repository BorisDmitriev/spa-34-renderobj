# `02` Rendern von Objekten

Lass uns jetzt eine komplexere Variable als HTML rendern. Wie wäre es z.B. mit dem folgenden Objekt von Nutzer-Informationen:

```js
const customer = {
  firstName: 'Bob',
  lastName: 'Dylan',
};
```

Erinnerung: Um an eine Eigenschaft (property) des `customer`-Objekts zu kommen, müssen wir die Punkt-Schreibweise benutzen:

```js
console.log(customer.firstName); // wird "Bob" in der Browser-Konsole ausgeben
```

# :speech_balloon: Aufgabe:

Öffne die `App.js` und schreibe den nötigen JSX-Code, um das folgende Endergebnis zu erzeugen:

```jsx
<div>
  <h1>My name is Bob</h1>
  <h2>My last name is Dylan</h2>
</div>
```
