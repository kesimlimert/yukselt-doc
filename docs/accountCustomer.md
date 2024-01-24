# Musteri Hesabi Olustumak

JavaScript Ornegi:
```javascript
 fetch("https://yukseltapi.com/createCustomer", {
  method: "POST",
  body: JSON.stringify({
        firstName: "John",
        lastName: "Doe",
        email: "john@mail.com",
        phone: "5454323154",
    },
  }),
  headers: {
    "Content-type": "application/json; charset=UTF-8"
  }
})

```