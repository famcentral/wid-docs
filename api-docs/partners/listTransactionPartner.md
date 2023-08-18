# Thông tin lịch sử giao dịch wid FAM3 

**URL** : `https://api.w3w.link/api/public/transactions/list-transaction-partner?pageSize=10&pageIndex=1&partnerCode=Onus`

**Method** : `GET`

**PARAM Type**


**partnerCode** : `type=[enum]`  [**required**] ( mã đối tác )
*  Onus = "Onus"

**pageIndex** : `type=[number]`  
**pageSize** : `type=[number]` 


**wid** : `type=[string]`  [**optional**] (filter theo mã wid gắn với những collection đối tác)




## Success Response


**Code** : `200 OK`

**Content example**

```json
{
    "data": [
        {
            "id": "7235e028-1a97-486f-bb53-4185128d71a2",
            "createdDate": "2023-08-18T06:56:23.470Z",
            "updatedDate": "2023-08-18T06:56:23.470Z",
            "createdBy": null,
            "updatedBy": null,
            "version": 1,
            "userId": "e1086381-4088-4084-879d-63a5d76dcdd4",
            "merchantId": "ca2c3a63-55d4-4853-948e-dceba0875f00",
            "programId": "f69a89fe-4d3e-4f88-b3c2-aac5b2c5c1b7",
            "storeId": "427c17ed-836c-43ee-8490-4db826e2eeb4",
            "storeCode": "15hoaphuong",
            "programCode": "21493906CB41496E96B938C4730C6E94",
            "apiKey": "14f301c7c4075475a552545913ef7dfc",
            "wid": "F36BA24AED93E0401E8CC660547EDE677B",
            "campaignId": null,
            "earningPoolId": null,
            "nftId": null,
            "nftAddress": "",
            "tokenId": null,
            "note": null,
            "merchantName": "F Coffee & Tea",
            "programName": "Free upsize",
            "storeName": "15 Hoa Phuong branch"
        },
        {
            "id": "a844fe71-3aaf-41d4-8ce3-a454a6005c04",
            "createdDate": "2023-08-18T06:54:26.276Z",
            "updatedDate": "2023-08-18T06:54:26.276Z",
            "createdBy": null,
            "updatedBy": null,
            "version": 1,
            "userId": "3888279c-c6ca-438b-83d6-29ffe92bc12d",
            "merchantId": "ca2c3a63-55d4-4853-948e-dceba0875f00",
            "programId": "f69a89fe-4d3e-4f88-b3c2-aac5b2c5c1b7",
            "storeId": "427c17ed-836c-43ee-8490-4db826e2eeb4",
            "storeCode": "15hoaphuong",
            "programCode": "21493906CB41496E96B938C4730C6E94",
            "apiKey": "14f301c7c4075475a552545913ef7dfc",
            "wid": "F35EE396C193FD43C39ACF2B5E69CC0B3D",
            "campaignId": null,
            "earningPoolId": null,
            "nftId": null,
            "nftAddress": "",
            "tokenId": null,
            "note": null,
            "merchantName": "F Coffee & Tea",
            "programName": "Free upsize",
            "storeName": "15 Hoa Phuong branch"
        },
        {
            "id": "526f1930-7250-42e6-b659-83cdc44e1801",
            "createdDate": "2023-08-18T06:51:42.340Z",
            "updatedDate": "2023-08-18T06:51:42.340Z",
            "createdBy": null,
            "updatedBy": null,
            "version": 1,
            "userId": "b063c2cf-0e43-4a89-afb3-bbabf1626865",
            "merchantId": "ca2c3a63-55d4-4853-948e-dceba0875f00",
            "programId": "f69a89fe-4d3e-4f88-b3c2-aac5b2c5c1b7",
            "storeId": "427c17ed-836c-43ee-8490-4db826e2eeb4",
            "storeCode": "15hoaphuong",
            "programCode": "21493906CB41496E96B938C4730C6E94",
            "apiKey": "14f301c7c4075475a552545913ef7dfc",
            "wid": "F35EE396C193FD43C39ACF2B5E69CC0B3D",
            "campaignId": null,
            "earningPoolId": null,
            "nftId": null,
            "nftAddress": "",
            "tokenId": null,
            "note": null,
            "merchantName": "F Coffee & Tea",
            "programName": "Free upsize",
            "storeName": "15 Hoa Phuong branch"
        }
    ],
    "total": 3
}
```
## Notes

Thông tin của những wid scan ở các cửa hàng

