Task performed during Front-End Developer Bootcamp

# Moduł JavaScript

## Lekcja 4

### Zadanie 2 - poziom podstawowy

Stwórz funkcję `createList`, która będzie tworzyła 3 elementową listę zakupów. Lista powinna mieć postać znacznika `<ul>`, posiadać identyfikator (id) `list`, a zawartość elementów `<li>` może być dowolna (jakikolwiek tekst). W zadaniu należy użyć funkcji `document.createElement` do tworzenia elementów i `appendChild` do podpięcia listy do elementu `<body>`. Funkcja musi również zwrócić (`return`) tą listę na samym końcu.

notka: Do stworzenia 3-elementowej listy możesz użyć takiej techniki:

```javascript
["Item 1", "Item 2", "Item 3"].map((item) => {
  const li = document.createElement("li");
  li.textContent = item;
  return li;
});
```

Przykładowy input:
brak

Przykładowy output:
Element `<ul id="list"><li>Test 1</li><li>Test 2</li><li>Test 3</li></ul>`
