# Epic Games Store API
Here you have some examples of the Epic Games Store API I've made.

## Latest Games
[https://api.egdata.app/](https://api.egdata.app/)
Sample response
```JSON
[
    {
        "title": "Mundaun",
        "id": "16ca7a26e9274d768771378e152b2d00",
        "namespace": "8f08ba8f76c940f89fa9d84658535a02",
        "effectiveDate": "2021-03-16T13:00:00.000Z",
        "currentPrice": "Free",
        "seller": "MWM Interactive",
        "productSlug": "https://www.epicgames.com/store/product/mundaun",
        "slug": "mundaun",
        "OfferImageWide": "https://cdn1.epicgames.com/8f08ba8f76c940f89fa9d84658535a02/offer/EGS_Mundaun_HiddenFields_S1-2560x1440-7b6555d4ab16483beda9d9efe347998f.jpg",
        "OfferImageTall": "https://cdn1.epicgames.com/8f08ba8f76c940f89fa9d84658535a02/offer/EGS_Mundaun_HiddenFields_S2-1200x1600-0e209f071069b203df62c2f80a3f624f.jpg",
        "Thumbnail": "https://cdn1.epicgames.com/8f08ba8f76c940f89fa9d84658535a02/offer/EGS_Mundaun_HiddenFields_S2-1200x1600-0e209f071069b203df62c2f80a3f624f.jpg",
        "CodeRedemption_340x440": "https://cdn1.epicgames.com/8f08ba8f76c940f89fa9d84658535a02/offer/EGS_Mundaun_HiddenFields_S2-1200x1600-0e209f071069b203df62c2f80a3f624f.jpg",
        "DieselStoreFrontWide": "https://cdn1.epicgames.com/8f08ba8f76c940f89fa9d84658535a02/offer/EGS_Mundaun_HiddenFields_S1-2560x1440-7b6555d4ab16483beda9d9efe347998f.jpg",
        "DieselStoreFrontTall": "https://cdn1.epicgames.com/8f08ba8f76c940f89fa9d84658535a02/offer/EGS_Mundaun_HiddenFields_S2-1200x1600-0e209f071069b203df62c2f80a3f624f.jpg",
        "originalPrice": "0",
        "discount": "0",
        "discountPercentage": "NAN"
    },
    ...
]
```

## Game Information
[https://api.egdata.app/game.php?title={GameSlug}](https://api.egdata.app/game.php?title=assassins-creed-valhalla)
```JSON
{
   "title":"Assassin's Creed Valhalla",
   "id":"d6b4c22c5360465aaf3d9a0161fad210",
   "_id":"e9787644a12a46beb66c102dfcbaea40",
   "namespace":"400347196e674de89c23cc2a7f2121db",
   "effectiveDate":"2020-04-30T15:00:00.000Z",
   "releaseDate":"2020-11-10T16:00:00.000Z",
   "available":"true",
   "OfferImageWide":"https://cdn1.epicgames.com/400347196e674de89c23cc2a7f2121db/offer/AC KINGDOM PREORDER_STANDARD EDITION_EPIC_Key_Art_Wide_3840x2160-3840x2160-485fe17203671386c71bde8110886c7d.jpg",
   "OfferImageTall":"https://cdn1.epicgames.com/400347196e674de89c23cc2a7f2121db/offer/AC KINGDOM PREORDER_STANDARD EDITION_EPIC_Key_Art_Portrait_640x854-640x854-288120c5573756cb988b6c1968cebd86.png",
   "DieselStoreFrontWide":"https://cdn1.epicgames.com/400347196e674de89c23cc2a7f2121db/offer/AC KINGDOM PREORDER_STANDARD EDITION_EPIC_Key_Art_Wide_3840x2160-3840x2160-485fe17203671386c71bde8110886c7d.jpg",
   "DieselStoreFrontTall":"https://cdn1.epicgames.com/400347196e674de89c23cc2a7f2121db/offer/AC KINGDOM PREORDER_STANDARD EDITION_EPIC_Key_Art_Portrait_640x854-640x854-288120c5573756cb988b6c1968cebd86.png",
   "Thumbnail":"https://cdn1.epicgames.com/400347196e674de89c23cc2a7f2121db/offer/AC KINGDOM PREORDER_STANDARD EDITION_EPIC_Key_Art_Portrait_640x854-640x854-288120c5573756cb988b6c1968cebd86.png",
   "currentPrice":"$59.99",
   "seller":"Ubisoft Entertainment",
   "productSlug":"https://www.epicgames.com/store/product/assassins-creed-valhalla",
   "originalPrice":"$59.99",
   "slug":"assassins-creed-valhalla",
   "website_url":"https://egs-website.vercel.app/product/assassins-creed-valhalla",
   "discount":"0",
   "discountPercentage":"0",
   "_title":"Gold Edition",
   "_description":"![Banner 3](https://cdn2.unrealengine.com/Diesel%2Fproductv2%2Fassassins-creed-valhalla%2Fhome%2FBanner-3%2FACK_EPIC_KeyFeature_Banner3_Feature1_1200x200_GB-1200x200-47a09c7a01db13d51566e42316c3b4aa8c8a4194.jpg)\n\n\nIncludes the game and Season Pass. \n\nBecome Eivor, a legendary Viking warrior on a quest for glory. Explore England's Dark Ages as you raid your enemies, grow your settlement, and build your political power...",
   "_logo":"https://cdn2.unrealengine.com/Diesel%2Fproductv2%2Fassassins-creed-valhalla%2Fgold-edition%2FAC-KINGDOM-PREORDER_GOLD-EDITION_EPIC_Game_Logo_Bright_1000x375-1000x375-06fa53f150f3634854ad5ca8a04ec27c59c06904.png",
   "galleryImages":[
      "https://cdn2.unrealengine.com/Diesel%2Fproductv2%2Fassassins-creed-valhalla%2FComparativeGrid%2FKINGDOMS_Announce_pack_COMPARATIVEGRID_200430_5pm_CET_GB-1920x1080-8e7919fb38bea252e7428a954259dc703bd073ba.jpg",
      "https://cdn2.unrealengine.com/Diesel%2Fproductv2%2Fassassins-creed-valhalla%2Fhome%2FACK_UCS16199_Screenshots_1920x1080_1_US-1920x1080-cdfecdd9071ae3f9f645fb9757232007507cb0f1.jpg",
      "https://cdn2.unrealengine.com/Diesel%2Fproductv2%2Fassassins-creed-valhalla%2Fhome%2FACK_UCS16199_Screenshots_1920x1080_2_US-1920x1080-1cace62592e6fa23d190742654ca6068cfcd9035.jpg",
      "https://cdn2.unrealengine.com/Diesel%2Fproductv2%2Fassassins-creed-valhalla%2Fhome%2FACK_UCS16199_Screenshots_1920x1080_3_US-1920x1080-5650a5e3b07a8a9bda4be5b7d9c2fe912ba78cb8.jpg",
      null
   ],
   "pages":[
      {
         "type":"offer",
         "slug":"gold-edition",
         "title":"Gold Edition",
         "image":"https://cdn2.unrealengine.com/Diesel%2Fproductv2%2Fassassins-creed-valhalla%2Fgold-edition%2FAC-KINGDOM-PREORDER_GOLD-EDITION_EPIC_Edition_Capsule_1920x1080-1920x1080-636d5ccf372c0addd369d43ba13741ba7ba456e5.jpg"
      },
      {
         "type":"offer",
         "slug":"ultimate-edition",
         "title":"Ultimate Edition",
         "image":"https://cdn2.unrealengine.com/Diesel%2Fproductv2%2Fassassins-creed-valhalla%2Fultimate-edition%2FAC-KINGDOM-PREORDER_ULTIMATE-EDITION_EPIC_Edition_Capsule_1920x1080-3840x2160-e095c5ba6c001fbebb215f7981d4d4b26adf8ee8.jpg"
      },
      {
         "type":"productHome",
         "slug":"home",
         "title":"Assassin's Creed Valhalla",
         "image":"https://cdn2.unrealengine.com/Diesel%2Fproductv2%2Fassassins-creed-valhalla%2Fhome%2FAC-KINGDOM-PREORDER_STANDARD-EDITION_EPIC_Key_Art_Wide_3840x2160-3840x2160-a1e051b288877ce621393421221b18d924d4f42a.png"
      },
      {
         "type":null
      }
   ]
}
```

## Game Price
[https://api.egdata.app/price.php?id={GameID}](https://api.egdata.app/price.php?id=32a37ec072474cf4a621d0ce28505f36)

```JSON
{
   "data":[
      {
         "date":"2021/02/25 16:26:16",
         "price":"39.99"
      },
      {
         "date":"2021/02/11 16:20:29",
         "price":"15.99"
      },
      {
         "date":"2021/01/07 16:18:17",
         "price":"39.99"
      },
      {
         "date":"2021/01/06 16:04:30",
         "price":"15.99"
      },
      {
         "date":"2020/12/03 16:18:31",
         "price":"39.99"
      },
      {
         "date":"2020/11/26 16:11:29",
         "price":"19.99"
      },
      {
         "date":"2020/09/24 15:21:55",
         "price":"39.99"
      },
      {
         "date":"2020/09/10 15:07:51",
         "price":"19.99"
      },
      {
         "date":"2020/08/06 15:13:28",
         "price":"39.99"
      },
      {
         "date":"2020/07/27 08:44:24",
         "price":"19.99"
      },
      {
         "date":"2020/07/04 16:20:01",
         "price":"39.99"
      }
   ]
}
```

## Free Games 
This API has a problem in the Epic Games official API, it shows previous free games too.
I recommend doing a conditional rendering with the value "endDate", games that have already been released have that value empty.

https://api.egdata.app/free-api.php
```JSON
[
   {
      "title":"Surviving Mars",
      "id":"39516a5b66d04b75b25a810e593b0a97",
      "namespace":"d759128018124dcabb1fbee9bb28e178",
      "effectiveDate":"2019-10-10T15:00:00.000Z",
      "currentPrice":"Free",
      "seller":"Paradox Interactive",
      "productSlug":"https://www.epicgames.com/store/product/surviving-mars",
      "DieselStoreFrontWide":"https://cdn1.epicgames.com/epic/offer/EGS_PDX_SurvivingMars_S1_Store Primary Promo (Landscape)-2560x1440-ef059cb5bccdef0947c508db16e4a14a.jpg",
      "DieselStoreFrontTall":"https://cdn1.epicgames.com/epic/offer/EGS_PDX_SurvivingMars_S2_Store Primary Promo (Portrait)-1280x1440-0eaf5ed168d8aadd7f63c808765e9021.jpg",
      "OfferImageTall":"https://cdn1.epicgames.com/epic/offer/EGS_PDX_SurvivingMars_S2_Store Primary Promo (Portrait)-1280x1440-0eaf5ed168d8aadd7f63c808765e9021.jpg",
      "Thumbnail":"https://cdn1.epicgames.com/d759128018124dcabb1fbee9bb28e178/offer/CodeRedemption_SurvivingMars-340x440-d3bf4bea36581cf967044ef712e67f9c.jpg",
      "CodeRedemption_340x440":"https://cdn1.epicgames.com/d759128018124dcabb1fbee9bb28e178/offer/CodeRedemption_SurvivingMars-340x440-d3bf4bea36581cf967044ef712e67f9c.jpg",
      "OfferImageWide":"https://cdn1.epicgames.com/d759128018124dcabb1fbee9bb28e178/offer/EGS_PDX_SurvivingMars_IC1_GameLogoRed-2560x844-a3b788af1422e4c4574c7c6be6464fbdb78d9251.png",
      "startDate":"2021-03-11T16:00:00.000Z",
      "endDate":"2021-03-18T15:00:00.000Z",
      "available":"true"
   },
   {
      "title":"The Fall",
      "id":"d7173e5531f549f1ba523319aceefc53",
      "namespace":"d16f231f238646e881bb0cd83e1d30c8",
      "effectiveDate":"2021-03-18T15:00:00.000Z",
      "currentPrice":"$9.99",
      "seller":"Over the Moon Games",
      "productSlug":"https://www.epicgames.com/store/product/the-fall",
      "OfferImageWide":"https://cdn1.epicgames.com/d16f231f238646e881bb0cd83e1d30c8/offer/EGS_TheFall_overTheMoon_S1-2560x1440-7b4817dcd4a35cf5826da7f0bbc744f4.jpg",
      "OfferImageTall":"https://cdn1.epicgames.com/d16f231f238646e881bb0cd83e1d30c8/offer/EGS_TheFall_overTheMoon_S2-1200x1600-368b3e85b4d26f63468593c1defca54f.jpg",
      "Thumbnail":"https://cdn1.epicgames.com/d16f231f238646e881bb0cd83e1d30c8/offer/EGS_TheFall_overTheMoon_S2-1200x1600-368b3e85b4d26f63468593c1defca54f.jpg",
      "CodeRedemption_340x440":"https://cdn1.epicgames.com/d16f231f238646e881bb0cd83e1d30c8/offer/EGS_TheFall_overTheMoon_S2-1200x1600-368b3e85b4d26f63468593c1defca54f.jpg",
      "DieselStoreFrontWide":"https://cdn1.epicgames.com/d16f231f238646e881bb0cd83e1d30c8/offer/EGS_TheFall_overTheMoon_S1-2560x1440-7b4817dcd4a35cf5826da7f0bbc744f4.jpg",
      "DieselStoreFrontTall":"https://cdn1.epicgames.com/d16f231f238646e881bb0cd83e1d30c8/offer/EGS_TheFall_overTheMoon_S2-1200x1600-368b3e85b4d26f63468593c1defca54f.jpg",
      "startDate":"2021-03-18T15:00:00.000Z",
      "endDate":"2021-03-25T15:00:00.000Z",
      "available":"false"
   },
   {
      "title":"Jurassic World Evolution",
      "id":"e58e33fc6aa449469b6d2fe02f52e4e4",
      "namespace":"d5241c76f178492ea1540fce45616757",
      "effectiveDate":"2099-01-01T00:00:00.000Z",
      "currentPrice":"Free",
      "seller":"Epic Dev Test Account",
      "productSlug":"https://www.epicgames.com/store/product/jurassic-world-evolution",
      "VaultClosed":"https://cdn1.epicgames.com/d5241c76f178492ea1540fce45616757/offer/EGS_HolidaySale2020_DoG_31_1920x1080_Teaser-1920x1080-68876bdc4a75589c69e221b6a00581a3.jpg",
      "DieselStoreFrontWide":"https://cdn1.epicgames.com/d5241c76f178492ea1540fce45616757/offer/EGS_HolidaySale2020_DoG_JurassicWorldEvolution_1920x1080_Teaser-R-1920x1080-26f66b9b2bc29ce9bf2b87abe2efbfab.jpg",
      "startDate":"",
      "endDate":"",
      "available":"true"
   },
   {
      "title":"Torchlight II",
      "id":"af887062235447459380559888ee5b97",
      "namespace":"d5241c76f178492ea1540fce45616757",
      "effectiveDate":"2099-01-01T00:00:00.000Z",
      "currentPrice":"Free",
      "seller":"Epic Dev Test Account",
      "productSlug":"https://www.epicgames.com/store/product/torchlight-2",
      "VaultClosed":"https://cdn1.epicgames.com/d5241c76f178492ea1540fce45616757/offer/EGS_HolidaySale2020_DoG_30_1920x1080_Teaser-1920x1080-0bb081e7879c49cd68f242c49a2ec55c.jpg",
      "DieselStoreFrontWide":"https://cdn1.epicgames.com/d5241c76f178492ea1540fce45616757/offer/EGS_HolidaySale2020_DoG_TorchlightII_1920x1080_Teaser-R-1920x1080-f6aec62524340cff0d7489f7fee95b87.jpg",
      "startDate":"",
      "endDate":"",
      "available":"true"
   },
   {
      "title":"Stranded Deep",
      "id":"45fffdd898b543cfaadb6072d9dfaa58",
      "namespace":"d5241c76f178492ea1540fce45616757",
      "effectiveDate":"2099-01-01T00:00:00.000Z",
      "currentPrice":"Free",
      "seller":"Epic Dev Test Account",
      "productSlug":"https://www.epicgames.com/store/product/stranded-deep/home",
      "VaultClosed":"https://cdn1.epicgames.com/d5241c76f178492ea1540fce45616757/offer/EGS_HolidaySale2020_DoG_28_1920x1080_Teaser-1920x1080-cf3e4beebe9d0a36064acf6d0bdb3217.jpg",
      "DieselStoreFrontWide":"https://cdn1.epicgames.com/d5241c76f178492ea1540fce45616757/offer/EGS_HolidaySale2020_DoG_StrandedDeep_1920x1080_Teaser-R-1920x1080-0b2d3e3f9f64712b216a98091e3cb4f8.jpg",
      "startDate":"",
      "endDate":"",
      "available":"true"
   },
   {
      "id":"engines",
      "end":"true",
      "category":"engines",
      "endDate":"",
      "startDate":""
   }
]
```

Conditional Rendering NextJS
```javascript
{endDate != "" &&
        <h1>Removing previous games!</h1>
    }
```
