# 🚀 AgroMarket API

This API allows you to manage and retrieve Agromarket website. Below are the available endpoints and their functionalities.

### `Endpoints`

Start your Strapi application with autoReload enabled. [Learn more]( )

```
npm run develop
# or
yarn develop
```

### `Get All Products AgroMarket`

Ex: How to get all products AgroMarket [Learn more](https://colorful-ball-607353d204.strapiapp.com/api/products?populate=*)

```
GET http://localhost:1337/api/products

```


```
{
    "data": [
        {
            "id": 31,
            "attributes": {
                "ProductID": 24,
                "Name": "Kubota M9540",
                "Price": 2000000,
                "Quantity": 3,
                "Origanic": false,
                "OriginProvince": "Kandal ",
                "OwerID": 7,
                "createdAt": "2024-05-23T07:15:22.610Z",
                "updatedAt": "2024-05-31T07:27:55.128Z",
                "publishedAt": "2024-05-23T07:18:13.226Z",
                "images": 
```



### `AgroMarket 6 Product by Category`

Ex: How to get AgroMarket 6 products by Category [Learn more](https://colorful-ball-607353d204.strapiapp.com/api/products?filters[categoryID][CategoryID][$eq]=${categoryId}&pagination[pageSize]=6&populate=*)



```
GET /api/restaurants?filters[CategoryID][Products][Category][$eq]=6
```


#### `Get Detail page `

Ex: How to get detail page [Learn more]([https://colorful-ball-607353d204.strapiapp.com/api/products?populate=*](https://colorful-ball-607353d204.strapiapp.com/api/products?filters[categoryID][CategoryID][$eq]=${categoryId}&pagination[pageSize]=5&populate=*))

```
GET /api/restaurants?filters[CategoryID][Products][Category][$eq]=5
```

```
{
    "data": {
        "id": 9,
        "attributes": {
            "ProductID": 6,
            "Name": "Orange",
            "Price": 2.5,
            "Quantity": 100,
            "Origanic": false,
            "OriginProvince": "\tSiem Reap",
            "OwerID": 3,
            "createdAt": "2024-05-23T06:51:18.844Z",
            "updatedAt": "2024-05-31T07:31:56.789Z",
            "publishedAt": "2024-05-23T06:51:22.914Z"
        }
    },
```


## 📚 Learn more




