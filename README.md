# rental-api

### detail product
- path `/products/:id`
- method `GET` 
- response 
```json
{
    "product_id": 1,
    "product_name": "supra",
    "product_price": 100000,
    "product_availability": true,
    "product_description": "product 1 description",
    "product_images": [
        "https://raw.githubusercontent.com/IzumiShaka-desu/gif_host/main/supra-removebg-preview%201%20(2).png",
        "https://raw.githubusercontent.com/IzumiShaka-desu/gif_host/main/supra-removebg-preview%201%20(2).png",
        "https://raw.githubusercontent.com/IzumiShaka-desu/gif_host/main/tenkuji_takeru.png",
    ],
    "location": "batam",
    "rating": 4.5,
    "brand": "Honda",
    "type": "classic",
    "author": {
        "author_id": 1,
        "author_name": "Izumi Shaka",
        "author_email": "shk@m.com",
        "author_photo": "https://raw.githubusercontent.com/IzumiShaka-desu/gif_host/main/tenkuji_takeru.png"
    },
    "reviews": [
        {
            "review_id": 1,
            "reviewer": {
                "reviewer_id": 1,
                "reviewer_name": "Izumi Shaka",
                "reviewer_photo": "https://raw.githubusercontent.com/IzumiShaka-desu/gif_host/main/tenkuji_takeru.png"
            },
            "review_content": "review content 1",
            "review_rating": 4.5,
            "review_date": "2021-08-01"
        },
        {
            "review_id": 2,
            "reviewer": {
                "reviewer_id": 2,
                "reviewer_name": "Izumi Shaka",
                "reviewer_photo": "https://raw.githubusercontent.com/IzumiShaka-desu/gif_host/main/tenkuji_takeru.png"
            },
            "review_content": "review content 2",
            "review_rating": 4.5,
            "review_date": "2021-08-01"
        }
    ]

}
```
