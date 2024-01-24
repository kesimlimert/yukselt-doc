### Aktivitelerin Yuklenmesi

JavaScript Ornegi:
```javascript
 fetch("https://yukseltapi.com/uploadActivities", {
  method: "POST",
  body: JSON.stringify({
    activities: [
      {
        activityName: "Deniz Turu",
        activityType: "Su aktivitesi",
        price: "300",
        currency: "$"
      },
      {
        activityName: "Parasut",
        activityType: "Su aktivitesi",
        price: "200",
        currency: "$"
      },
      ...
    ];
  }),
  headers: {
    "Content-type": "application/json; charset=UTF-8"
  }
})

```
