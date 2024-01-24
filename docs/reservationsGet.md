# Rezervasyonlarin Cekilmesi

JavaScript Ornegi:
```javascript
 fetch("https://yukseltapi.com/reservationsGet")
  .then((response) => response.json())
  .then((json) => console.log(json));

```