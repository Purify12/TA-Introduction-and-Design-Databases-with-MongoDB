# TA-Introduction-and-Design-Databases-with-MongoDB
Soal 1
# Relasi One to One : seorang user dapat memiliki sebuah email serta sebuah nomor telepom

{
    "_id": "ObjectId('AAA')",
    "fullName": "SubjekA",
    "email": "subjeka@mail.com",
    "phoneNumber": 08123456789
}



Soal 2
# Relasi One to Many : seorang user dapat memiliki lebih dari 1 alamat

{
     "_id": "ObjectId('AAA')",
    "fullName": "John Doe",
    "phoneNumber": "Skilvul",
    "address": [{
               "_id": "ObjectId('ADR1')",
               "street": "Asaha street km.6",
               "postCode": 21151
          },
          {
               "_id": "ObjectId('ADR2')",
               "street": "Medeka street no.155",
               "postCode": 21152
          }]
}


Soal 3
# Relasi One to Many : tiap objek dapat memiliki banyak varian

{
     "_id": "ObjectId('AAA')",
     "productName": "Kaos Polos",
     "brandName": "SkilShirt",
     "varian": [{
         "_id": "ObjectId('AAA')",
         "varianName": "Kaos Polos Hitam",
         "color": "hitam",
         "quantity": 12,
         "price": "Rp 99.000"
     },{
          "_id": "ObjectId('BBB')",
         "varianName": "Kaos Polos Navy",
         "color": "navy",
         "quantity": 10,
         "price": "Rp 99.000"
     }]


Soal 4
# Relasi Many To Many : satu bioskop dapat memutar banyak film dan sebuah film dapat diputar di banyak bioskop

{
      "_id": "ObjectId('CINEMA1')",
      "cinemaName": "CGF",
      "location": "Pondok Indah Mall",
      "films": [{
           "_id": "ObjectId('FILM1')",
           "names": "Venom 2"
      },{
           "_id": "ObjectId('FILM2')",
           "names": "Spiderman No Way Home"
           }]
      },{
      "_id": "ObjectId('CINEMA2')",
      "cinemaName": "Cinema31",
      "location": "Mall Kelapa Gading",
      "films": [{
           "_id": "ObjectId('FILM1')",
           "names": "Venom 2"
      },{
           "_id": "ObjectId('FILM2')",
           "names": "Spiderman No Way Home"
      }]
}]
