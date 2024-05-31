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

Ex: [Learn more](https://colorful-ball-607353d204.strapiapp.com/api/products?populate=*)

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
                "images": {
                    "data": [
                        {
                            "id": 95,
                            "attributes": {
                                "name": "Kubota M954.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 563,
                                "height": 544,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_Kubota_M954_1e735228e9.jpg",
                                        "hash": "small_Kubota_M954_1e735228e9",
                                        "mime": "image/jpeg",
                                        "name": "small_Kubota M954.jpg",
                                        "path": null,
                                        "size": 27.42,
                                        "width": 500,
                                        "height": 483,
                                        "sizeInBytes": 27420
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_Kubota_M954_1e735228e9.jpg",
                                        "hash": "thumbnail_Kubota_M954_1e735228e9",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_Kubota M954.jpg",
                                        "path": null,
                                        "size": 4.58,
                                        "width": 161,
                                        "height": 156,
                                        "sizeInBytes": 4579
                                    }
                                },
                                "hash": "Kubota_M954_1e735228e9",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 33.15,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/Kubota_M954_1e735228e9.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-30T01:29:40.718Z",
                                "updatedAt": "2024-05-30T01:29:40.718Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 3,
                        "attributes": {
                            "CategoryID": 3,
                            "Name": "Tractor",
                            "createdAt": "2024-05-23T03:37:51.625Z",
                            "updatedAt": "2024-05-23T03:37:54.899Z",
                            "publishedAt": "2024-05-23T03:37:54.894Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 7,
                        "attributes": {
                            "CustomerID": 7,
                            "Name": "Samantha Martinez",
                            "Type": "buyer",
                            "Phone": "11234567",
                            "Email": "samantha.martinez@example.com",
                            "Telegram": "11234567",
                            "createdAt": "2024-05-23T06:40:54.381Z",
                            "updatedAt": "2024-05-23T06:40:58.173Z",
                            "publishedAt": "2024-05-23T06:40:58.167Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 23,
            "attributes": {
                "ProductID": 16,
                "Name": "Lettuce",
                "Price": 1.5,
                "Quantity": 100,
                "Origanic": true,
                "OriginProvince": "\tPrey Veng",
                "OwerID": 9,
                "createdAt": "2024-05-23T07:07:42.210Z",
                "updatedAt": "2024-05-31T07:28:07.398Z",
                "publishedAt": "2024-05-23T07:07:45.008Z",
                "images": {
                    "data": [
                        {
                            "id": 63,
                            "attributes": {
                                "name": "saladlete79e8339ac3547127abec2f1166cc05de.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_saladlete79e8339ac3547127abec2f1166cc05de_def0128b43.jpg",
                                        "hash": "small_saladlete79e8339ac3547127abec2f1166cc05de_def0128b43",
                                        "mime": "image/jpeg",
                                        "name": "small_saladlete79e8339ac3547127abec2f1166cc05de.jpg",
                                        "path": null,
                                        "size": 68.97,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 68969
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_saladlete79e8339ac3547127abec2f1166cc05de_def0128b43.jpg",
                                        "hash": "thumbnail_saladlete79e8339ac3547127abec2f1166cc05de_def0128b43",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_saladlete79e8339ac3547127abec2f1166cc05de.jpg",
                                        "path": null,
                                        "size": 8.64,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 8636
                                    }
                                },
                                "hash": "saladlete79e8339ac3547127abec2f1166cc05de_def0128b43",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 86.53,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/saladlete79e8339ac3547127abec2f1166cc05de_def0128b43.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T06:39:04.192Z",
                                "updatedAt": "2024-05-29T06:39:04.192Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 2,
                        "attributes": {
                            "CategoryID": 2,
                            "Name": "Vegetable",
                            "createdAt": "2024-05-23T03:37:31.373Z",
                            "updatedAt": "2024-05-23T03:37:34.712Z",
                            "publishedAt": "2024-05-23T03:37:34.706Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 4,
                        "attributes": {
                            "CustomerID": 4,
                            "Name": "Michael Davis",
                            "Type": "buyer",
                            "Phone": "18901234",
                            "Email": "michael.davis@example.com",
                            "Telegram": "18901234",
                            "createdAt": "2024-05-23T06:34:29.684Z",
                            "updatedAt": "2024-05-23T06:34:32.896Z",
                            "publishedAt": "2024-05-23T06:34:32.854Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 2,
            "attributes": {
                "ProductID": 1,
                "Name": "\tMango",
                "Price": 2.5,
                "Quantity": 100,
                "Origanic": true,
                "OriginProvince": "Kampong Speu",
                "OwerID": 1,
                "createdAt": "2024-05-23T06:40:58.578Z",
                "updatedAt": "2024-05-31T07:29:11.137Z",
                "publishedAt": "2024-05-23T06:41:11.303Z",
                "images": {
                    "data": [
                        {
                            "id": 96,
                            "attributes": {
                                "name": "mango1.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 480,
                                "height": 479,
                                "formats": {
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_mango1_15e5f4694d.jpg",
                                        "hash": "thumbnail_mango1_15e5f4694d",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_mango1.jpg",
                                        "path": null,
                                        "size": 5.71,
                                        "width": 157,
                                        "height": 156,
                                        "sizeInBytes": 5708
                                    }
                                },
                                "hash": "mango1_15e5f4694d",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 41.49,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/mango1_15e5f4694d.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-30T01:30:45.433Z",
                                "updatedAt": "2024-05-30T01:30:45.433Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 1,
                        "attributes": {
                            "CategoryID": 1,
                            "Name": "Fruit",
                            "createdAt": "2024-05-23T03:36:44.434Z",
                            "updatedAt": "2024-05-23T03:36:47.991Z",
                            "publishedAt": "2024-05-23T03:36:47.986Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 10,
                        "attributes": {
                            "CustomerID": 10,
                            "Name": "Matthew Anderson",
                            "Type": "seller",
                            "Phone": "19210987",
                            "Email": "matthew.anderson@example.com",
                            "Telegram": "19210987",
                            "createdAt": "2024-05-23T06:45:43.789Z",
                            "updatedAt": "2024-05-23T06:45:46.495Z",
                            "publishedAt": "2024-05-23T06:45:46.454Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 28,
            "attributes": {
                "ProductID": 26,
                "Name": "Massey Ferguson",
                "Price": 1750000,
                "Quantity": 2,
                "Origanic": false,
                "OriginProvince": "Preas Sihanouk",
                "OwerID": 8,
                "createdAt": "2024-05-23T07:12:25.453Z",
                "updatedAt": "2024-05-31T07:29:25.019Z",
                "publishedAt": "2024-05-23T07:12:29.403Z",
                "images": {
                    "data": [
                        {
                            "id": 72,
                            "attributes": {
                                "name": "massey2c98b1c2fe6d3f0146cce4b0d9ae69e4.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_massey2c98b1c2fe6d3f0146cce4b0d9ae69e4_550890de05.jpg",
                                        "hash": "small_massey2c98b1c2fe6d3f0146cce4b0d9ae69e4_550890de05",
                                        "mime": "image/jpeg",
                                        "name": "small_massey2c98b1c2fe6d3f0146cce4b0d9ae69e4.jpg",
                                        "path": null,
                                        "size": 31.2,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 31196
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_massey2c98b1c2fe6d3f0146cce4b0d9ae69e4_550890de05.jpg",
                                        "hash": "thumbnail_massey2c98b1c2fe6d3f0146cce4b0d9ae69e4_550890de05",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_massey2c98b1c2fe6d3f0146cce4b0d9ae69e4.jpg",
                                        "path": null,
                                        "size": 5.33,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 5329
                                    }
                                },
                                "hash": "massey2c98b1c2fe6d3f0146cce4b0d9ae69e4_550890de05",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 37.46,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/massey2c98b1c2fe6d3f0146cce4b0d9ae69e4_550890de05.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T07:14:26.533Z",
                                "updatedAt": "2024-05-29T07:14:26.533Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 3,
                        "attributes": {
                            "CategoryID": 3,
                            "Name": "Tractor",
                            "createdAt": "2024-05-23T03:37:51.625Z",
                            "updatedAt": "2024-05-23T03:37:54.899Z",
                            "publishedAt": "2024-05-23T03:37:54.894Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 9,
                        "attributes": {
                            "CustomerID": 9,
                            "Name": "Jessica Garcia",
                            "Type": "seller",
                            "Phone": "17876543",
                            "Email": "jessica.garcia@example.com",
                            "Telegram": "17876543",
                            "createdAt": "2024-05-23T06:44:05.639Z",
                            "updatedAt": "2024-05-23T06:44:08.795Z",
                            "publishedAt": "2024-05-23T06:44:08.748Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 30,
            "attributes": {
                "ProductID": 25,
                "Name": "New Holland T6",
                "Price": 1850000,
                "Quantity": 4,
                "Origanic": false,
                "OriginProvince": "Kampong Cham",
                "OwerID": 8,
                "createdAt": "2024-05-23T07:14:23.144Z",
                "updatedAt": "2024-05-31T07:29:44.486Z",
                "publishedAt": "2024-05-23T07:14:27.398Z",
                "images": {
                    "data": [
                        {
                            "id": 76,
                            "attributes": {
                                "name": "New Holland T68d9fbcc87c4a283fd9ae117bf38e7ec1.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 500,
                                "height": 500,
                                "formats": {
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_New_Holland_T68d9fbcc87c4a283fd9ae117bf38e7ec1_d973f1a170.jpg",
                                        "hash": "thumbnail_New_Holland_T68d9fbcc87c4a283fd9ae117bf38e7ec1_d973f1a170",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_New Holland T68d9fbcc87c4a283fd9ae117bf38e7ec1.jpg",
                                        "path": null,
                                        "size": 6.06,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 6059
                                    }
                                },
                                "hash": "New_Holland_T68d9fbcc87c4a283fd9ae117bf38e7ec1_d973f1a170",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 36.34,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/New_Holland_T68d9fbcc87c4a283fd9ae117bf38e7ec1_d973f1a170.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T07:22:50.752Z",
                                "updatedAt": "2024-05-29T07:22:50.752Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 3,
                        "attributes": {
                            "CategoryID": 3,
                            "Name": "Tractor",
                            "createdAt": "2024-05-23T03:37:51.625Z",
                            "updatedAt": "2024-05-23T03:37:54.899Z",
                            "publishedAt": "2024-05-23T03:37:54.894Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 5,
                        "attributes": {
                            "CustomerID": 5,
                            "Name": "Jennifer Wilson",
                            "Type": "buyer",
                            "Phone": "15678901",
                            "Email": "jennifer.wilson@example.com",
                            "Telegram": "15678901",
                            "createdAt": "2024-05-23T06:36:41.020Z",
                            "updatedAt": "2024-05-23T06:36:43.726Z",
                            "publishedAt": "2024-05-23T06:36:43.720Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 16,
            "attributes": {
                "ProductID": 29,
                "Name": "NPK Fertilizer",
                "Price": 10,
                "Quantity": 100,
                "Origanic": false,
                "OriginProvince": "Phnom Penh",
                "OwerID": 10,
                "createdAt": "2024-05-23T07:00:04.425Z",
                "updatedAt": "2024-05-31T07:31:13.612Z",
                "publishedAt": "2024-05-23T07:00:11.568Z",
                "images": {
                    "data": [
                        {
                            "id": 91,
                            "attributes": {
                                "name": "NPK Fertilize.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_NPK_Fertilize_badce56077.jpg",
                                        "hash": "small_NPK_Fertilize_badce56077",
                                        "mime": "image/jpeg",
                                        "name": "small_NPK Fertilize.jpg",
                                        "path": null,
                                        "size": 28.41,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 28405
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_NPK_Fertilize_badce56077.jpg",
                                        "hash": "thumbnail_NPK_Fertilize_badce56077",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_NPK Fertilize.jpg",
                                        "path": null,
                                        "size": 4.77,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 4768
                                    }
                                },
                                "hash": "NPK_Fertilize_badce56077",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 33.33,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/NPK_Fertilize_badce56077.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-30T01:10:51.497Z",
                                "updatedAt": "2024-05-30T01:10:51.497Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 4,
                        "attributes": {
                            "CategoryID": 4,
                            "Name": "Fertilizer",
                            "createdAt": "2024-05-23T03:38:41.046Z",
                            "updatedAt": "2024-05-23T03:38:44.834Z",
                            "publishedAt": "2024-05-23T03:38:44.829Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 5,
                        "attributes": {
                            "CustomerID": 5,
                            "Name": "Jennifer Wilson",
                            "Type": "buyer",
                            "Phone": "15678901",
                            "Email": "jennifer.wilson@example.com",
                            "Telegram": "15678901",
                            "createdAt": "2024-05-23T06:36:41.020Z",
                            "updatedAt": "2024-05-23T06:36:43.726Z",
                            "publishedAt": "2024-05-23T06:36:43.720Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 27,
            "attributes": {
                "ProductID": 19,
                "Name": "Onion",
                "Price": 1.2,
                "Quantity": 170,
                "Origanic": true,
                "OriginProvince": "\tBattambang",
                "OwerID": 10,
                "createdAt": "2024-05-23T07:12:09.125Z",
                "updatedAt": "2024-05-31T07:31:33.419Z",
                "publishedAt": "2024-05-23T07:12:12.952Z",
                "images": {
                    "data": [
                        {
                            "id": 82,
                            "attributes": {
                                "name": "onion1.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_onion1_78002829a4.jpg",
                                        "hash": "small_onion1_78002829a4",
                                        "mime": "image/jpeg",
                                        "name": "small_onion1.jpg",
                                        "path": null,
                                        "size": 56.69,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 56694
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_onion1_78002829a4.jpg",
                                        "hash": "thumbnail_onion1_78002829a4",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_onion1.jpg",
                                        "path": null,
                                        "size": 8.29,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 8289
                                    }
                                },
                                "hash": "onion1_78002829a4",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 69.26,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/onion1_78002829a4.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T08:42:45.724Z",
                                "updatedAt": "2024-05-29T08:42:45.724Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 2,
                        "attributes": {
                            "CategoryID": 2,
                            "Name": "Vegetable",
                            "createdAt": "2024-05-23T03:37:31.373Z",
                            "updatedAt": "2024-05-23T03:37:34.712Z",
                            "publishedAt": "2024-05-23T03:37:34.706Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 3,
                        "attributes": {
                            "CustomerID": 3,
                            "Name": "Emily Brown",
                            "Type": "buyer",
                            "Phone": "17890123",
                            "Email": "emily.brown@example.com",
                            "Telegram": "17890123",
                            "createdAt": "2024-05-23T06:33:28.493Z",
                            "updatedAt": "2024-05-23T06:33:32.123Z",
                            "publishedAt": "2024-05-23T06:33:32.119Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
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
                "publishedAt": "2024-05-23T06:51:22.914Z",
                "images": {
                    "data": [
                        {
                            "id": 68,
                            "attributes": {
                                "name": "oraphoto_2024-05-29_13-59-14.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 736,
                                "height": 693,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_oraphoto_2024_05_29_13_59_14_25909a8b77.jpg",
                                        "hash": "small_oraphoto_2024_05_29_13_59_14_25909a8b77",
                                        "mime": "image/jpeg",
                                        "name": "small_oraphoto_2024-05-29_13-59-14.jpg",
                                        "path": null,
                                        "size": 48.79,
                                        "width": 500,
                                        "height": 471,
                                        "sizeInBytes": 48787
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_oraphoto_2024_05_29_13_59_14_25909a8b77.jpg",
                                        "hash": "thumbnail_oraphoto_2024_05_29_13_59_14_25909a8b77",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_oraphoto_2024-05-29_13-59-14.jpg",
                                        "path": null,
                                        "size": 7.58,
                                        "width": 166,
                                        "height": 156,
                                        "sizeInBytes": 7577
                                    }
                                },
                                "hash": "oraphoto_2024_05_29_13_59_14_25909a8b77",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 91.36,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/oraphoto_2024_05_29_13_59_14_25909a8b77.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T06:59:52.474Z",
                                "updatedAt": "2024-05-29T06:59:52.474Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 1,
                        "attributes": {
                            "CategoryID": 1,
                            "Name": "Fruit",
                            "createdAt": "2024-05-23T03:36:44.434Z",
                            "updatedAt": "2024-05-23T03:36:47.991Z",
                            "publishedAt": "2024-05-23T03:36:47.986Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 2,
                        "attributes": {
                            "CustomerID": 2,
                            "Name": "David Smith",
                            "Type": "buyer",
                            "Phone": "16789012",
                            "Email": "david.smith@example.com",
                            "Telegram": "16789012",
                            "createdAt": "2024-05-23T06:32:07.622Z",
                            "updatedAt": "2024-05-23T06:32:11.026Z",
                            "publishedAt": "2024-05-23T06:32:11.018Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 7,
            "attributes": {
                "ProductID": 4,
                "Name": "\tPapaya",
                "Price": 2,
                "Quantity": 120,
                "Origanic": false,
                "OriginProvince": "\tPreah Sihanouk",
                "OwerID": 2,
                "createdAt": "2024-05-23T06:48:38.871Z",
                "updatedAt": "2024-05-31T07:32:22.717Z",
                "publishedAt": "2024-05-23T06:48:47.717Z",
                "images": {
                    "data": [
                        {
                            "id": 88,
                            "attributes": {
                                "name": "papaya.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_papaya_934ddef798.jpg",
                                        "hash": "small_papaya_934ddef798",
                                        "mime": "image/jpeg",
                                        "name": "small_papaya.jpg",
                                        "path": null,
                                        "size": 48.29,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 48294
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_papaya_934ddef798.jpg",
                                        "hash": "thumbnail_papaya_934ddef798",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_papaya.jpg",
                                        "path": null,
                                        "size": 8.1,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 8104
                                    }
                                },
                                "hash": "papaya_934ddef798",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 58.12,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/papaya_934ddef798.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-30T00:53:37.898Z",
                                "updatedAt": "2024-05-30T00:53:37.898Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 1,
                        "attributes": {
                            "CategoryID": 1,
                            "Name": "Fruit",
                            "createdAt": "2024-05-23T03:36:44.434Z",
                            "updatedAt": "2024-05-23T03:36:47.991Z",
                            "publishedAt": "2024-05-23T03:36:47.986Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 8,
                        "attributes": {
                            "CustomerID": 8,
                            "Name": "Daniel Thompson",
                            "Type": "seller",
                            "Phone": "16543210",
                            "Email": "daniel.thompson@example.com",
                            "Telegram": "16543210",
                            "createdAt": "2024-05-23T06:42:50.346Z",
                            "updatedAt": "2024-05-23T06:42:54.132Z",
                            "publishedAt": "2024-05-23T06:42:54.128Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 4,
            "attributes": {
                "ProductID": 33,
                "Name": "Ammonium Sulfate",
                "Price": 11,
                "Quantity": 90,
                "Origanic": false,
                "OriginProvince": "Kampong Thom",
                "OwerID": 12,
                "createdAt": "2024-05-23T06:44:35.529Z",
                "updatedAt": "2024-05-31T06:38:34.931Z",
                "publishedAt": "2024-05-23T06:44:40.816Z",
                "images": {
                    "data": [
                        {
                            "id": 4,
                            "attributes": {
                                "name": "Ammonisul-1.png",
                                "alternativeText": null,
                                "caption": null,
                                "width": 800,
                                "height": 800,
                                "formats": {
                                    "small": {
                                        "ext": ".png",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_Ammonisul_1_291b79a9f9.png",
                                        "hash": "small_Ammonisul_1_291b79a9f9",
                                        "mime": "image/png",
                                        "name": "small_Ammonisul-1.png",
                                        "path": null,
                                        "size": 170.06,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 170057
                                    },
                                    "medium": {
                                        "ext": ".png",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/medium_Ammonisul_1_291b79a9f9.png",
                                        "hash": "medium_Ammonisul_1_291b79a9f9",
                                        "mime": "image/png",
                                        "name": "medium_Ammonisul-1.png",
                                        "path": null,
                                        "size": 336.07,
                                        "width": 750,
                                        "height": 750,
                                        "sizeInBytes": 336065
                                    },
                                    "thumbnail": {
                                        "ext": ".png",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_Ammonisul_1_291b79a9f9.png",
                                        "hash": "thumbnail_Ammonisul_1_291b79a9f9",
                                        "mime": "image/png",
                                        "name": "thumbnail_Ammonisul-1.png",
                                        "path": null,
                                        "size": 24.43,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 24430
                                    }
                                },
                                "hash": "Ammonisul_1_291b79a9f9",
                                "ext": ".png",
                                "mime": "image/png",
                                "size": 98.52,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/Ammonisul_1_291b79a9f9.png",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-23T06:44:23.776Z",
                                "updatedAt": "2024-05-23T06:44:23.776Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 4,
                        "attributes": {
                            "CategoryID": 4,
                            "Name": "Fertilizer",
                            "createdAt": "2024-05-23T03:38:41.046Z",
                            "updatedAt": "2024-05-23T03:38:44.834Z",
                            "publishedAt": "2024-05-23T03:38:44.829Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 3,
                        "attributes": {
                            "CustomerID": 3,
                            "Name": "Emily Brown",
                            "Type": "buyer",
                            "Phone": "17890123",
                            "Email": "emily.brown@example.com",
                            "Telegram": "17890123",
                            "createdAt": "2024-05-23T06:33:28.493Z",
                            "updatedAt": "2024-05-23T06:33:32.123Z",
                            "publishedAt": "2024-05-23T06:33:32.119Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 11,
            "attributes": {
                "ProductID": 7,
                "Name": "\tApple",
                "Price": 2,
                "Quantity": 150,
                "Origanic": true,
                "OriginProvince": "Kampong Thom",
                "OwerID": 4,
                "createdAt": "2024-05-23T06:52:50.496Z",
                "updatedAt": "2024-05-31T07:22:40.029Z",
                "publishedAt": "2024-05-23T06:52:52.892Z",
                "images": {
                    "data": [
                        {
                            "id": 66,
                            "attributes": {
                                "name": "apple78553ff9077bdc3356b39b44d7d0262d.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_apple78553ff9077bdc3356b39b44d7d0262d_16942365d8.jpg",
                                        "hash": "small_apple78553ff9077bdc3356b39b44d7d0262d_16942365d8",
                                        "mime": "image/jpeg",
                                        "name": "small_apple78553ff9077bdc3356b39b44d7d0262d.jpg",
                                        "path": null,
                                        "size": 46.7,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 46696
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_apple78553ff9077bdc3356b39b44d7d0262d_16942365d8.jpg",
                                        "hash": "thumbnail_apple78553ff9077bdc3356b39b44d7d0262d_16942365d8",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_apple78553ff9077bdc3356b39b44d7d0262d.jpg",
                                        "path": null,
                                        "size": 7.13,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 7132
                                    }
                                },
                                "hash": "apple78553ff9077bdc3356b39b44d7d0262d_16942365d8",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 58,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/apple78553ff9077bdc3356b39b44d7d0262d_16942365d8.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T06:53:09.308Z",
                                "updatedAt": "2024-05-29T06:53:09.308Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 1,
                        "attributes": {
                            "CategoryID": 1,
                            "Name": "Fruit",
                            "createdAt": "2024-05-23T03:36:44.434Z",
                            "updatedAt": "2024-05-23T03:36:47.991Z",
                            "publishedAt": "2024-05-23T03:36:47.986Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 2,
                        "attributes": {
                            "CustomerID": 2,
                            "Name": "David Smith",
                            "Type": "buyer",
                            "Phone": "16789012",
                            "Email": "david.smith@example.com",
                            "Telegram": "16789012",
                            "createdAt": "2024-05-23T06:32:07.622Z",
                            "updatedAt": "2024-05-23T06:32:11.026Z",
                            "publishedAt": "2024-05-23T06:32:11.018Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 3,
            "attributes": {
                "ProductID": 2,
                "Name": "Banana",
                "Price": 1.5,
                "Quantity": 200,
                "Origanic": false,
                "OriginProvince": "\tKampong Cham",
                "OwerID": 1,
                "createdAt": "2024-05-23T06:43:20.826Z",
                "updatedAt": "2024-05-31T07:23:07.824Z",
                "publishedAt": "2024-05-23T06:43:25.500Z",
                "images": {
                    "data": [
                        {
                            "id": 94,
                            "attributes": {
                                "name": "banana.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 575,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_banana_98b3d11187.jpg",
                                        "hash": "small_banana_98b3d11187",
                                        "mime": "image/jpeg",
                                        "name": "small_banana.jpg",
                                        "path": null,
                                        "size": 37.13,
                                        "width": 490,
                                        "height": 500,
                                        "sizeInBytes": 37125
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_banana_98b3d11187.jpg",
                                        "hash": "thumbnail_banana_98b3d11187",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_banana.jpg",
                                        "path": null,
                                        "size": 7.5,
                                        "width": 153,
                                        "height": 156,
                                        "sizeInBytes": 7502
                                    }
                                },
                                "hash": "banana_98b3d11187",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 44.95,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/banana_98b3d11187.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-30T01:29:08.573Z",
                                "updatedAt": "2024-05-30T01:29:08.573Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 1,
                        "attributes": {
                            "CategoryID": 1,
                            "Name": "Fruit",
                            "createdAt": "2024-05-23T03:36:44.434Z",
                            "updatedAt": "2024-05-23T03:36:47.991Z",
                            "publishedAt": "2024-05-23T03:36:47.986Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 6,
                        "attributes": {
                            "CustomerID": 6,
                            "Name": "Christopher Taylor",
                            "Type": "buyer",
                            "Phone": "13456789",
                            "Email": "christopher.taylor@example.com",
                            "Telegram": "13456789",
                            "createdAt": "2024-05-23T06:38:16.101Z",
                            "updatedAt": "2024-05-23T06:38:19.089Z",
                            "publishedAt": "2024-05-23T06:38:19.083Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 29,
            "attributes": {
                "ProductID": 20,
                "Name": "Bell Pepper",
                "Price": 2,
                "Quantity": 180,
                "Origanic": false,
                "OriginProvince": "\tSiem Reap",
                "OwerID": 11,
                "createdAt": "2024-05-23T07:13:35.302Z",
                "updatedAt": "2024-05-31T07:23:33.901Z",
                "publishedAt": "2024-05-23T07:13:38.855Z",
                "images": {
                    "data": [
                        {
                            "id": 83,
                            "attributes": {
                                "name": "paper.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 474,
                                "height": 474,
                                "formats": {
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_paper_f60c895339.jpg",
                                        "hash": "thumbnail_paper_f60c895339",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_paper.jpg",
                                        "path": null,
                                        "size": 6.46,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 6464
                                    }
                                },
                                "hash": "paper_f60c895339",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 31.12,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/paper_f60c895339.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T08:49:26.756Z",
                                "updatedAt": "2024-05-29T08:49:26.756Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 2,
                        "attributes": {
                            "CategoryID": 2,
                            "Name": "Vegetable",
                            "createdAt": "2024-05-23T03:37:31.373Z",
                            "updatedAt": "2024-05-23T03:37:34.712Z",
                            "publishedAt": "2024-05-23T03:37:34.706Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 6,
                        "attributes": {
                            "CustomerID": 6,
                            "Name": "Christopher Taylor",
                            "Type": "buyer",
                            "Phone": "13456789",
                            "Email": "christopher.taylor@example.com",
                            "Telegram": "13456789",
                            "createdAt": "2024-05-23T06:38:16.101Z",
                            "updatedAt": "2024-05-23T06:38:19.089Z",
                            "publishedAt": "2024-05-23T06:38:19.083Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 34,
            "attributes": {
                "ProductID": 21,
                "Name": "Broccoli",
                "Price": 1.75,
                "Quantity": 140,
                "Origanic": false,
                "OriginProvince": "Kampong Thom",
                "OwerID": 11,
                "createdAt": "2024-05-28T01:24:18.728Z",
                "updatedAt": "2024-05-31T07:23:51.489Z",
                "publishedAt": "2024-05-28T01:25:20.561Z",
                "images": {
                    "data": [
                        {
                            "id": 79,
                            "attributes": {
                                "name": "Broccoli.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 534,
                                "height": 534,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_Broccoli_d1f2b6ef81.jpg",
                                        "hash": "small_Broccoli_d1f2b6ef81",
                                        "mime": "image/jpeg",
                                        "name": "small_Broccoli.jpg",
                                        "path": null,
                                        "size": 82.6,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 82596
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_Broccoli_d1f2b6ef81.jpg",
                                        "hash": "thumbnail_Broccoli_d1f2b6ef81",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_Broccoli.jpg",
                                        "path": null,
                                        "size": 10.26,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 10257
                                    }
                                },
                                "hash": "Broccoli_d1f2b6ef81",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 92.18,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/Broccoli_d1f2b6ef81.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T07:44:44.930Z",
                                "updatedAt": "2024-05-29T07:44:44.930Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 2,
                        "attributes": {
                            "CategoryID": 2,
                            "Name": "Vegetable",
                            "createdAt": "2024-05-23T03:37:31.373Z",
                            "updatedAt": "2024-05-23T03:37:34.712Z",
                            "publishedAt": "2024-05-23T03:37:34.706Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 6,
                        "attributes": {
                            "CustomerID": 6,
                            "Name": "Christopher Taylor",
                            "Type": "buyer",
                            "Phone": "13456789",
                            "Email": "christopher.taylor@example.com",
                            "Telegram": "13456789",
                            "createdAt": "2024-05-23T06:38:16.101Z",
                            "updatedAt": "2024-05-23T06:38:19.089Z",
                            "publishedAt": "2024-05-23T06:38:19.083Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 1,
            "attributes": {
                "ProductID": 34,
                "Name": "Calcium Nitrate",
                "Price": 13,
                "Quantity": 70,
                "Origanic": false,
                "OriginProvince": "Takeo",
                "OwerID": 12,
                "createdAt": "2024-05-23T06:37:36.172Z",
                "updatedAt": "2024-05-31T07:24:11.083Z",
                "publishedAt": "2024-05-23T06:40:40.630Z",
                "images": {
                    "data": [
                        {
                            "id": 1,
                            "attributes": {
                                "name": "Calcium Nitrate 160_1345.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 1500,
                                "height": 1500,
                                "formats": {
                                    "large": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/large_Calcium_Nitrate_160_1345_d4f4481e3f.jpg",
                                        "hash": "large_Calcium_Nitrate_160_1345_d4f4481e3f",
                                        "mime": "image/jpeg",
                                        "name": "large_Calcium Nitrate 160_1345.jpg",
                                        "path": null,
                                        "size": 99.62,
                                        "width": 1000,
                                        "height": 1000,
                                        "sizeInBytes": 99623
                                    },
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_Calcium_Nitrate_160_1345_d4f4481e3f.jpg",
                                        "hash": "small_Calcium_Nitrate_160_1345_d4f4481e3f",
                                        "mime": "image/jpeg",
                                        "name": "small_Calcium Nitrate 160_1345.jpg",
                                        "path": null,
                                        "size": 34.35,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 34350
                                    },
                                    "medium": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/medium_Calcium_Nitrate_160_1345_d4f4481e3f.jpg",
                                        "hash": "medium_Calcium_Nitrate_160_1345_d4f4481e3f",
                                        "mime": "image/jpeg",
                                        "name": "medium_Calcium Nitrate 160_1345.jpg",
                                        "path": null,
                                        "size": 64.38,
                                        "width": 750,
                                        "height": 750,
                                        "sizeInBytes": 64377
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_Calcium_Nitrate_160_1345_d4f4481e3f.jpg",
                                        "hash": "thumbnail_Calcium_Nitrate_160_1345_d4f4481e3f",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_Calcium Nitrate 160_1345.jpg",
                                        "path": null,
                                        "size": 4.95,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 4952
                                    }
                                },
                                "hash": "Calcium_Nitrate_160_1345_d4f4481e3f",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 166.11,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/Calcium_Nitrate_160_1345_d4f4481e3f.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-23T06:40:02.884Z",
                                "updatedAt": "2024-05-23T06:40:02.884Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 4,
                        "attributes": {
                            "CategoryID": 4,
                            "Name": "Fertilizer",
                            "createdAt": "2024-05-23T03:38:41.046Z",
                            "updatedAt": "2024-05-23T03:38:44.834Z",
                            "publishedAt": "2024-05-23T03:38:44.829Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 2,
                        "attributes": {
                            "CustomerID": 2,
                            "Name": "David Smith",
                            "Type": "buyer",
                            "Phone": "16789012",
                            "Email": "david.smith@example.com",
                            "Telegram": "16789012",
                            "createdAt": "2024-05-23T06:32:07.622Z",
                            "updatedAt": "2024-05-23T06:32:11.026Z",
                            "publishedAt": "2024-05-23T06:32:11.018Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 20,
            "attributes": {
                "ProductID": 14,
                "Name": "\tCarrot",
                "Price": 0.8,
                "Quantity": 200,
                "Origanic": true,
                "OriginProvince": "Takeo",
                "OwerID": 8,
                "createdAt": "2024-05-23T07:04:58.213Z",
                "updatedAt": "2024-05-31T07:24:27.884Z",
                "publishedAt": "2024-05-23T07:05:01.655Z",
                "images": {
                    "data": [
                        {
                            "id": 42,
                            "attributes": {
                                "name": "carrot.webp",
                                "alternativeText": null,
                                "caption": null,
                                "width": 800,
                                "height": 800,
                                "formats": {
                                    "small": {
                                        "ext": ".webp",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_carrot_bb9fe0f2a6.webp",
                                        "hash": "small_carrot_bb9fe0f2a6",
                                        "mime": "image/webp",
                                        "name": "small_carrot.webp",
                                        "path": null,
                                        "size": 39.24,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 39244
                                    },
                                    "medium": {
                                        "ext": ".webp",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/medium_carrot_bb9fe0f2a6.webp",
                                        "hash": "medium_carrot_bb9fe0f2a6",
                                        "mime": "image/webp",
                                        "name": "medium_carrot.webp",
                                        "path": null,
                                        "size": 73.96,
                                        "width": 750,
                                        "height": 750,
                                        "sizeInBytes": 73964
                                    },
                                    "thumbnail": {
                                        "ext": ".webp",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_carrot_bb9fe0f2a6.webp",
                                        "hash": "thumbnail_carrot_bb9fe0f2a6",
                                        "mime": "image/webp",
                                        "name": "thumbnail_carrot.webp",
                                        "path": null,
                                        "size": 5.71,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 5712
                                    }
                                },
                                "hash": "carrot_bb9fe0f2a6",
                                "ext": ".webp",
                                "mime": "image/webp",
                                "size": 110.95,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/carrot_bb9fe0f2a6.webp",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-28T00:57:52.892Z",
                                "updatedAt": "2024-05-28T00:57:52.892Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 2,
                        "attributes": {
                            "CategoryID": 2,
                            "Name": "Vegetable",
                            "createdAt": "2024-05-23T03:37:31.373Z",
                            "updatedAt": "2024-05-23T03:37:34.712Z",
                            "publishedAt": "2024-05-23T03:37:34.706Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 8,
                        "attributes": {
                            "CustomerID": 8,
                            "Name": "Daniel Thompson",
                            "Type": "seller",
                            "Phone": "16543210",
                            "Email": "daniel.thompson@example.com",
                            "Telegram": "16543210",
                            "createdAt": "2024-05-23T06:42:50.346Z",
                            "updatedAt": "2024-05-23T06:42:54.132Z",
                            "publishedAt": "2024-05-23T06:42:54.128Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 25,
            "attributes": {
                "ProductID": 27,
                "Name": "Case IH Magnum",
                "Price": 2200000,
                "Quantity": 3,
                "Origanic": false,
                "OriginProvince": "Battambong",
                "OwerID": 9,
                "createdAt": "2024-05-23T07:09:51.312Z",
                "updatedAt": "2024-05-31T07:24:40.778Z",
                "publishedAt": "2024-05-23T07:09:54.746Z",
                "images": {
                    "data": [
                        {
                            "id": 74,
                            "attributes": {
                                "name": "Case IH Magnum8a1defd06f1eebedc82ce433ce93984c.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_Case_IH_Magnum8a1defd06f1eebedc82ce433ce93984c_8f317b9bde.jpg",
                                        "hash": "small_Case_IH_Magnum8a1defd06f1eebedc82ce433ce93984c_8f317b9bde",
                                        "mime": "image/jpeg",
                                        "name": "small_Case IH Magnum8a1defd06f1eebedc82ce433ce93984c.jpg",
                                        "path": null,
                                        "size": 29.8,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 29797
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_Case_IH_Magnum8a1defd06f1eebedc82ce433ce93984c_8f317b9bde.jpg",
                                        "hash": "thumbnail_Case_IH_Magnum8a1defd06f1eebedc82ce433ce93984c_8f317b9bde",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_Case IH Magnum8a1defd06f1eebedc82ce433ce93984c.jpg",
                                        "path": null,
                                        "size": 5.1,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 5104
                                    }
                                },
                                "hash": "Case_IH_Magnum8a1defd06f1eebedc82ce433ce93984c_8f317b9bde",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 35.8,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/Case_IH_Magnum8a1defd06f1eebedc82ce433ce93984c_8f317b9bde.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T07:18:47.661Z",
                                "updatedAt": "2024-05-29T07:18:47.661Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 3,
                        "attributes": {
                            "CategoryID": 3,
                            "Name": "Tractor",
                            "createdAt": "2024-05-23T03:37:51.625Z",
                            "updatedAt": "2024-05-23T03:37:54.899Z",
                            "publishedAt": "2024-05-23T03:37:54.894Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 9,
                        "attributes": {
                            "CustomerID": 9,
                            "Name": "Jessica Garcia",
                            "Type": "seller",
                            "Phone": "17876543",
                            "Email": "jessica.garcia@example.com",
                            "Telegram": "17876543",
                            "createdAt": "2024-05-23T06:44:05.639Z",
                            "updatedAt": "2024-05-23T06:44:08.795Z",
                            "publishedAt": "2024-05-23T06:44:08.748Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 33,
            "attributes": {
                "ProductID": 22,
                "Name": "Causliflower",
                "Price": 1.8,
                "Quantity": 130,
                "Origanic": true,
                "OriginProvince": "Kampong Spue",
                "OwerID": 12,
                "createdAt": "2024-05-23T07:23:52.500Z",
                "updatedAt": "2024-05-31T07:25:02.168Z",
                "publishedAt": "2024-05-23T07:23:56.716Z",
                "images": {
                    "data": [
                        {
                            "id": 78,
                            "attributes": {
                                "name": "Causliflower.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 380,
                                "height": 397,
                                "formats": {
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_Causliflower_a622e0d4fd.jpg",
                                        "hash": "thumbnail_Causliflower_a622e0d4fd",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_Causliflower.jpg",
                                        "path": null,
                                        "size": 6.03,
                                        "width": 149,
                                        "height": 156,
                                        "sizeInBytes": 6025
                                    }
                                },
                                "hash": "Causliflower_a622e0d4fd",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 27.11,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/Causliflower_a622e0d4fd.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T07:39:05.518Z",
                                "updatedAt": "2024-05-29T07:39:05.518Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 2,
                        "attributes": {
                            "CategoryID": 2,
                            "Name": "Vegetable",
                            "createdAt": "2024-05-23T03:37:31.373Z",
                            "updatedAt": "2024-05-23T03:37:34.712Z",
                            "publishedAt": "2024-05-23T03:37:34.706Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 1,
                        "attributes": {
                            "CustomerID": 1,
                            "Name": "Sarah Johnson",
                            "Type": "buyer",
                            "Phone": "12345678",
                            "Email": "sarah.johnson@example.com",
                            "Telegram": "12345678",
                            "createdAt": "2024-05-23T06:31:05.213Z",
                            "updatedAt": "2024-05-23T06:31:08.409Z",
                            "publishedAt": "2024-05-23T06:31:08.396Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 19,
            "attributes": {
                "ProductID": 13,
                "Name": "Cucumber",
                "Price": 0.75,
                "Quantity": 250,
                "Origanic": false,
                "OriginProvince": "\tKampong Thom",
                "OwerID": 7,
                "createdAt": "2024-05-23T07:03:51.896Z",
                "updatedAt": "2024-05-31T07:25:17.918Z",
                "publishedAt": "2024-05-23T07:03:54.691Z",
                "images": {
                    "data": [
                        {
                            "id": 61,
                            "attributes": {
                                "name": "cucumberced183ea9ff0481c86e115cf0bd611.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_cucumberced183ea9ff0481c86e115cf0bd611_84cfa4fb22.jpg",
                                        "hash": "small_cucumberced183ea9ff0481c86e115cf0bd611_84cfa4fb22",
                                        "mime": "image/jpeg",
                                        "name": "small_cucumberced183ea9ff0481c86e115cf0bd611.jpg",
                                        "path": null,
                                        "size": 52.3,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 52299
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_cucumberced183ea9ff0481c86e115cf0bd611_84cfa4fb22.jpg",
                                        "hash": "thumbnail_cucumberced183ea9ff0481c86e115cf0bd611_84cfa4fb22",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_cucumberced183ea9ff0481c86e115cf0bd611.jpg",
                                        "path": null,
                                        "size": 7.71,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 7706
                                    }
                                },
                                "hash": "cucumberced183ea9ff0481c86e115cf0bd611_84cfa4fb22",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 63.83,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/cucumberced183ea9ff0481c86e115cf0bd611_84cfa4fb22.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T06:27:47.927Z",
                                "updatedAt": "2024-05-29T06:27:47.927Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 2,
                        "attributes": {
                            "CategoryID": 2,
                            "Name": "Vegetable",
                            "createdAt": "2024-05-23T03:37:31.373Z",
                            "updatedAt": "2024-05-23T03:37:34.712Z",
                            "publishedAt": "2024-05-23T03:37:34.706Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 7,
                        "attributes": {
                            "CustomerID": 7,
                            "Name": "Samantha Martinez",
                            "Type": "buyer",
                            "Phone": "11234567",
                            "Email": "samantha.martinez@example.com",
                            "Telegram": "11234567",
                            "createdAt": "2024-05-23T06:40:54.381Z",
                            "updatedAt": "2024-05-23T06:40:58.173Z",
                            "publishedAt": "2024-05-23T06:40:58.167Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 12,
            "attributes": {
                "ProductID": 8,
                "Name": "Dragon Fruit",
                "Price": 3.5,
                "Quantity": 130,
                "Origanic": true,
                "OriginProvince": "\tKampong Speu",
                "OwerID": 4,
                "createdAt": "2024-05-23T06:54:21.817Z",
                "updatedAt": "2024-05-31T07:25:45.005Z",
                "publishedAt": "2024-05-23T06:54:24.963Z",
                "images": {
                    "data": [
                        {
                            "id": 87,
                            "attributes": {
                                "name": "dragon.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_dragon_ca8e672819.jpg",
                                        "hash": "small_dragon_ca8e672819",
                                        "mime": "image/jpeg",
                                        "name": "small_dragon.jpg",
                                        "path": null,
                                        "size": 57.11,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 57110
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_dragon_ca8e672819.jpg",
                                        "hash": "thumbnail_dragon_ca8e672819",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_dragon.jpg",
                                        "path": null,
                                        "size": 8.2,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 8202
                                    }
                                },
                                "hash": "dragon_ca8e672819",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 73.5,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/dragon_ca8e672819.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-30T00:48:25.609Z",
                                "updatedAt": "2024-05-30T00:48:25.609Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 1,
                        "attributes": {
                            "CategoryID": 1,
                            "Name": "Fruit",
                            "createdAt": "2024-05-23T03:36:44.434Z",
                            "updatedAt": "2024-05-23T03:36:47.991Z",
                            "publishedAt": "2024-05-23T03:36:47.986Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 4,
                        "attributes": {
                            "CustomerID": 4,
                            "Name": "Michael Davis",
                            "Type": "buyer",
                            "Phone": "18901234",
                            "Email": "michael.davis@example.com",
                            "Telegram": "18901234",
                            "createdAt": "2024-05-23T06:34:29.684Z",
                            "updatedAt": "2024-05-23T06:34:32.896Z",
                            "publishedAt": "2024-05-23T06:34:32.854Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 24,
            "attributes": {
                "ProductID": 17,
                "Name": "\tEggplant",
                "Price": 1.25,
                "Quantity": 120,
                "Origanic": false,
                "OriginProvince": "\tSvay Rieng",
                "OwerID": 9,
                "createdAt": "2024-05-23T07:09:07.157Z",
                "updatedAt": "2024-05-31T07:26:08.760Z",
                "publishedAt": "2024-05-23T07:09:19.234Z",
                "images": {
                    "data": [
                        {
                            "id": 97,
                            "attributes": {
                                "name": "a687698cbc0352126b6848fec37aecd0.png",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".png",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_a687698cbc0352126b6848fec37aecd0_da35e40a30.png",
                                        "hash": "small_a687698cbc0352126b6848fec37aecd0_da35e40a30",
                                        "mime": "image/png",
                                        "name": "small_a687698cbc0352126b6848fec37aecd0.png",
                                        "path": null,
                                        "size": 678.02,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 678018
                                    },
                                    "thumbnail": {
                                        "ext": ".png",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_a687698cbc0352126b6848fec37aecd0_da35e40a30.png",
                                        "hash": "thumbnail_a687698cbc0352126b6848fec37aecd0_da35e40a30",
                                        "mime": "image/png",
                                        "name": "thumbnail_a687698cbc0352126b6848fec37aecd0.png",
                                        "path": null,
                                        "size": 71.4,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 71404
                                    }
                                },
                                "hash": "a687698cbc0352126b6848fec37aecd0_da35e40a30",
                                "ext": ".png",
                                "mime": "image/png",
                                "size": 198.12,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/a687698cbc0352126b6848fec37aecd0_da35e40a30.png",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-30T01:53:11.179Z",
                                "updatedAt": "2024-05-30T01:53:11.179Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 2,
                        "attributes": {
                            "CategoryID": 2,
                            "Name": "Vegetable",
                            "createdAt": "2024-05-23T03:37:31.373Z",
                            "updatedAt": "2024-05-23T03:37:34.712Z",
                            "publishedAt": "2024-05-23T03:37:34.706Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 10,
                        "attributes": {
                            "CustomerID": 10,
                            "Name": "Matthew Anderson",
                            "Type": "seller",
                            "Phone": "19210987",
                            "Email": "matthew.anderson@example.com",
                            "Telegram": "19210987",
                            "createdAt": "2024-05-23T06:45:43.789Z",
                            "updatedAt": "2024-05-23T06:45:46.495Z",
                            "publishedAt": "2024-05-23T06:45:46.454Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 22,
            "attributes": {
                "ProductID": 28,
                "Name": "Fendt 1000 Vario",
                "Price": 2500000,
                "Quantity": 1,
                "Origanic": false,
                "OriginProvince": "Siem Reap",
                "OwerID": 9,
                "createdAt": "2024-05-23T07:07:06.959Z",
                "updatedAt": "2024-05-31T07:26:26.411Z",
                "publishedAt": "2024-05-23T07:07:12.031Z",
                "images": {
                    "data": [
                        {
                            "id": 75,
                            "attributes": {
                                "name": "Fendt 1000 Varioab645cce3ca40d90bcb6da165f6a2e8d.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 200,
                                "height": 200,
                                "formats": {
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_Fendt_1000_Varioab645cce3ca40d90bcb6da165f6a2e8d_2483c3bfd2.jpg",
                                        "hash": "thumbnail_Fendt_1000_Varioab645cce3ca40d90bcb6da165f6a2e8d_2483c3bfd2",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_Fendt 1000 Varioab645cce3ca40d90bcb6da165f6a2e8d.jpg",
                                        "path": null,
                                        "size": 5.88,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 5875
                                    }
                                },
                                "hash": "Fendt_1000_Varioab645cce3ca40d90bcb6da165f6a2e8d_2483c3bfd2",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 8.52,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/Fendt_1000_Varioab645cce3ca40d90bcb6da165f6a2e8d_2483c3bfd2.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T07:21:32.482Z",
                                "updatedAt": "2024-05-29T07:21:32.482Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 3,
                        "attributes": {
                            "CategoryID": 3,
                            "Name": "Tractor",
                            "createdAt": "2024-05-23T03:37:51.625Z",
                            "updatedAt": "2024-05-23T03:37:54.899Z",
                            "publishedAt": "2024-05-23T03:37:54.894Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 9,
                        "attributes": {
                            "CustomerID": 9,
                            "Name": "Jessica Garcia",
                            "Type": "seller",
                            "Phone": "17876543",
                            "Email": "jessica.garcia@example.com",
                            "Telegram": "17876543",
                            "createdAt": "2024-05-23T06:44:05.639Z",
                            "updatedAt": "2024-05-23T06:44:08.795Z",
                            "publishedAt": "2024-05-23T06:44:08.748Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 13,
            "attributes": {
                "ProductID": 9,
                "Name": "Guava",
                "Price": 2,
                "Quantity": 180,
                "Origanic": false,
                "OriginProvince": "\tBattambang",
                "OwerID": 5,
                "createdAt": "2024-05-23T06:56:08.097Z",
                "updatedAt": "2024-05-31T07:26:55.203Z",
                "publishedAt": "2024-05-23T06:56:11.219Z",
                "images": {
                    "data": [
                        {
                            "id": 84,
                            "attributes": {
                                "name": "Guava.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 634,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_Guava_43e4b0ec7b.jpg",
                                        "hash": "small_Guava_43e4b0ec7b",
                                        "mime": "image/jpeg",
                                        "name": "small_Guava.jpg",
                                        "path": null,
                                        "size": 51.88,
                                        "width": 445,
                                        "height": 500,
                                        "sizeInBytes": 51883
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_Guava_43e4b0ec7b.jpg",
                                        "hash": "thumbnail_Guava_43e4b0ec7b",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_Guava.jpg",
                                        "path": null,
                                        "size": 7.08,
                                        "width": 139,
                                        "height": 156,
                                        "sizeInBytes": 7079
                                    }
                                },
                                "hash": "Guava_43e4b0ec7b",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 77.74,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/Guava_43e4b0ec7b.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-30T00:23:42.008Z",
                                "updatedAt": "2024-05-30T00:23:42.008Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 1,
                        "attributes": {
                            "CategoryID": 1,
                            "Name": "Fruit",
                            "createdAt": "2024-05-23T03:36:44.434Z",
                            "updatedAt": "2024-05-23T03:36:47.991Z",
                            "publishedAt": "2024-05-23T03:36:47.986Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 5,
                        "attributes": {
                            "CustomerID": 5,
                            "Name": "Jennifer Wilson",
                            "Type": "buyer",
                            "Phone": "15678901",
                            "Email": "jennifer.wilson@example.com",
                            "Telegram": "15678901",
                            "createdAt": "2024-05-23T06:36:41.020Z",
                            "updatedAt": "2024-05-23T06:36:43.726Z",
                            "publishedAt": "2024-05-23T06:36:43.720Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 17,
            "attributes": {
                "ProductID": 11,
                "Name": "Jackfruit",
                "Price": 5,
                "Quantity": 100,
                "Origanic": true,
                "OriginProvince": "Preah Sihanouk",
                "OwerID": 6,
                "createdAt": "2024-05-23T07:00:54.578Z",
                "updatedAt": "2024-05-31T07:27:14.013Z",
                "publishedAt": "2024-05-23T07:00:57.773Z",
                "images": {
                    "data": [
                        {
                            "id": 90,
                            "attributes": {
                                "name": "jeckfruit.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_jeckfruit_854ed7bce4.jpg",
                                        "hash": "small_jeckfruit_854ed7bce4",
                                        "mime": "image/jpeg",
                                        "name": "small_jeckfruit.jpg",
                                        "path": null,
                                        "size": 37.38,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 37381
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_jeckfruit_854ed7bce4.jpg",
                                        "hash": "thumbnail_jeckfruit_854ed7bce4",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_jeckfruit.jpg",
                                        "path": null,
                                        "size": 6.33,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 6326
                                    }
                                },
                                "hash": "jeckfruit_854ed7bce4",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 45.17,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/jeckfruit_854ed7bce4.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-30T01:08:27.017Z",
                                "updatedAt": "2024-05-30T01:08:27.017Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 1,
                        "attributes": {
                            "CategoryID": 1,
                            "Name": "Fruit",
                            "createdAt": "2024-05-23T03:36:44.434Z",
                            "updatedAt": "2024-05-23T03:36:47.991Z",
                            "publishedAt": "2024-05-23T03:36:47.986Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 3,
                        "attributes": {
                            "CustomerID": 3,
                            "Name": "Emily Brown",
                            "Type": "buyer",
                            "Phone": "17890123",
                            "Email": "emily.brown@example.com",
                            "Telegram": "17890123",
                            "createdAt": "2024-05-23T06:33:28.493Z",
                            "updatedAt": "2024-05-23T06:33:32.123Z",
                            "publishedAt": "2024-05-23T06:33:32.119Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        },
        {
            "id": 32,
            "attributes": {
                "ProductID": 23,
                "Name": "Jonh Deere 5055E",
                "Price": 1500000,
                "Quantity": 5,
                "Origanic": false,
                "OriginProvince": "Phnom Penh",
                "OwerID": 7,
                "createdAt": "2024-05-23T07:19:45.450Z",
                "updatedAt": "2024-05-31T07:27:41.716Z",
                "publishedAt": "2024-05-23T07:21:03.614Z",
                "images": {
                    "data": [
                        {
                            "id": 73,
                            "attributes": {
                                "name": "Jonh Deere 5055Ec9df1520d0c06bee0066bf7b41f98211.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_Jonh_Deere_5055_Ec9df1520d0c06bee0066bf7b41f98211_f37a652180.jpg",
                                        "hash": "small_Jonh_Deere_5055_Ec9df1520d0c06bee0066bf7b41f98211_f37a652180",
                                        "mime": "image/jpeg",
                                        "name": "small_Jonh Deere 5055Ec9df1520d0c06bee0066bf7b41f98211.jpg",
                                        "path": null,
                                        "size": 27.49,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 27491
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_Jonh_Deere_5055_Ec9df1520d0c06bee0066bf7b41f98211_f37a652180.jpg",
                                        "hash": "thumbnail_Jonh_Deere_5055_Ec9df1520d0c06bee0066bf7b41f98211_f37a652180",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_Jonh Deere 5055Ec9df1520d0c06bee0066bf7b41f98211.jpg",
                                        "path": null,
                                        "size": 4.31,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 4314
                                    }
                                },
                                "hash": "Jonh_Deere_5055_Ec9df1520d0c06bee0066bf7b41f98211_f37a652180",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 33.69,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/Jonh_Deere_5055_Ec9df1520d0c06bee0066bf7b41f98211_f37a652180.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T07:16:31.431Z",
                                "updatedAt": "2024-05-29T07:16:31.431Z"
                            }
                        }
                    ]
                },
                "categoryID": {
                    "data": {
                        "id": 3,
                        "attributes": {
                            "CategoryID": 3,
                            "Name": "Tractor",
                            "createdAt": "2024-05-23T03:37:51.625Z",
                            "updatedAt": "2024-05-23T03:37:54.899Z",
                            "publishedAt": "2024-05-23T03:37:54.894Z"
                        }
                    }
                },
                "customer": {
                    "data": {
                        "id": 1,
                        "attributes": {
                            "CustomerID": 1,
                            "Name": "Sarah Johnson",
                            "Type": "buyer",
                            "Phone": "12345678",
                            "Email": "sarah.johnson@example.com",
                            "Telegram": "12345678",
                            "createdAt": "2024-05-23T06:31:05.213Z",
                            "updatedAt": "2024-05-23T06:31:08.409Z",
                            "publishedAt": "2024-05-23T06:31:08.396Z"
                        }
                    }
                },
                "strapi_stage": {
                    "data": null
                },
                "strapi_assignee": {
                    "data": null
                }
            }
        }
    ],
    "meta": {
        "pagination": {
            "page": 1,
            "pageSize": 25,
            "pageCount": 2,
            "total": 34
        }
    }
}
```


#### `Get Product page `

Ex: [Learn more](https://colorful-ball-607353d204.strapiapp.com/api/products?populate=*)


```
GET /api/restaurants?filters[CategoryID][Products][Category][$eq]=5
```






### `AgroMarket 6 Product by Category`

Ex: [Learn more](https://colorful-ball-607353d204.strapiapp.com/api/products?filters[categoryID][CategoryID][$eq]=${categoryId}&pagination[pageSize]=6&populate=*)

```
GET /api/restaurants?filters[CategoryID][Products][Category][$eq]=6
```




## 📚 Learn more




