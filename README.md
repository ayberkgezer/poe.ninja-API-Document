# poe.ninja API

Hi! I compiled **poe.ninja API** to use in projects

### Active League Names

- `Settlers`
- `Standard`
- `Hardcore`
- `Necropolis`

JS Libraries I Prepared
- poe-api-manager [NPM](https://www.npmjs.com/package/poe-api-manager) [Github](https://github.com/ayberkgezer/poe-api-manager)

## Poe Ninja

There are two types of data types in the poe ninja api. One is `currencyoverview` and the other is `itemoverview`.

| currencyoverview | itemoverview    |
| ---------------- | --------------- |
| Currency         | Oil             |
| Fragment         | Incubator       |
|                  | Scarab          |
|                  | Fossil          |
|                  | Resonator       |
|                  | Essence         |
|                  | DivinationCard  |
|                  | SkillGem        |
|                  | BaseType        |
|                  | HelmetEnchant   |
|                  | UniqueMap       |
|                  | Map             |
|                  | UniqueJewel     |
|                  | UniqueFlask     |
|                  | UniqueWeapon    |
|                  | UniqueArmour    |
|                  | UniqueAccessory |
|                  | Beast           |
|                  | Vials           |
|                  | Delirium Orbs   |
||Omens|
||Unique Relic|
||Cluster Jewel|
||Blighted Maps|
||Blight Ravaged Maps|
||Invitations|
||Memories|
||Coffins|
||AllflameEmbers|
## Poe Ninja API

| Category                                                                                        | API                                                                             |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| [Currency](#currency)                      | https://poe.ninja/api/data/currencyoverview?league=LEAGUE-NAME&type=Currency    |
| [Fragment](#fragment)                      | https://poe.ninja/api/data/currencyoverview?league=LEAGUE-NAME&type=Fragment    |
| [Oils](#oils)                              | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Oil             |
| [Incubators ](#incubators)                 | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Incubator       |
| [Scarabs ](#scarabs)                       | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Scarab          |
| [Fossils ](#fossils)                       | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Fossil          |
| [Resonators ](#resonators)                 | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Resonator       |
| [Essences ](#essences)                     | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Essence         |
| [Divination Cards ](#divination-cards)     | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=DivinationCard  |
| [Skill Gems ](#skill-gems)                 | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=SkillGem        |
| [Base Types ](#base-types)                 | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=BaseType        |
| [Helmet Enchants ](#helmet-enchants)       | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=HelmetEnchant   |
| [Unique Maps ](#unique-maps)               | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueMap       |
| [Maps ](#maps)                             | https://poe.ninja/api/data/itemoverview?type=Map&league=LEAGUE-NAME             |
| [Unique Jewels ](#unique-jewels)           | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueJewel     |
| [Unique Flasks ](#unique-flasks)           | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueFlask     |
| [Unique Weapons ](#unique-weapons)         | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueWeapon    |
| [Unique Armours ](#unique-armours)         | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueArmour    |
| [Unique Accessories ](#unique-accessories) | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueAccessory |
| [Beasts ](#beasts)                         | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Beast           |
| [Vials ](#vials)                           | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Vial            |
| [Delirium Orbs ](#delirium-orbs)           | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=DeliriumOrb     |
| [Omens](#omens) | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Omen
|[Unique Relics](#unique-relics)|https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueRelic|
|[Cluster Jewels](#cluster-jewels)|https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=ClusterJewel|
|[Blighted Maps](#blighted-maps)|https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=BlightedMap|
|[Blight Ravaged Maps](#blight-ravaged-maps)|https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=BlightRavagedMap|
|[Invitations](#invitations)|https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Invitation|
|[Memories](#memories)|https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Memory|
|[Coffins](#coffins)|https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Coffin|
|[Allflame Embers](#allflame-embers)|https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=AllflameEmber|


## Currency

- `https://poe.ninja/api/data/currencyoverview?league=LEAGUE-NAME&type=Currency`
- `LEAGUE-NAME`: Write League Names
- `chaosEquivalent`: Chaos Value
- `pay_currency_id - get_currency_id`: Currency Id
- `get_currency_id - pay_currency_id`: Chaos Id
- `detailsId`: Unique Name
- `icon`: Png Photo

```json
"lines": [
    {
    "currencyTypeName": "Mirror of Kalandra",
    "pay": {
        "id": 0,
        "league_id": 161,
        "pay_currency_id": 22,
        "get_currency_id": 1,
        "sample_time_utc": "2023-03-25T20:33:07.1089319Z",
        "count": 59,
        "value": 0.0000070301,
        "data_point_count": 1,
        "includes_secondary": true,
        "listing_count": 252
    },
    "receive": {
        "id": 0,
        "league_id": 161,
        "pay_currency_id": 1,
        "get_currency_id": 22,
        "sample_time_utc": "2023-03-25T20:33:07.1089319Z",
        "count": 33,
        "value": 146900,
        "data_point_count": 1,
        "includes_secondary": true,
        "listing_count": 161
    },
    "paySparkLine": {
        "data": [],
        "totalChange": 42.25
    },
    "receiveSparkLine": {
        "data": [],
        "totalChange": -3.92
    },
    "chaosEquivalent": 143915.04,
    "lowConfidencePaySparkLine": {
        "data": [],
        "totalChange": 42.25
    },
    "lowConfidenceReceiveSparkLine": {
        "data": [],
        "totalChange": -3.92
    },
    "detailsId": "mirror-of-kalandra"},
]
"currencyDetails": [
    {
        "id": 22,
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvQ3VycmVuY3lEdXBsaWNhdGUiLCJ3IjoxLCJoIjoxLCJzY2FsZSI6MX1d/7111e35254/CurrencyDuplicate.png",
        "name": "Mirror of Kalandra",
        "tradeId": "mirror"
    },
]
```

## Fragment

- `https://poe.ninja/api/data/currencyoverview?league=LEAGUE-NAME&type=Fragment`
- `LEAGUE-NAME`: Write League Names
- `chaosEquivalent`: Chaos Value
- `pay_currency_id - get_currency_id`: Fragment Id
- `get_currency_id - pay_currency_id`: Chaos Id
- `detailsId`: Unique Name
- `icon`: Png Photo

```json
"lines": [
{
    "currencyTypeName": "Voidborn Reliquary Key",
    "pay": {
        "id": 0,
        "league_id": 161,
        "pay_currency_id": 232,
        "get_currency_id": 1,
        "sample_time_utc": "2023-03-27T16:53:05.2641346Z",
        "count": 2,
        "value": 0.0013066536,
        "data_point_count": 1,
        "includes_secondary": true,
        "listing_count": 4
    },
    "receive": {},
    "paySparkLine": {
        "data": [],
        "totalChange": -21.19
    },
    "receiveSparkLine": {
        "data": [],
        "totalChange": -32.1
    },
    "chaosEquivalent": 1100,
    "lowConfidencePaySparkLine": {
        "data": [],
        "totalChange": -28.83
    },
    "lowConfidenceReceiveSparkLine": {
        "data": [],
        "totalChange": -32.1
    },
    "detailsId": "voidborn-reliquary-key"
},
]
"currencyDetails": [
    {
        "id": 232,
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvTWFwcy9Db3NtaWNDb3JlU3VwcG9ydGVyVmF1bHRLZXkiLCJ3IjoxLCJoIjoxLCJzY2FsZSI6MX1d/16d2e6b54d/CosmicCoreSupporterVaultKey.png",
        "name": "Voidborn Reliquary Key",
        "tradeId": "voidborn-reliquary-key"
    },
]
```

## Oils

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Oil`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 22607,
        "name": "Golden Oil",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvT2lscy9Hb2xkZW5PaWwiLCJ3IjoxLCJoIjoxLCJzY2FsZSI6MX1d/69094a06e9/GoldenOil.png",
        "baseType": "Golden Oil",
        "stackSize": 10,
        "itemClass": 5,
        "sparkline": {
            "data": [],
            "totalChange": -1.67
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": -1.67
        },
        "implicitModifiers": [],
        "explicitModifiers": [],
        "flavourText": "",
        "chaosValue": 59,
        "exaltedValue": 2.42,
        "divineValue": 0.23,
        "count": 99,
        "detailsId": "golden-oil",
        "listingCount": 1997
    },
]
```

## Incubators

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Incubator`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 21676,
        "name": "Whispering Incubator",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvSW5jdWJhdGlvbi9JbmN1YmF0aW9uRXNzZW5jZSIsInciOjEsImgiOjEsInNjYWxlIjoxfV0/4a659194f8/IncubationEssence.png",
        "stackSize": 10,
        "itemClass": 5,
        "sparkline": {
            "data": [],
            "totalChange": 0
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": -4.6
        },
        "implicitModifiers": [],
        "explicitModifiers": [
            {
                "text": "Adds an incubated Essence item to an equippable item\nItem drops after killing (2495-2685) monsters",
                "optional": false
            }
        ],
        "flavourText": "",
        "chaosValue": 249.02,
        "exaltedValue": 10.7,
        "divineValue": 1,
        "count": 1,
        "detailsId": "whispering-incubator",
        "listingCount": 2
    },
]
```

## Scarabs

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Scarab`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 42606,
        "name": "Winged Divination Scarab",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvU2NhcmFicy9UaWVyNFNjYXJhYkRpdmluYXRpb24iLCJ3IjoxLCJoIjoxLCJzY2FsZSI6MX1d/e6539f578d/Tier4ScarabDivination.png",
        "stackSize": 10,
        "itemClass": 0,
        "sparkline": {
            "data": [],
            "totalChange": -3.99
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": -3.99
        },
        "implicitModifiers": [],
        "explicitModifiers": [
            {
                "text": "250% more Divination Cards found in Area",
                "optional": false
            }
        ],
        "flavourText": "Hinekora has sent the world another herald, but this hatungo walks another path.\nWe are left blinded, and subject to the vagaries of Fate.",
        "chaosValue": 35.61,
        "exaltedValue": 1.5,
        "divineValue": 0.14,
        "count": 99,
        "detailsId": "winged-divination-scarab",
        "listingCount": 3248
    },
]
```

## Fossils

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Fossil`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 7666,
        "name": "Glyphic Fossil",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvRGVsdmUvR2x5cGhpY0Zvc3NpbCIsInciOjEsImgiOjEsInNjYWxlIjoxfV0/f5b3c6edf7/GlyphicFossil.png",
        "stackSize": 10,
        "itemClass": 5,
        "sparkline": {
            "data": [],
            "totalChange": -1.8
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": -1.8
        },
        "implicitModifiers": [],
        "explicitModifiers": [
            {
                "text": "Has a Corrupt Essence modifier",
                "optional": false
            }
        ],
        "flavourText": "",
        "chaosValue": 98.2,
        "exaltedValue": 4.48,
        "divineValue": 0.4,
        "count": 99,
        "detailsId": "glyphic-fossil",
        "listingCount": 1678
},
]
```

## Resonators

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Resanator`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 7662,
        "name": "Prime Chaotic Resonator",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvRGVsdmUvUmVyb2xsMngyQyIsInciOjIsImgiOjIsInNjYWxlIjoxfV0/584267701b/Reroll2x2C.png",
        "stackSize": 10,
        "itemClass": 5,
        "sparkline": {
            "data": [],
            "totalChange": 0
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": 0
        },
        "implicitModifiers": [],
        "explicitModifiers": [],
        "flavourText": "",
        "chaosValue": 33,
        "exaltedValue": 1.51,
        "divineValue": 0.13,
        "count": 99,
        "detailsId": "prime-chaotic-resonator",
        "listingCount": 4426
    },
]
```

## Essences

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Essence`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 494,
        "name": "Essence of Horror",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvRXNzZW5jZS9Ib3Jyb3IxIiwidyI6MSwiaCI6MSwic2NhbGUiOjF9XQ/748d594bde/Horror1.png",
        "mapTier": 8,
        "baseType": "Essence of Horror",
        "stackSize": 9,
        "itemClass": 5,
        "sparkline": {},
        "lowConfidenceSparkline": {},
        "implicitModifiers": [],
        "explicitModifiers": [
            {
                "text": "Upgrades a normal item to rare or reforges a rare item, guaranteeing one property",
                "optional": false
            },
            {
                "text": "",
                "optional": false
            },
            {
                "text": "Weapon: 16% chance to gain a Power, Frenzy or Endurance Charge on Kill",
                "optional": false
            },
            {
                "text": "Gloves: Socketed Gems have +3.5% Critical Strike Chance",
                "optional": false
            },
            {
                "text": "Boots: 5% reduced Elemental Damage Taken while stationary",
                "optional": false
            },
            {
                "text": "Body Armour: 15% of Physical Damage from Hits taken as Cold Damage",
                "optional": false
            },
            {
                "text": "Helmet: Socketed Gems deal 30% more Elemental Damage",
                "optional": false
            },
            {
                "text": "Shield: Chill Nearby Enemies when you Block",
                "optional": false
            },
            {
                "text": "Quiver: 8 to 12 Added Cold Damage per Frenzy Charge",
                "optional": false
            },
            {
                "text": "Amulet: (15-25)% chance to Crush on Hit",
                "optional": false
            },
            {
                "text": "Ring: 4 to 7 Added Cold Damage per Frenzy Charge",
                "optional": false
            },
            {
                "text": "Belt: Gain Alchemist's Genius when you use a Flask",
                "optional": false
            }
        ],
        "flavourText": "",
        "chaosValue": 35,
        "exaltedValue": 1.56,
        "divineValue": 0.14,
        "count": 99,
        "detailsId": "essence-of-horror",
        "listingCount": 5237
    },
]
```

## Divination Cards

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=DivinationCard`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 636,
        "name": "House of Mirrors",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvRGl2aW5hdGlvbi9JbnZlbnRvcnlJY29uIiwidyI6MSwiaCI6MSwic2NhbGUiOjF9XQ/f34bf8cbb5/InventoryIcon.png",
        "stackSize": 9,
        "artFilename": "HouseOfMirrors",
        "itemClass": 6,
        "sparkline": {
            "data": [],
            "totalChange": -7.62
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": -7.62
        },
        "implicitModifiers": [],
        "explicitModifiers": [
            {
                "text": "<currencyitem>{Mirror of Kalandra}",
                "optional": false
            }
        ],
        "flavourText": "What do you see in the mirror?",
        "chaosValue": 18567,
        "exaltedValue": 822.64,
        "divineValue": 75,
        "count": 44,
        "detailsId": "house-of-mirrors",
        "listingCount": 119
    },
]
```

## Skill Gems

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=SkillGem`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id":96363,
        "name":"Awakened Enlighten Support",
        "icon":"https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvR2Vtcy9TdXBwb3J0L1N1cHBvcnRQbHVzL0VubGlnaHRlbnBsdXMiLCJ3IjoxLCJoIjoxLCJzY2FsZSI6MX1d/7ec7d0544d/Enlightenplus.png",
        "levelRequired":80,
        "variant":"5/20c",
        "itemClass":4,
        "sparkline":{"data":[],"totalChange":-2.35},
        "lowConfidenceSparkline":{
            "data":[],
            "totalChange":-2.35
        },
        "implicitModifiers":[],
        "explicitModifiers":[
            {
                "text":"This Gem gains (95-110)% increased Experience",
                "optional":false
            }
        ],
        "flavourText":"",
        "corrupted":true,
        "gemLevel":5,
        "gemQuality":20,
        "chaosValue":104767.39,
        "exaltedValue":4641.89,
        "divineValue":423.20,
        "count":5,
        "detailsId":"awakened-enlighten-support-5-20c",
        "listingCount":11
    },
]
```

## Base Types

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=BaseType`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id":101178,
        "name":"Accumulator Wand",
        "icon":"https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvV2VhcG9ucy9PbmVIYW5kV2VhcG9ucy9XYW5kcy9IZWlzdFdhbmQiLCJ3IjoxLCJoIjozLCJzY2FsZSI6MX1d/4499b00066/HeistWand.png",
        "levelRequired":86,
        "baseType":"Accumulator Wand",
        "variant":"Shaper/Elder",
        "itemClass":2,
        "sparkline":{"data":[],"totalChange":0},
        "lowConfidenceSparkline":{
            "data":[],
            "totalChange":159134.70
        },
        "implicitModifiers":[],
        "explicitModifiers":[],
        "flavourText":"",
        "itemType":"Wand",
        "chaosValue":274791.32,
        "exaltedValue":12175.07,
        "divineValue":1110.00,
        "count":1,
        "detailsId":"accumulator-wand-86-shaper-elder",
        "listingCount":6
    },
]
```

## Helmet Enchants

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=HelmetEnchant`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 6097,
        "name": "Tornado Shot fires an additional secondary Projectile",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvR2Vtcy9Ub3JuYWRvU2hvdCIsInciOjEsImgiOjEsInNjYWxlIjoxfV0/7299d3edf8/TornadoShot.png",
        "variant": "0",
        "itemClass": 0,
        "sparkline": {
            "data": [],
            "totalChange": 89.01
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": 89.01
        },
        "implicitModifiers": [],
        "explicitModifiers": [],
        "chaosValue": 495.12,
        "exaltedValue": 21.94,
        "divineValue": 2,
        "count": 99,
        "detailsId": "tornado-shot-fires-an-additional-secondary-projectile-0",
        "tradeInfo": [
            {
                "mod": "enchant.stat_1580810115",
                "min": 1,
                "max": 1
            }
        ],
        "listingCount": 1544
    },
]
```

## Unique Maps

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueMap`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 41117,
        "name": "Doryani's Machinarium",
        "icon": "https://web.poecdn.com/gen/image/WzI4LDE0LHsiZiI6IjJESXRlbXMvTWFwcy9Eb3J5YW5pcyIsInciOjEsImgiOjEsInNjYWxlIjoxfV0/581444be53/Doryanis.png",
        "mapTier": 14,
        "baseType": "Maze Map",
        "itemClass": 3,
        "sparkline": {
            "data": [],
            "totalChange": 19.1
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": 19.1
        },
        "implicitModifiers": [],
        "explicitModifiers": [
            {
                "text": "(20-50)% increased Experience gain",
                "optional": false
            },
            {
                "text": "Found Items have 10% chance to drop Corrupted in Area",
                "optional": false
            },
            {
                "text": "Unique Boss is augmented by Player choices",
                "optional": false
            }
        ],
        "flavourText": "We are ever the makers of our own undoing.",
        "chaosValue": 3309.8,
        "exaltedValue": 147.04,
        "divineValue": 13.4,
        "count": 5,
        "detailsId": "doryanis-machinarium-t14",
        "listingCount": 32
    },
]
```

## Maps

- `https://poe.ninja/api/data/itemoverview?type=Map&league=LEAGUE-NAME`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 100355,
        "name": "Maze of the Minotaur Map",
        "icon": "https://web.poecdn.com/gen/image/WzI4LDE0LHsiZiI6IjJESXRlbXMvTWFwcy9BdGxhczJNYXBzL05ldy9NaW5vdGF1ciIsInciOjEsImgiOjEsInNjYWxlIjoxLCJtbiI6MTYsIm10IjowLCJtaSI6MX1d/9a58b4bdae/Minotaur.png",
        "mapTier": 16,
        "baseType": "Maze of the Minotaur Map",
        "variant": ", Gen-16",
        "itemClass": 2,
        "sparkline": {
            "data": [],
            "totalChange": 25
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": 25
        },
        "implicitModifiers": [],
        "explicitModifiers": [],
        "flavourText": "",
        "chaosValue": 15,
        "exaltedValue": 0.67,
        "divineValue": 0.06,
        "count": 99,
        "detailsId": "maze-of-the-minotaur-map-t16-gen-16",
        "listingCount": 9101
    },
]
```

## Unique Jewels

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueJewel`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 40773,
        "name": "Voices",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvSmV3ZWxzL1VuaXF1ZUpld2VsQmFzZTMiLCJ3IjoxLCJoIjoxLCJzY2FsZSI6MX1d/314c9905c8/UniqueJewelBase3.png",
        "baseType": "Large Cluster Jewel",
        "itemClass": 3,
        "sparkline": {
            "data": [],
            "totalChange": 5.47
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": 5.47
        },
        "implicitModifiers": [],
        "explicitModifiers": [],
        "flavourText": "Only a madman would ignore a god's instructions.",
        "chaosValue": 96330,
        "exaltedValue": 4279.43,
        "divineValue": 390,
        "count": 22,
        "detailsId": "voices-large-cluster-jewel",
        "listingCount": 67
    },
]
```

## Unique Flasks

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueFlask`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 101729,
        "name": "Progenesis",
        "icon": "https://web.poecdn.com/gen/image/WzksMTQseyJmIjoiMkRJdGVtcy9GbGFza3MvVWJlck1hdmVuRmxhc2siLCJ3IjoxLCJoIjoyLCJzY2FsZSI6MSwibGV2ZWwiOjEsInJlbGljIjowfV0/ac476ad3d0/UberMavenFlask.png",
        "levelRequired": 60,
        "baseType": "Amethyst Flask",
        "itemClass": 9,
        "sparkline": {
            "data": [],
            "totalChange": 169.37
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": 149.62
        },
        "implicitModifiers": [],
        "explicitModifiers": [
            {
                "text": "(10-20)% reduced Charges per use",
                "optional": false
            },
            {
                "text": "(1-35)% reduced Duration",
                "optional": true
            },
            {
                "text": "(1-35)% increased Duration",
                "optional": true
            },
            {
                "text": "When Hit during effect, 25% of Life loss from Damage taken occurs over 4 seconds instead",
                "optional": false
            }
        ],
        "flavourText": "They were bred in a cosmic ocean of raw creation.\nFeasting and drinking of the milk of the mother,\nthey fought to the death for every last drop.",
        "chaosValue": 32110,
        "exaltedValue": 1426.48,
        "divineValue": 130,
        "count": 4,
        "detailsId": "progenesis-relic",
        "listingCount": 30
    },
]
```

## Unique Weapons

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueWeapon`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 99868,
        "name": "Voidforge",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvV2VhcG9ucy9Ud29IYW5kV2VhcG9ucy9Ud29IYW5kU3dvcmRzL1N0YXJmb3JnZSIsInciOjIsImgiOjQsInNjYWxlIjoxLCJyZWxpYyI6MH1d/1a41d46a59/Starforge.png",
        "levelRequired": 67,
        "baseType": "Infernal Sword",
        "links": 6,
        "itemClass": 9,
        "sparkline": {
            "data": [],
            "totalChange": 0
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": -0.21
        },
        "implicitModifiers": [
            {
                "text": "30% increased Elemental Damage with Attack Skills",
                "optional": false
            }
        ],
        "explicitModifiers": [
            {
                "text": "6% increased Attack Speed",
                "optional": false
            },
            {
                "text": "+(91-92) to maximum Life",
                "optional": false
            },
            {
                "text": "Your Elemental Damage can Shock",
                "optional": false
            },
            {
                "text": "Gain 700% of Weapon Physical Damage as Extra Damage of a random Element",
                "optional": false
            },
            {
                "text": "20% increased Area of Effect for Attacks",
                "optional": false
            },
            {
                "text": "Deal no Non-Elemental Damage",
                "optional": false
            }
        ],
        "flavourText": "A weapon born of nothingness,\ncan only create more nothingness.",
        "itemType": "Two Handed Sword",
        "chaosValue": 137105.86,
        "exaltedValue": 6090.89,
        "divineValue": 555.08,
        "count": 1,
        "detailsId": "voidforge-infernal-sword-relic-6l",
        "listingCount": 2
    },
]
```

## Unique Armours

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueArmour`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 99487,
        "name": "The Eternity Shroud",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQXJtb3Vycy9Cb2R5QXJtb3Vycy9NYW50bGVPZkRpc21hbnRsaW5nIiwidyI6MiwiaCI6Mywic2NhbGUiOjEsInJlbGljIjowfV0/0a567446fc/MantleOfDismantling.png",
        "levelRequired": 65,
        "baseType": "Blood Raiment",
        "links": 6,
        "itemClass": 9,
        "sparkline": {
            "data": [],
            "totalChange": 0
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": -4.14
        },
        "implicitModifiers": [],
        "explicitModifiers": [
            {
                "text": "Trigger Level 20 Glimpse of Eternity when Hit",
                "optional": false
            },
            {
                "text": "(105-146)% increased Evasion and Energy Shield",
                "optional": false
            },
            {
                "text": "+(84-96) to maximum Life",
                "optional": false
            },
            {
                "text": "+(19-23)% to Chaos Resistance",
                "optional": false
            },
            {
                "text": "Gain (4-5)% of Elemental Damage as Extra Chaos Damage per Shaper Item Equipped",
                "optional": false
            },
            {
                "text": "Hits ignore Enemy Monster Chaos Resistance if all Equipped Items are Shaper Items",
                "optional": false
            }
        ],
        "flavourText": "There can be no defence against the celestial siblings entropy and time.",
        "itemType": "Body Armour",
        "chaosValue": 274211.72,
        "exaltedValue": 12181.77,
        "divineValue": 1110.17,
        "count": 1,
        "detailsId": "the-eternity-shroud-blood-raiment-relic-6l",
        "listingCount": 2
    },
]
```

## Unique Accessories

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueAccessory`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 102267,
        "name": "Impresence",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQW11bGV0cy9FbGRlclBoeXNpY2FsIiwidyI6MSwiaCI6MSwic2NhbGUiOjEsInJlbGljIjowfV0/6205114f81/ElderPhysical.png",
        "levelRequired": 64,
        "baseType": "Onyx Amulet",
        "variant": "Physical",
        "itemClass": 9,
        "sparkline": {
            "data": [],
            "totalChange": 0
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": -4.14
        },
        "implicitModifiers": [
            {
                "text": "+(10-16) to all Attributes",
                "optional": false
            }
        ],
        "explicitModifiers": [
            {
                "text": "Adds (12-16) to (21-25) Physical Damage",
                "optional": false
            },
            {
                "text": "+(417-499) to Armour",
                "optional": false
            },
            {
                "text": "+(51-61) to maximum Life",
                "optional": false
            },
            {
                "text": "(30-39)% increased Stun and Block Recovery",
                "optional": false
            },
            {
                "text": "Punishment has no Reservation if Cast as an Aura",
                "optional": true
            },
            {
                "text": "Elemental Weakness has no Reservation if Cast as an Aura",
                "optional": true
            },
            {
                "text": "Enfeeble has no Reservation if Cast as an Aura",
                "optional": true
            },
            {
                "text": "Temporal Chains has no Reservation if Cast as an Aura",
                "optional": true
            },
            {
                "text": "Vulnerability has no Reservation if Cast as an Aura",
                "optional": false
            },
            {
                "text": "Gain Maddening Presence for 10 seconds when you Kill a Rare or Unique Enemy",
                "optional": false
            }
        ],
        "flavourText": "There is no darker void than the hollow\nache of love disremembered...",
        "itemType": "Amulet",
        "chaosValue": 274211.72,
        "exaltedValue": 12181.77,
        "divineValue": 1110.17,
        "count": 1,
        "detailsId": "impresence-physical-onyx-amulet-relic",
        "listingCount": 3
    },
]
```

## Beasts

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Beast`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 20253,
        "name": "Barrow Ape",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvQmVzdGlhcnlPcmJGdWxsIiwidyI6MSwiaCI6MSwic2NhbGUiOjF9XQ/3214b44360/BestiaryOrbFull.png",
        "baseType": "Apes|Primates|The Wilds",
        "itemClass": 2,
        "sparkline": {
            "data": [],
            "totalChange": 54.55
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": 125645.45
        },
        "implicitModifiers": [],
        "explicitModifiers": [],
        "flavourText": "",
        "chaosValue": 5532.8,
        "exaltedValue": 245.79,
        "divineValue": 22.4,
        "count": 2,
        "detailsId": "barrow-ape",
        "listingCount": 146
    },
]
```

## Vials

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Beast`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 39825,
        "name": "Vial of Sacrifice",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvVmlhbFNhY3JpZmljaWFsSGVhcnQiLCJ3IjoxLCJoIjoxLCJzY2FsZSI6MX1d/7f68150b22/VialSacrificialHeart.png",
        "stackSize": 10,
        "itemClass": 5,
        "sparkline": {
            "data": [],
            "totalChange": 0
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": 2134.76
        },
        "implicitModifiers": [],
        "explicitModifiers": [],
        "flavourText": "Festivities of blood. Bleeding hearts and screaming lungs.",
        "chaosValue": 938.6,
        "exaltedValue": 41.7,
        "divineValue": 3.8,
        "count": 2,
        "detailsId": "vial-of-sacrifice",
        "listingCount": 51
    },
]
```

## Delirium Orbs

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=DeliriumOrb`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 40910,
        "name": "Diviner's Delirium Orb",
        "icon":   "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvRGVsaXJpdW0vRGVsaXJpdW1PcmJEaXZpbmF0aW9uQ2FyZHMiLCJ3IjoxLCJoIjoxLCJzY2FsZSI6MX1d/e47017caab/DeliriumOrbDivinationCards.png",
        "baseType": "Diviner's Delirium Orb",
        "stackSize": 10,
        "itemClass": 5,
        "sparkline": {
            "data": [],
            "totalChange": 0
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": 0
        },
        "implicitModifiers": [],
        "explicitModifiers": [
            {
                "text": "Modifies a Map item adding layers of Delirium with the Divination Cards reward type",
                "optional": false
            }
        ],
        "flavourText": "",
        "chaosValue": 17,
        "exaltedValue": 0.98,
        "divineValue": 0.08,
        "count": 99,
        "detailsId": "diviners-delirium-orb",
        "tradeInfo": [],
        "listingCount": 6047
    },
]
```

## Omens

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Omen`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 107341,
        "name": "Omen of Fortune",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvQXptZXJpL1Zvb2Rvb09tZW5zMVB1cnBsZSIsInciOjEsImgiOjEsInNjYWxlIjoxfV0/68c64f2338/VoodooOmens1Purple.png",
        "baseType": "Omen of Fortune",
        "itemClass": 5,
        "sparkline": {
            "data": [
                0,
                36.87,
                42.01,
                42.72,
                43.25,
                43.34,
                49.9
            ],
        "totalChange": 49.9
        },
        "lowConfidenceSparkline": {
            "data": [
                0,
                36.87,
                42.01,
                42.72,
                43.25,
                43.34,
                49.9
            ],
        "totalChange": 49.9
        },
        "implicitModifiers": [],
        "explicitModifiers": [
            {
                "text": "Will be Consumed when you use an Orb of Chance\non an item which can become Unique to ensure it does so",
                "optional": false
            }
        ],
        "flavourText": "",
        "chaosValue": 3500.28,
        "exaltedValue": 315.06,
        "divineValue": 27,
        "count": 32,
        "detailsId": "omen-of-fortune",
        "tradeInfo": [],
        "listingCount": 71
    },
]
```

## Unique Relics

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueRelic`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
	    "id": 107858,
	    "name": "The Original Scripture",
	    "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvUmVsaWNzL1JlbGljVW5pcXVlNHgxIiwidyI6NCwiaCI6MSwic2NhbGUiOjF9XQ/e6e8bfb6e4/RelicUnique4x1.png",
	    "baseType": "Papyrus Relic",
	    "itemClass": 3,
	    "sparkline": {
		    "data": [
			    0,
			    -6.53,
			    -12.59,
			    -3.74,
			    -3.79,
			    -2.13,
			    0.58
		    ],
		    "totalChange": 0.58
	    },
	    "lowConfidenceSparkline": {
		    "data": [
			    0,
			    -6.53,
			    -12.59,
			    -3.74,
			    -3.79,
			    -2.13,
			    0.58
		    ],
		    "totalChange": 0.58
	    },
	    "implicitModifiers": [],
	    "explicitModifiers": [
		    {
			    "text": "The Herald of the Scourge drops the Original Sin",
			    "optional": false
		    },
		    {
			    "text": "Cannot have Inspiration",
			    "optional": false
		    },
		    {
			    "text": "Maximum Resolve is 1",
			    "optional": false
		    },
		    {
			    "text": "Cannot be used with Forbidden Tomes below level 83",
			    "optional": false
		    },
		    {
			    "text": "This item is destroyed when applied to a Sanctum",
			    "optional": false
		    }
	    ],
	    "flavourText": "\"It's all here. The lie at the core of my faith. Maxarius was not the first chosen of Innocence. Maxarius was Innocence himself. A charlatan, a liar, and a power-seeker.\" - Lycia, the Heretic",
	    "chaosValue": 181464.1,
	    "exaltedValue": 16333.4,
	    "divineValue": 1399.75,
	    "count": 12,
	    "detailsId": "the-original-scripture-relic",
	    "tradeInfo": [],
	    "listingCount": 18
    }
]
```

## Cluster Jewels

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=ClusterJewel`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
	    "id": 71084,
	    "name": "6% increased Mana Reservation Efficiency of Skills",
	    "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvSmV3ZWxzL05ld0dlbUJhc2UxIiwidyI6MSwiaCI6MSwic2NhbGUiOjF9XQ/0eb1a9d981/NewGemBase1.png",
	    "levelRequired": 84,
	    "baseType": "Small Cluster Jewel",
	    "variant": "3 passives",
	    "itemClass": 2,
	    "sparkline": {
		    "data": [
			    0,
			    -0.88,
		    	1.11,
		    	11.99,
		    	5.05,
		    	5.43,
			    6.71
		    ],
		    "totalChange": 6.71
	    },
	    "lowConfidenceSparkline": {
		    "data": [
			    0,
			    -0.88,
			    1.11,
			    11.99,
			    5.05,
			    5.43,
			    6.71
		    ],
		    "totalChange": 6.71
	    },
	    "implicitModifiers": [],
	    "explicitModifiers": [],
	    "flavourText": "",
	    "itemType": "Jewel",
	    "chaosValue": 7524.92,
	    "exaltedValue": 677.31,
	    "divineValue": 58,
	    "count": 399,
	    "detailsId": "6-increased-mana-reservation-efficiency-of-skills-3-passives-84",
	    "tradeInfo": [
		    {
			    "mod": "enchant.stat_3948993189",
			    "min": 0,
			    "max": 0,
			    "option": "54"
		    },
		    {
			    "mod": "enchant.stat_3086156145",
			    "min": 3,
			    "max": 3
		    }
	    ],
	    "listingCount": 2612
    }
]
```

## Blighted Maps

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=BlightedMap`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 109785,
        "name": "Blighted Relic Chambers Map",
        "icon": "https://web.poecdn.com/gen/image/WzI4LDE0LHsiZiI6IjJESXRlbXMvTWFwcy9BdGxhczJNYXBzL05ldy9BbnRpcXVhcnkiLCJ3IjoxLCJoIjoxLCJzY2FsZSI6MSwibW4iOjE5LCJtdCI6MTAsIm1iIjp0cnVlfV0/d55ed367b8/Antiquary.png",
        "mapTier": 10,
        "baseType": "Blighted Relic Chambers Map",
        "variant": ", Gen-19",
        "itemClass": 0,
        "sparkline": {
            "data": [],
            "totalChange": 0
        },
        "lowConfidenceSparkline": {
            "data": [
                0,
                -0.41,
                1.5,
                3.86,
                5.3,
                6.01,
                10.74
            ],
            "totalChange": 10.74
        },
        "implicitModifiers": [],
        "explicitModifiers": [],
        "flavourText": "",
        "chaosValue": 129.55,
        "exaltedValue": 11.66,
        "divineValue": 1,
        "count": 1,
        "detailsId": "blighted-relic-chambers-map-t10-gen-19",
        "tradeInfo": [],
        "listingCount": 4
    },
]
```

## Blight Ravaged Maps

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=BlightRavagedMap`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 109851,
        "name": "Blight-ravaged Bone Crypt Map",
        "icon": "https://web.poecdn.com/gen/image/WzI4LDE0LHsiZiI6IjJESXRlbXMvTWFwcy9BdGxhczJNYXBzL05ldy9DYXRhY29tYiIsInciOjEsImgiOjEsInNjYWxlIjoxLCJtbiI6MTksIm10IjoxNiwibXViIjp0cnVlfV0/22c6fcf5fb/Catacomb.png",
        "mapTier": 16,
        "baseType": "Blight-ravaged Bone Crypt Map",
        "variant": ", Gen-19",
        "itemClass": 0,
        "sparkline": {
            "data": [],
            "totalChange": 0
        },
        "lowConfidenceSparkline": {
            "data": [
                0,
                -0.35,
                -22.19,
                59.64,
                65.9,
                65.95,
                102.86
            ],
            "totalChange": 102.86
        },
        "implicitModifiers": [],
        "explicitModifiers": [],
        "flavourText": "",
        "chaosValue": 1016.6,
        "exaltedValue": 91.5,
        "divineValue": 7.85,
        "count": 2,
        "detailsId": "blight-ravaged-bone-crypt-map-t16-gen-19",
        "tradeInfo": [],
        "listingCount": 5
    },
]
```

## Invitations

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Invitation`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 93816,
        "name": "Screaming Invitation",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvUXVlc3RJdGVtcy9UYW5nbGVkT3JiUXVlc3Q1IiwidyI6MSwiaCI6MSwic2NhbGUiOjF9XQ/75de691c2b/TangledOrbQuest5.png",
        "baseType": "Screaming Invitation",
        "itemClass": 0,
        "sparkline": {
            "data": [
                0,
                7.53,
                1.38,
                -3.09,
                14.45,
                22.89,
                -7.83
            ],
            "totalChange": -7.83
        },
        "lowConfidenceSparkline": {
            "data": [
                0,
                7.53,
                1.38,
                -3.09,
                14.45,
                22.89,
                -7.83
            ],
            "totalChange": -7.83
        },
        "implicitModifiers": [],
        "explicitModifiers": [],
        "flavourText": "From the heart of the Tangle, the Eater of Worlds\nreaches out for control of the Atlas.",
        "chaosValue": 300,
        "exaltedValue": 27.47,
        "divineValue": 2.32,
        "count": 399,
        "detailsId": "screaming-invitation",
        "tradeInfo": [],
        "listingCount": 8416
    },
]
```

## Memories

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Memory`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 108143,
        "name": "Einhar's Memory of Harvest Beasts",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvTWVtb3J5TGluZS9FaW5oYXJNZW1vcnlJdGVtIiwidyI6MSwiaCI6MSwic2NhbGUiOjF9XQ/5e4c7a8f89/EinharMemoryItem.png",
        "baseType": "Einhar's Memory",
        "itemClass": 1,
        "sparkline": {
            "data": [
                0,
                -0.41,
                0.54,
                1.74,
                -8.39,
                -8.4,
                -3.79
            ],
            "totalChange": -3.79
        },
        "lowConfidenceSparkline": {
            "data": [
                0,
                -0.41,
                0.54,
                1.74,
                -8.39,
                -8.4,
                -3.79
            ],
            "totalChange": -3.79
        },
        "implicitModifiers": [],
        "explicitModifiers": [
            {
                "text": "Areas contain Einhar\nAreas can contain capturable Harvest Beasts",
                "optional": false
            }
        ],
        "flavourText": "",
        "chaosValue": 1800.74,
        "exaltedValue": 164.9,
        "divineValue": 13.9,
        "count": 399,
        "detailsId": "einhars-memory-of-harvest-beasts",
        "tradeInfo": [
            {
                "mod": "explicit.stat_3751566939",
                "min": 0,
                "max": 0
            }
        ],
        "listingCount": 1815
    }
]
```

## Coffins

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Coffin`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 116312,
        "name": "Creates a Sacrificial Garb",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvTmVjcm9wb2xpcy9OZWNyb3BvbGlzQ29mZmluRmlsbGVkIiwidyI6MiwiaCI6MSwic2NhbGUiOjF9XQ/5b4214a420/NecropolisCoffinFilled.png",
        "levelRequired": 80,
        "baseType": "Creates a Sacrificial Garb",
        "itemClass": 5,
        "sparkline": {
            "data": [],
            "totalChange": 0
        },
        "lowConfidenceSparkline": {
            "data": [],
            "totalChange": 792.03
        },
        "implicitModifiers": [
            {
                "text": "Creates a Sacrificial Garb",
                "optional": false
            }
        ],
        "explicitModifiers": [],
        "flavourText": "",
        "chaosValue": 267.61,
        "exaltedValue": 27.82,
        "divineValue": 2.02,
        "count": 17,
        "detailsId": "creates-a-sacrificial-garb-80",
        "tradeInfo": [],
        "tradeFilter": {
            "query": {}
        },
        "listingCount": 17
    }
]
```

## Allflame Embers

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=AllflameEmber`
- `LEAGUE-NAME`: Write League Names
- `id`: Unique Item Id
- `name`: Item Name
- `icon`: Png Photo
- `chaosValue`: Chaos Price
- `exaltedValue`: Exalted Price
- `divineValue`: Divine Price
- `detailsId`: Unique Name

```json
"lines": [
    {
        "id": 117303,
        "name": "Allflame Ember of The Shaper",
        "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvTmVjcm9wb2xpcy9BbGxmbGFtZUVtYmVyc0Jhc2VJbmZsdWVuY2UiLCJ3IjoxLCJoIjoxLCJzY2FsZSI6MX1d/002ce1f2e1/AllflameEmbersBaseInfluence.png",
        "levelRequired": 82,
        "baseType": "Allflame Ember of The Shaper",
        "itemClass": 11,
        "sparkline": {
            "data": [
                0,
                -21.53,
                -17.73,
                44.98,
                39.77,
                47.13,
                52.04
            ],
            "totalChange": 52.04
        },
        "lowConfidenceSparkline": {
            "data": [
                0,
                -21.53,
                -17.73,
                44.98,
                39.77,
                47.13,
                52.04
            ],
            "totalChange": 52.04
        },
        "implicitModifiers": [
            {
                "text": "Pack monsters can drop Shaper Influenced items\nPack monsters have a chance to leave corpses with a Special Craft",
                "optional": false
            },
            {
                "text": "Pack monsters can drop Shaper Influenced items",
                "optional": true
            }
        ],
        "explicitModifiers": [],
        "flavourText": "",
        "chaosValue": 310,
        "exaltedValue": 36.9,
        "divineValue": 2.37,
        "count": 399,
        "detailsId": "allflame-ember-of-the-shaper-(82-83)",
        "tradeInfo": [],
        "tradeFilter": {
            "query": {
                "type": {
                    "option": "Allflame Ember of The Shaper"
                },
                "filters": {
                    "misc_filters": {
                        "filters": {
                            "ilvl": {
                                "min": 82,
                                "max": 83
                            }
                        }
                    }
                }
            }
        },
        "listingCount": 2240
    }
]
```
