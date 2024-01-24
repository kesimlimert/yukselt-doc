# Musteri Hesaplarinin Yuklenmesi

JavaScript Ornegi:
```javascript
 fetch("https://yukseltapi.com/uploadCustomers", {
  method: "POST",
  body: JSON.stringify({
    customers: [
      {
        firstName: "John",
        lastName: "Doe",
        email: "john@mail.com",
        phone: "5454323154",
      },
      {
        firstName: "Dohn",
        lastName: "Joe",
        email: "dohn@mail.com",
        phone: "5454323154",
      },
      {
        firstName: "Veli",
        lastName: "Joe",
        email: "veli@mail.com",
        phone: "5454323154",
      },
      ...
    ];
  }),
  headers: {
    "Content-type": "application/json; charset=UTF-8"
  }
})

```
