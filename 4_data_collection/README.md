# Sheltr🐾 
#### Final Project Submission for INFO-C451: System Implementation (Spring 2024)
by Matthew Fante

# Data Collection:

Here are sample objects for each datatype that's written to FireBase: 

### meet_and_greet_requests

<pre>
{
    "createDate": "2024-04-30T11:36:07.378488",
    "lastUpdatedBy": "7BmR9m728OchFEVySpVDJycdTQm1",
    "meetDate": "2024-04-30T15:00:00.000",
    "meetTime": "15:00",
    "notes": "",
    "petId": "My9vp4EEw24FtH2mAFb9",
    "requestId": "sErMtHHX2HwOz0TIEboZ",
    "requesterId": "VYg6KFRzDaWr1daOEfcMRAolIap1",
    "status": "approved",
    "updateDate": "2024-04-30T11:36:37.866817",
}
</pre>

### pets

<pre>
{ 
    "age":
        "months": 4,
        "years": 10,
    "available": true,
    "breed": "Monitor Lizard",
    "createdByUserId": "UNCWfcE3FaaNpitLmoIY0Mp46Wp2",
    "description": "",
    "documentId": "4YPDazINN4Gu5io7FVYU",
    "imageUrls": [
        "https://as1.ftcdn.net/v2/jpg/03/08/89/52/1000_F_308895203_IytB5oRXdWJw2e94AG4psiAMq7OtlwBt.jpg",
        "https://as2.ftcdn.net/v2/jpg/04/82/76/41/1000_F_482764131_0CGGyarCDLZGQAHzvEFpfBzeSqbFLgd1.jpg"
    ]
    "name": "Sobek",
    "sex": "Female" 
    "size": "Large"
    "species": "Reptile"
}
</pre>

### upgrade_requests

<pre>
{
    "requestId" : "5aEW94A8tBG34SzFu1oH"
    "requestTime" : "April 29, 2024 at 2:23:00 PM UTC-4"
    "status" : "rejected"
    "uid" : "VYg6KFRzDaWr1daOEfcMRAolIap1"
}
</pre>

### user_profiles

<pre>
{
  "address": "555 Main Street",
  "bio": "We are so excited to connect you with your new best friend!",
  "city": "Louisville",
  "displayName": "Happy Pets Shelter",
  "email": "shelter@test.com",
  "favoritePets": null,
  "hoursOfOperation": "8-5pm Monday-Friday",
  "phoneNumber": "5551234567",
  "profilePictureUrl": "https://as2.ftcdn.net/v2/jpg/02/33/99/59/1000_F_233995940_808BmDwI25yp0FGWrxMVnKTNvMcivzLu.jpg",
  "state": "KY",
  "userId": "UNCWfcE3FaaNpitLmoIY0Mp46Wp2",
  "userType": "shelter",
  "website": "www.happypetsshelter.com",
  "zipCode": "40219"
}
</pre>