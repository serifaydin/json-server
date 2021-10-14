# json-server
json-server
{
  "orders": [
    {
      "orderNumber": "00000001",
      "customerName": "Şerif Aydın",
      "carrierAccount": "YK",
      "orderDate": "11.20.2021",
      "id": 1
    },
    {
      "id": 2,
      "orderNumber": "00000002",
      "customerName": "Elif Aydın",
      "carrierAccount": "Aras",
      "orderDate": "11.10.2021"
    },
    {
      "id": 3,
      "orderNumber": "00000003",
      "customerName": "Çınar Aydın",
      "carrierAccount": "MNG",
      "orderDate": "13.20.2021"
    }
  ],
  "orderDetails": [
    {
      "id": 1,
      "orderId": 1,
      "itemCode": "item code 1",
      "itemDescription": "item Description 1"
    },
    {
      "id": 2,
      "orderId": 1,
      "itemCode": "item code 2",
      "itemDescription": "item Description 2"
    },
    {
      "id": 3,
      "orderId": 2,
      "itemCode": "item code 3",
      "itemDescription": "item Description 3"
    },
    {
      "id": 4,
      "orderId": 2,
      "itemCode": "item code 4",
      "itemDescription": "item Description 4"
    }
  ],
  "orderCustomerDetail": [
    {
      "orderId": 1,
      "AddressText": "üsküdar"
    },
    {
      "orderId": 2,
      "AddressText": "Ümraniye"
    }
  ]
}
