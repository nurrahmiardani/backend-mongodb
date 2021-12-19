# Soal 1
Data aplikasi Skiljek 
- Full Name
- Email
- Phone Number

Relasi One to One

``` javascript
    {
        "_id": "ObjectId('AAAA')",
        "fullName": "Nurrahmi Ardani Risqy",
        "email": "nurrahmiardani@gmail.com",
        "phoneNumber": "01231324343"
    }
```

# Soal 2
Relasi Skilshop and Schema

- Full Name
- Phone Number
- Address (Max 2)

Relasi : one to few
 ```javascript
     {
        "_id": "ObjectId('AAAA')",
        "fullName": "Nurrahmi Ardani Risqy",
        "email": "nurrahmiardani@gmail.com",
        "phoneNumber": "01231324343",
        "address" : [
            {
                "street" : "Jalan Kartini no 200",
                "city" : "sumenep"
            },
            {
                "street" : "Jalan Pahlawan no 200",
                "city" : "Surabaya"
            } 
        ]
    }

    
 ```