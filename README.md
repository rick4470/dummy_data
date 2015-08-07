# Dummy Data
Data that I use through out my applications.

**Female Names**
* First Name: Isabella
* Last Name: Ramirez

* First Name: Megan 
* Last Name: Miller

* First Name: Kimberly
* Last Name: Thompson

**Male Names**
* First Name: Ferguson
* Last Name: Jones


## JSON Data
```javascript
{  
   "name":"Isabella",
   "userId":"bella32",
   "age":19,
   "friends":[  
      "a2ebc33adfjklajd3j33ka33ddf",
      "a2ebc333adcdjalkfjd3ka33ddf",
      "a2ebc333ajdsijadisd3ka33ddf",
      "a2ebcadsfijai3ee1dd3ka33ddf"
   ],
   "subscription":true
}
```

```javascript
{
  "id": 123,
  "firstName": "Isabella",
  "lastName": "Ramirez",
  "followers_id": [1,23,44,21,22,11,93],
  "favorited_posts": [
   {
      "id": 23,
      "date_published": 1448067813,
      "title": "The top 20 most interesting stories in the world"
   },
   {
      "id": 17,
      "date_published": 1446339813,
      "title": "The Best hiking trails in the US"
   }
  ]
}
```

```json
{
  "schema": "http://learnmean.com/schema#",
  "id": "http://learnmean.com",
  "type": "object",
  "properties": {
    "address": {
      "id": "http://learnmean.com/address",
      "type": "object",
      "properties": {
        "streetAddress": {
          "id": "http://learnmean.com/address",
          "type": "string"
        },
        "city": {
          "id": "http://learnmean.com/address/city",
          "type": "string"
        }
      },
      "required": [
        "streetAddress",
        "city"
      ]
    },
    "phoneNumber": {
      "id": "http://learnmean.com/phoneNumber",
      "type": "array",
      "items": {
        "id": "http://learnmean.com/phoneNumber/0",
        "type": "object",
        "properties": {
          "location": {
            "id": "http://learnmean.com/phoneNumber/0/location",
            "type": "string"
          },
          "code": {
            "id": "http://learnmean.com/phoneNumber/0/code",
            "type": "integer"
          }
        }
      }
    }
  },
  "required": [
    "address",
    "phoneNumber"
  ]
}
```
