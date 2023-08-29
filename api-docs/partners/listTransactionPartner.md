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
            "storeName": "15 Hoa Phuong branch",
            "program": {
                "id": "f69a89fe-4d3e-4f88-b3c2-aac5b2c5c1b7",
                "createdDate": "2023-05-25T04:37:47.239844",
                "updatedDate": "2023-08-01T04:46:25.636315",
                "createdBy": null,
                "updatedBy": null,
                "version": 38,
                "merchantId": "ca2c3a63-55d4-4853-948e-dceba0875f00",
                "name": "Free upsize",
                "code": "21493906CB41496E96B938C4730C6E94",
                "w3wTiers": [
                    4,
                    3
                ],
                "merchantTiers": [
                    "94bbcc25-a160-4b95-89e3-fec2dcd7a0a9"
                ],
                "programType": "TYPE03",
                "desc": "<p>[Vietnamese below] F Coffee &amp; Tea offers a special promotion for our valued customers:</p><p>\"Free upsize\" which increases the cup size without changing the price.</p><p><strong>Conditions of the promotion:</strong></p><p>Applicable products/services: the entire menu at F Coffee &amp; Tea.</p><p>This promotion is available for customers who own the Tier - Beginner of the Hunting Web3 Treasure campaign.</p><p>Promotion period: From June 10th to July 30th, 2023.</p><p>Promotion location: 15 Hoa Phuong Street, Ward 2, Phu Nhuan District, Ho Chi Minh City.</p><p><u>Note:</u> After the experience, you can receive a code from the cashier and participate in the Spin Wheel.</p><p><br></p><p>*****</p><p>Chương trình ưu đãi \"F Coffee &amp; Tea\" dành cho quý khách hàng:</p><p>\"Free upsize - Ly to không lo về giá\" tăng thể tích ly những giá không đổi.</p><p><strong>Điều kiện áp dụng:</strong></p><p>- Sản phẩm/ dịch vụ áp dụng chương trình: toàn bộ menu tại F Coffee &amp; Tea.</p><p>- Chương trình áp dụng cho khách hàng sở hữu Tier - Beginner của chiến dịch Hunting Web3 Treasure.</p><p>- Thời gian áp dụng: Từ 10/6 đến 15/7/2023.</p><p>- Địa điểm áp dụng: CN 15 Hoa Phượng, Phường 2, Quận Phú Nhuận, TP. Hồ Chí Minh</p>",
                "banner": "https://api-qa.nft-square.io/files/ecommerce/9f12ccc0ff9949eb9cff5629c7fd0b17F Coffee & Tea.jpeg",
                "status": 2,
                "startTime": "2023-06-09T17:05:00",
                "endTime": "2023-08-31T16:59:00",
                "title": "Free upsize for all types of beverages.",
                "type": 0
            }
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
            "storeName": "15 Hoa Phuong branch",
            "program": {
                "id": "f69a89fe-4d3e-4f88-b3c2-aac5b2c5c1b7",
                "createdDate": "2023-05-25T04:37:47.239844",
                "updatedDate": "2023-08-01T04:46:25.636315",
                "createdBy": null,
                "updatedBy": null,
                "version": 38,
                "merchantId": "ca2c3a63-55d4-4853-948e-dceba0875f00",
                "name": "Free upsize",
                "code": "21493906CB41496E96B938C4730C6E94",
                "w3wTiers": [
                    4,
                    3
                ],
                "merchantTiers": [
                    "94bbcc25-a160-4b95-89e3-fec2dcd7a0a9"
                ],
                "programType": "TYPE03",
                "desc": "<p>[Vietnamese below] F Coffee &amp; Tea offers a special promotion for our valued customers:</p><p>\"Free upsize\" which increases the cup size without changing the price.</p><p><strong>Conditions of the promotion:</strong></p><p>Applicable products/services: the entire menu at F Coffee &amp; Tea.</p><p>This promotion is available for customers who own the Tier - Beginner of the Hunting Web3 Treasure campaign.</p><p>Promotion period: From June 10th to July 30th, 2023.</p><p>Promotion location: 15 Hoa Phuong Street, Ward 2, Phu Nhuan District, Ho Chi Minh City.</p><p><u>Note:</u> After the experience, you can receive a code from the cashier and participate in the Spin Wheel.</p><p><br></p><p>*****</p><p>Chương trình ưu đãi \"F Coffee &amp; Tea\" dành cho quý khách hàng:</p><p>\"Free upsize - Ly to không lo về giá\" tăng thể tích ly những giá không đổi.</p><p><strong>Điều kiện áp dụng:</strong></p><p>- Sản phẩm/ dịch vụ áp dụng chương trình: toàn bộ menu tại F Coffee &amp; Tea.</p><p>- Chương trình áp dụng cho khách hàng sở hữu Tier - Beginner của chiến dịch Hunting Web3 Treasure.</p><p>- Thời gian áp dụng: Từ 10/6 đến 15/7/2023.</p><p>- Địa điểm áp dụng: CN 15 Hoa Phượng, Phường 2, Quận Phú Nhuận, TP. Hồ Chí Minh</p>",
                "banner": "https://api-qa.nft-square.io/files/ecommerce/9f12ccc0ff9949eb9cff5629c7fd0b17F Coffee & Tea.jpeg",
                "status": 2,
                "startTime": "2023-06-09T17:05:00",
                "endTime": "2023-08-31T16:59:00",
                "title": "Free upsize for all types of beverages.",
                "type": 0
            }
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
            "storeName": "15 Hoa Phuong branch",
            "program": {
                "id": "f69a89fe-4d3e-4f88-b3c2-aac5b2c5c1b7",
                "createdDate": "2023-05-25T04:37:47.239844",
                "updatedDate": "2023-08-01T04:46:25.636315",
                "createdBy": null,
                "updatedBy": null,
                "version": 38,
                "merchantId": "ca2c3a63-55d4-4853-948e-dceba0875f00",
                "name": "Free upsize",
                "code": "21493906CB41496E96B938C4730C6E94",
                "w3wTiers": [
                    4,
                    3
                ],
                "merchantTiers": [
                    "94bbcc25-a160-4b95-89e3-fec2dcd7a0a9"
                ],
                "programType": "TYPE03",
                "desc": "<p>[Vietnamese below] F Coffee &amp; Tea offers a special promotion for our valued customers:</p><p>\"Free upsize\" which increases the cup size without changing the price.</p><p><strong>Conditions of the promotion:</strong></p><p>Applicable products/services: the entire menu at F Coffee &amp; Tea.</p><p>This promotion is available for customers who own the Tier - Beginner of the Hunting Web3 Treasure campaign.</p><p>Promotion period: From June 10th to July 30th, 2023.</p><p>Promotion location: 15 Hoa Phuong Street, Ward 2, Phu Nhuan District, Ho Chi Minh City.</p><p><u>Note:</u> After the experience, you can receive a code from the cashier and participate in the Spin Wheel.</p><p><br></p><p>*****</p><p>Chương trình ưu đãi \"F Coffee &amp; Tea\" dành cho quý khách hàng:</p><p>\"Free upsize - Ly to không lo về giá\" tăng thể tích ly những giá không đổi.</p><p><strong>Điều kiện áp dụng:</strong></p><p>- Sản phẩm/ dịch vụ áp dụng chương trình: toàn bộ menu tại F Coffee &amp; Tea.</p><p>- Chương trình áp dụng cho khách hàng sở hữu Tier - Beginner của chiến dịch Hunting Web3 Treasure.</p><p>- Thời gian áp dụng: Từ 10/6 đến 15/7/2023.</p><p>- Địa điểm áp dụng: CN 15 Hoa Phượng, Phường 2, Quận Phú Nhuận, TP. Hồ Chí Minh</p>",
                "banner": "https://api-qa.nft-square.io/files/ecommerce/9f12ccc0ff9949eb9cff5629c7fd0b17F Coffee & Tea.jpeg",
                "status": 2,
                "startTime": "2023-06-09T17:05:00",
                "endTime": "2023-08-31T16:59:00",
                "title": "Free upsize for all types of beverages.",
                "type": 0
            }
        }
    ],
    "total": 3
}
```
## Notes

merchantName: Tên merchant áp dụng
programName: Tên chương trình khuyến mãi
storeName: Tên cửa hàng áp dụng
storeCode: Mã cửa hàng áp dụng
