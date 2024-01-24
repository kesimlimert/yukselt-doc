# Rezervasyon Verilerinin Yukselt'e Aktarimi

Her otelin rezervasyon bilgilerini takip edebilmemiz icin her bir otelin kendine ait API endpoint' u bulunmasi gerekmektedir. Bu endpoint' u Saleor Dashboard' da otel yaratilirken doldurulan forma eklenmelidir.

JavaScript Ornegi:
```javascript
 fetch("https://yukseltapi.com/reservations/[otelinizin Id si]", {
  method: "POST",
  body: JSON.stringify({
    reservations: [
      {
        id: "resv_101",
        customerId: "cust_101",
        roomId: "room_101",
        checkIn: "2021-07-01T14:00:00Z",
        checkOut: "2021-07-05T11:00:00Z",
        notes: "Sea-facing room requested",
        guests: {
          adults: [
            {
              firstName: "John",
              lastName: "Doe",
            },
          ],
          children: [
            {
              firstName: "Junior",
              lastName: "Doe",
            },
          ],
        },
        customerDetails: {
          firstName: "John",
          lastName: "Doe",
          email: "johndoe@example.com",
          phone: "+123456789",
        },
        payment: {
          status: "Pending",
          amount: 1200,
          currency: "USD",
        },
      },
    ];
  }),
  headers: {
    "Content-type": "application/json; charset=UTF-8"
  }
})

```
