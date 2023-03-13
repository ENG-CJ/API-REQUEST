# API-REQUEST
API Waa fikrad aad muhiim u ah inaad wax ka taqaano, marar badanna ubahanysud luuqad walbo isticmaal,
kaba soo qaad waxaad sameeysay webapp ama application waxaa ubaahatay inaad kusoo darto qeeyb wether-ka laga aqrisan karo so waxaa ubahanysaa inaad xogta cimilada
kasoo aqrisato website-kale, meesha waxaa imaanaya marka (API)

# IN API (HTTP ENDPOINTS)
Waxaa jira methods la isticmaalo markii aad API REQUEST aad sameenaysid waxaana loo Yaqanaa (HTTP enpoints ama Methods),
Waxayna Kala Yihiin<br>
1. GET - oo aah inaad wax soo aqriso by default waa (GET method)
2. POST - oo ah (CREATE) inaad wax kusoo darto xogtii hori jirtay
3. PUT | PATCH - oo ah (UPDATE) inaad wax ka badasho xog horay ujirtay
4. DELETE - oo ah inaad wax ka tuurto xog horay ujirtay <br>
intaas iyo kabadan waaye lkn afartaas ayaa zaa'id loo isticmaalaa

# For practicals
Waxaa Jira website bixiya API FREEE AH without tookens wax KEY kaagama bahna, so website lik-giisa waaa kan<br>
✔ [https://www.randomuser.me]

# RANDOMUSER.ME API
Request [{
 url : "https://www.randomuser.me",
 results : 5
}];

Response - 
{
  "results": [
    {
      "gender": "female",
      "name": {
        "title": "Miss",
        "first": "Jennie",
        "last": "Nichols"
      },
      "location": {
        "street": {
          "number": 8929,
          "name": "Valwood Pkwy",
        },
        "city": "Billings",
        "state": "Michigan",
        "country": "United States",
        "postcode": "63104",
        "coordinates": {
          "latitude": "-69.8246",
          "longitude": "134.8719"
        },
        "timezone": {
          "offset": "+9:30",
          "description": "Adelaide, Darwin"
        }
      },
      "email": "jennie.nichols@example.com",
      "login": {
        "uuid": "7a0eed16-9430-4d68-901f-c0d4c1c3bf00",
        "username": "yellowpeacock117",
        "password": "addison",
        "salt": "sld1yGtd",
        "md5": "ab54ac4c0be9480ae8fa5e9e2a5196a3",
        "sha1": "edcf2ce613cbdea349133c52dc2f3b83168dc51b",
        "sha256": "48df5229235ada28389b91e60a935e4f9b73eb4bdb855ef9258a1751f10bdc5d"
      },
      "dob": {
        "date": "1992-03-08T15:13:16.688Z",
        "age": 30
      },
      "registered": {
        "date": "2007-07-09T05:51:59.390Z",
        "age": 14
      },
      "phone": "(272) 790-0888",
      "cell": "(489) 330-2385",
      "id": {
        "name": "SSN",
        "value": "405-88-3636"
      },
      "picture": {
        "large": "https://randomuser.me/api/portraits/men/75.jpg",
        "medium": "https://randomuser.me/api/portraits/med/men/75.jpg",
        "thumbnail": "https://randomuser.me/api/portraits/thumb/men/75.jpg"
      },
      "nat": "US"
    }
  ],
  "info": {
    "seed": "56d27f4a53bd5441",
    "results": 1,
    "page": 1,
    "version": "1.4"
  }
}


# More Documentation
https://randomuser.me/documentation


