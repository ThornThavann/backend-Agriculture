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
{
    "data": [
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
                "updatedAt": "2024-05-30T00:53:42.120Z",
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
                    "data": null
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
            "id": 15,
            "attributes": {
                "ProductID": 10,
                "Name": "Rambutan",
                "Price": 3.5,
                "Quantity": 90,
                "Origanic": true,
                "OriginProvince": "Siem Reap",
                "OwerID": 5,
                "createdAt": "2024-05-23T06:58:32.664Z",
                "updatedAt": "2024-05-29T06:34:53.798Z",
                "publishedAt": "2024-05-23T06:58:35.496Z",
                "images": {
                    "data": [
                        {
                            "id": 62,
                            "attributes": {
                                "name": "samavphoto_2024-05-29_13-32-47.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 532,
                                "height": 480,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_samavphoto_2024_05_29_13_32_47_b9b98582a0.jpg",
                                        "hash": "small_samavphoto_2024_05_29_13_32_47_b9b98582a0",
                                        "mime": "image/jpeg",
                                        "name": "small_samavphoto_2024-05-29_13-32-47.jpg",
                                        "path": null,
                                        "size": 55.49,
                                        "width": 500,
                                        "height": 451,
                                        "sizeInBytes": 55492
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_samavphoto_2024_05_29_13_32_47_b9b98582a0.jpg",
                                        "hash": "thumbnail_samavphoto_2024_05_29_13_32_47_b9b98582a0",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_samavphoto_2024-05-29_13-32-47.jpg",
                                        "path": null,
                                        "size": 8.58,
                                        "width": 173,
                                        "height": 156,
                                        "sizeInBytes": 8578
                                    }
                                },
                                "hash": "samavphoto_2024_05_29_13_32_47_b9b98582a0",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 60.13,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/samavphoto_2024_05_29_13_32_47_b9b98582a0.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T06:34:46.777Z",
                                "updatedAt": "2024-05-29T06:34:46.777Z"
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
                    "data": null
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
                "updatedAt": "2024-05-29T06:39:45.371Z",
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
                    "data": null
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
            "id": 8,
            "attributes": {
                "ProductID": 5,
                "Name": "\tWatermelon",
                "Price": 4,
                "Quantity": 80,
                "Origanic": true,
                "OriginProvince": "\tBattambang",
                "OwerID": 3,
                "createdAt": "2024-05-23T06:50:05.422Z",
                "updatedAt": "2024-05-29T06:48:11.457Z",
                "publishedAt": "2024-05-23T06:50:08.519Z",
                "images": {
                    "data": [
                        {
                            "id": 65,
                            "attributes": {
                                "name": "watermelon3f7495feb2f0329e8ca3e6f83e09703d.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_watermelon3f7495feb2f0329e8ca3e6f83e09703d_fcfcb7fc98.jpg",
                                        "hash": "small_watermelon3f7495feb2f0329e8ca3e6f83e09703d_fcfcb7fc98",
                                        "mime": "image/jpeg",
                                        "name": "small_watermelon3f7495feb2f0329e8ca3e6f83e09703d.jpg",
                                        "path": null,
                                        "size": 58.9,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 58900
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_watermelon3f7495feb2f0329e8ca3e6f83e09703d_fcfcb7fc98.jpg",
                                        "hash": "thumbnail_watermelon3f7495feb2f0329e8ca3e6f83e09703d_fcfcb7fc98",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_watermelon3f7495feb2f0329e8ca3e6f83e09703d.jpg",
                                        "path": null,
                                        "size": 8.23,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 8229
                                    }
                                },
                                "hash": "watermelon3f7495feb2f0329e8ca3e6f83e09703d_fcfcb7fc98",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 71.53,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/watermelon3f7495feb2f0329e8ca3e6f83e09703d_fcfcb7fc98.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T06:48:05.153Z",
                                "updatedAt": "2024-05-29T06:48:05.153Z"
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
                    "data": null
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
                "updatedAt": "2024-05-29T07:00:01.036Z",
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
                    "data": null
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
                "updatedAt": "2024-05-29T07:14:36.504Z",
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
                    "data": null
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
                "updatedAt": "2024-05-29T07:16:53.864Z",
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
                    "data": null
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
                "updatedAt": "2024-05-29T07:22:55.518Z",
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
                    "data": null
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
            "id": 21,
            "attributes": {
                "ProductID": 15,
                "Name": "Spinach",
                "Price": 1.2,
                "Quantity": 150,
                "Origanic": false,
                "OriginProvince": "\tPursat",
                "OwerID": 8,
                "createdAt": "2024-05-23T07:06:19.895Z",
                "updatedAt": "2024-05-29T07:37:11.764Z",
                "publishedAt": "2024-05-23T07:06:23.130Z",
                "images": {
                    "data": [
                        {
                            "id": 77,
                            "attributes": {
                                "name": "spinach6bb402d2a1c12340dc15fb81d1630907.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 400,
                                "height": 400,
                                "formats": {
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_spinach6bb402d2a1c12340dc15fb81d1630907_f8931a225a.jpg",
                                        "hash": "thumbnail_spinach6bb402d2a1c12340dc15fb81d1630907_f8931a225a",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_spinach6bb402d2a1c12340dc15fb81d1630907.jpg",
                                        "path": null,
                                        "size": 8.41,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 8411
                                    }
                                },
                                "hash": "spinach6bb402d2a1c12340dc15fb81d1630907_f8931a225a",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 38.05,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/spinach6bb402d2a1c12340dc15fb81d1630907_f8931a225a.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T07:37:04.847Z",
                                "updatedAt": "2024-05-29T07:37:04.847Z"
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
                    "data": null
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
            "id": 26,
            "attributes": {
                "ProductID": 18,
                "Name": "\tPotato",
                "Price": 1.5,
                "Quantity": 180,
                "Origanic": true,
                "OriginProvince": "\tKampong Cham",
                "OwerID": 10,
                "createdAt": "2024-05-23T07:10:29.510Z",
                "updatedAt": "2024-05-29T07:55:34.270Z",
                "publishedAt": "2024-05-23T07:10:34.524Z",
                "images": {
                    "data": [
                        {
                            "id": 80,
                            "attributes": {
                                "name": "Potato8.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_Potato8_521e00740c.jpg",
                                        "hash": "small_Potato8_521e00740c",
                                        "mime": "image/jpeg",
                                        "name": "small_Potato8.jpg",
                                        "path": null,
                                        "size": 50.81,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 50813
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_Potato8_521e00740c.jpg",
                                        "hash": "thumbnail_Potato8_521e00740c",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_Potato8.jpg",
                                        "path": null,
                                        "size": 7.03,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 7033
                                    }
                                },
                                "hash": "Potato8_521e00740c",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 61.25,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/Potato8_521e00740c.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-29T07:55:30.079Z",
                                "updatedAt": "2024-05-29T07:55:30.079Z"
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
                    "data": null
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
                "updatedAt": "2024-05-29T08:42:55.181Z",
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
                    "data": null
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
            "id": 18,
            "attributes": {
                "ProductID": 12,
                "Name": "Tomato",
                "Price": 1,
                "Quantity": 300,
                "Origanic": true,
                "OriginProvince": "Kandal",
                "OwerID": 7,
                "createdAt": "2024-05-23T07:02:08.012Z",
                "updatedAt": "2024-05-30T00:34:21.222Z",
                "publishedAt": "2024-05-23T07:02:10.849Z",
                "images": {
                    "data": [
                        {
                            "id": 85,
                            "attributes": {
                                "name": "tomato.jpg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 564,
                                "height": 564,
                                "formats": {
                                    "small": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_tomato_f6a7918abb.jpg",
                                        "hash": "small_tomato_f6a7918abb",
                                        "mime": "image/jpeg",
                                        "name": "small_tomato.jpg",
                                        "path": null,
                                        "size": 42.36,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 42359
                                    },
                                    "thumbnail": {
                                        "ext": ".jpg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_tomato_f6a7918abb.jpg",
                                        "hash": "thumbnail_tomato_f6a7918abb",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_tomato.jpg",
                                        "path": null,
                                        "size": 7.3,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 7300
                                    }
                                },
                                "hash": "tomato_f6a7918abb",
                                "ext": ".jpg",
                                "mime": "image/jpeg",
                                "size": 51.56,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/tomato_f6a7918abb.jpg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-30T00:34:14.949Z",
                                "updatedAt": "2024-05-30T00:34:14.949Z"
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
                    "data": null
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
                "updatedAt": "2024-05-30T01:08:33.715Z",
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
                    "data": null
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
                "updatedAt": "2024-05-30T01:10:57.127Z",
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
                    "data": null
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
            "id": 10,
            "attributes": {
                "ProductID": 31,
                "Name": "Postassium Nitrate",
                "Price": 12,
                "Quantity": 80,
                "Origanic": false,
                "OriginProvince": "Kampot",
                "OwerID": 11,
                "createdAt": "2024-05-23T06:51:35.471Z",
                "updatedAt": "2024-05-28T03:27:35.938Z",
                "publishedAt": "2024-05-23T06:51:42.835Z",
                "images": {
                    "data": [
                        {
                            "id": 10,
                            "attributes": {
                                "name": "[100-110-040900] Potassium nitrate acidic 13-0-46 Kemapco.jpeg",
                                "alternativeText": null,
                                "caption": null,
                                "width": 1024,
                                "height": 1024,
                                "formats": {
                                    "large": {
                                        "ext": ".jpeg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/large_100_110_040900_Potassium_nitrate_acidic_13_0_46_Kemapco_779456e112.jpeg",
                                        "hash": "large_100_110_040900_Potassium_nitrate_acidic_13_0_46_Kemapco_779456e112",
                                        "mime": "image/jpeg",
                                        "name": "large_[100-110-040900] Potassium nitrate acidic 13-0-46 Kemapco.jpeg",
                                        "path": null,
                                        "size": 83.9,
                                        "width": 1000,
                                        "height": 1000,
                                        "sizeInBytes": 83901
                                    },
                                    "small": {
                                        "ext": ".jpeg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_100_110_040900_Potassium_nitrate_acidic_13_0_46_Kemapco_779456e112.jpeg",
                                        "hash": "small_100_110_040900_Potassium_nitrate_acidic_13_0_46_Kemapco_779456e112",
                                        "mime": "image/jpeg",
                                        "name": "small_[100-110-040900] Potassium nitrate acidic 13-0-46 Kemapco.jpeg",
                                        "path": null,
                                        "size": 29.74,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 29744
                                    },
                                    "medium": {
                                        "ext": ".jpeg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/medium_100_110_040900_Potassium_nitrate_acidic_13_0_46_Kemapco_779456e112.jpeg",
                                        "hash": "medium_100_110_040900_Potassium_nitrate_acidic_13_0_46_Kemapco_779456e112",
                                        "mime": "image/jpeg",
                                        "name": "medium_[100-110-040900] Potassium nitrate acidic 13-0-46 Kemapco.jpeg",
                                        "path": null,
                                        "size": 54.43,
                                        "width": 750,
                                        "height": 750,
                                        "sizeInBytes": 54431
                                    },
                                    "thumbnail": {
                                        "ext": ".jpeg",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_100_110_040900_Potassium_nitrate_acidic_13_0_46_Kemapco_779456e112.jpeg",
                                        "hash": "thumbnail_100_110_040900_Potassium_nitrate_acidic_13_0_46_Kemapco_779456e112",
                                        "mime": "image/jpeg",
                                        "name": "thumbnail_[100-110-040900] Potassium nitrate acidic 13-0-46 Kemapco.jpeg",
                                        "path": null,
                                        "size": 5.12,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 5117
                                    }
                                },
                                "hash": "100_110_040900_Potassium_nitrate_acidic_13_0_46_Kemapco_779456e112",
                                "ext": ".jpeg",
                                "mime": "image/jpeg",
                                "size": 86.19,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/100_110_040900_Potassium_nitrate_acidic_13_0_46_Kemapco_779456e112.jpeg",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-23T06:51:22.639Z",
                                "updatedAt": "2024-05-23T06:51:22.639Z"
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
                    "data": null
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
                "updatedAt": "2024-05-30T01:29:44.561Z",
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
                    "data": null
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
                "updatedAt": "2024-05-30T01:30:49.545Z",
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
                    "data": null
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
            "id": 6,
            "attributes": {
                "ProductID": 32,
                "Name": "Phosphate",
                "Price": 9,
                "Quantity": 150,
                "Origanic": false,
                "OriginProvince": "Kandal",
                "OwerID": 11,
                "createdAt": "2024-05-23T06:48:13.299Z",
                "updatedAt": "2024-05-28T03:28:27.658Z",
                "publishedAt": "2024-05-23T06:48:17.414Z",
                "images": {
                    "data": [
                        {
                            "id": 7,
                            "attributes": {
                                "name": "calcium-phosphate-25-kg.webp",
                                "alternativeText": null,
                                "caption": null,
                                "width": 1800,
                                "height": 1800,
                                "formats": {
                                    "large": {
                                        "ext": ".webp",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/large_calcium_phosphate_25_kg_efaceab4a5.webp",
                                        "hash": "large_calcium_phosphate_25_kg_efaceab4a5",
                                        "mime": "image/webp",
                                        "name": "large_calcium-phosphate-25-kg.webp",
                                        "path": null,
                                        "size": 63.08,
                                        "width": 1000,
                                        "height": 1000,
                                        "sizeInBytes": 63084
                                    },
                                    "small": {
                                        "ext": ".webp",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/small_calcium_phosphate_25_kg_efaceab4a5.webp",
                                        "hash": "small_calcium_phosphate_25_kg_efaceab4a5",
                                        "mime": "image/webp",
                                        "name": "small_calcium-phosphate-25-kg.webp",
                                        "path": null,
                                        "size": 23.43,
                                        "width": 500,
                                        "height": 500,
                                        "sizeInBytes": 23428
                                    },
                                    "medium": {
                                        "ext": ".webp",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/medium_calcium_phosphate_25_kg_efaceab4a5.webp",
                                        "hash": "medium_calcium_phosphate_25_kg_efaceab4a5",
                                        "mime": "image/webp",
                                        "name": "medium_calcium-phosphate-25-kg.webp",
                                        "path": null,
                                        "size": 42.75,
                                        "width": 750,
                                        "height": 750,
                                        "sizeInBytes": 42754
                                    },
                                    "thumbnail": {
                                        "ext": ".webp",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_calcium_phosphate_25_kg_efaceab4a5.webp",
                                        "hash": "thumbnail_calcium_phosphate_25_kg_efaceab4a5",
                                        "mime": "image/webp",
                                        "name": "thumbnail_calcium-phosphate-25-kg.webp",
                                        "path": null,
                                        "size": 3.92,
                                        "width": 156,
                                        "height": 156,
                                        "sizeInBytes": 3916
                                    }
                                },
                                "hash": "calcium_phosphate_25_kg_efaceab4a5",
                                "ext": ".webp",
                                "mime": "image/webp",
                                "size": 145.87,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/calcium_phosphate_25_kg_efaceab4a5.webp",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-23T06:48:04.230Z",
                                "updatedAt": "2024-05-23T06:48:04.230Z"
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
                    "data": null
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
            "id": 5,
            "attributes": {
                "ProductID": 3,
                "Name": "Pineapple",
                "Price": 3,
                "Quantity": 150,
                "Origanic": true,
                "OriginProvince": "\tKampot",
                "OwerID": 2,
                "createdAt": "2024-05-23T06:46:00.668Z",
                "updatedAt": "2024-05-31T06:21:32.887Z",
                "publishedAt": "2024-05-23T06:46:03.833Z",
                "images": {
                    "data": [
                        {
                            "id": 98,
                            "attributes": {
                                "name": "99778d5e13e91111ccde658b8d18179d.png",
                                "alternativeText": null,
                                "caption": null,
                                "width": 475,
                                "height": 437,
                                "formats": {
                                    "thumbnail": {
                                        "ext": ".png",
                                        "url": "https://colorful-ball-607353d204.media.strapiapp.com/thumbnail_99778d5e13e91111ccde658b8d18179d_3e7e563ed9.png",
                                        "hash": "thumbnail_99778d5e13e91111ccde658b8d18179d_3e7e563ed9",
                                        "mime": "image/webp",
                                        "name": "thumbnail_99778d5e13e91111ccde658b8d18179d.png",
                                        "path": null,
                                        "size": 11.23,
                                        "width": 170,
                                        "height": 156,
                                        "sizeInBytes": 11234
                                    }
                                },
                                "hash": "99778d5e13e91111ccde658b8d18179d_3e7e563ed9",
                                "ext": ".png",
                                "mime": "image/webp",
                                "size": 56.35,
                                "url": "https://colorful-ball-607353d204.media.strapiapp.com/99778d5e13e91111ccde658b8d18179d_3e7e563ed9.png",
                                "previewUrl": null,
                                "provider": "strapi-provider-upload-strapi-cloud",
                                "provider_metadata": null,
                                "createdAt": "2024-05-31T06:21:19.617Z",
                                "updatedAt": "2024-05-31T06:21:19.617Z"
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
                    "data": null
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

### `Get Product page `

EX: [Learn more]( https://colorful-ball-607353d204.strapiapp.com/api/products?filters[categoryID][CategoryID][$eq]=${categoryId}&pagination[pageSize]=5&populate=*)

```
GET /api/restaurants?filters[CategoryID][Products][Category][$eq]=5
```

```

```
### `AgroMarket 6 Product by Category`


Ex: [Learn more](https://colorful-ball-607353d204.strapiapp.com/api/products?filters[categoryID][CategoryID][$eq]=${categoryId}&pagination[pageSize]=6&populate=*)


```
GET /api/restaurants?filters[CategoryID][Products][Category][$eq]=6
```
```

```



## 📚 Learn more




