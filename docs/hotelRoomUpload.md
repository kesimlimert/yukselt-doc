### Otel Odalarinin Yuklenmesi

JavaScript Ornegi:
```javascript
 fetch("https://yukseltapi.com/uploadRooms", {
  method: "POST",
  body: JSON.stringify({
    rooms: [
      {
        roomView: "Deniz Manzarali",
        roomType: "King Deluxe",
        roomSpecs: ['Mutfak', 'Jakuzi', 'King Boy Yatak'],
        pricePerNight: "3000",
        currency: "$",
        roomName: "Deniz Manzarali Guzel Oda",
        roomId: "1q23ed"
      },
      {
        roomView: "Deniz Manzarali",
        roomType: "King Deluxe",
        roomSpecs: ['Mutfak', 'Jakuzi', 'King Boy Yatak'],
        pricePerNight: "3000",
        currency: "$",
        roomName: "Deniz Manzarali Obur Oda",
        roomId: "2q13ea"
      },
      ...
    ];
  }),
  headers: {
    "Content-type": "application/json; charset=UTF-8"
  }
})

```
