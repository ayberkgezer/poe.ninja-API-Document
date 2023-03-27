# poe.ninja API

Hi! I compiled **poe.ninja API** to use in projects

### Active League Names

- Sanctum
- Standart

## Tables

| Category                                                                                        | API                                                                             |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| [Currency](https://github.com/ayberkgezer/poe.ninja-API-Document#currency)                      | https://poe.ninja/api/data/currencyoverview?league=LEAGUE-NAME&type=Currency    |
| [Fragment](https://github.com/ayberkgezer/poe.ninja-API-Document#fragment)                      | https://poe.ninja/api/data/currencyoverview?league=LEAGUE-NAME&type=Fragment    |
| [Oils](https://github.com/ayberkgezer/poe.ninja-API-Document#oils)                              | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Oil             |
| [Incubators ](https://github.com/ayberkgezer/poe.ninja-API-Document#incubators)                 | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Incubator       |
| [Scarabs ](https://github.com/ayberkgezer/poe.ninja-API-Document#scarabs)                       | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Scarab          |
| [Fossils ](https://github.com/ayberkgezer/poe.ninja-API-Document#fossils)                       | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Fossil          |
| [Resonators ](https://github.com/ayberkgezer/poe.ninja-API-Document#resonators)                 | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Resonator       |
| [Essences ](https://github.com/ayberkgezer/poe.ninja-API-Document#essences)                     | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Essence         |
| [Divination Cards ](https://github.com/ayberkgezer/poe.ninja-API-Document#divination-cards)     | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=DivinationCard  |
| [Prophecies ](https://github.com/ayberkgezer/poe.ninja-API-Document#prophecies)                 | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Prophecy        |
| [Skill Gems ](https://github.com/ayberkgezer/poe.ninja-API-Document#skill-gems)                 | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=SkillGem        |
| [Base Types ](https://github.com/ayberkgezer/poe.ninja-API-Document#base-types)                 | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=BaseType        |
| [Helmet Enchants ](https://github.com/ayberkgezer/poe.ninja-API-Document#helmet-enchants)       | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=HelmetEnchant   |
| [Unique Maps ](https://github.com/ayberkgezer/poe.ninja-API-Document#unique-maps)               | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueMap       |
| [Maps ](https://github.com/ayberkgezer/poe.ninja-API-Document#maps)                             | https://poe.ninja/api/data/itemoverview?type=Map&league=LEAGUE-NAME             |
| [Unique Jewels ](https://github.com/ayberkgezer/poe.ninja-API-Document#unique-jewels)           | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueJewel     |
| [Unique Flasks ](https://github.com/ayberkgezer/poe.ninja-API-Document#unique-flasks)           | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueFlask     |
| [Unique Weapons ](https://github.com/ayberkgezer/poe.ninja-API-Document#unique-weapons)         | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueWeapon    |
| [Unique Armours ](https://github.com/ayberkgezer/poe.ninja-API-Document#unique-armours)         | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueArmour    |
| [Unique Accessories ](https://github.com/ayberkgezer/poe.ninja-API-Document#unique-accessories) | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueAccessory |
| [Beasts ](https://github.com/ayberkgezer/poe.ninja-API-Document#Beasts)                         | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Beast           |

# Currency

- `https://poe.ninja/api/data/currencyoverview?league=LEAGUE-NAME&type=Currency`
- LEAGUE-NAME: `Write League Names`
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

# Fragment

- `https://poe.ninja/api/data/currencyoverview?league=LEAGUE-NAME&type=Fragment`
- LEAGUE-NAME: `Write League Names`
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

# Oils

- `https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Oil`
- LEAGUE-NAME: `Write League Names`
- `pay_currency_id - get_currency_id`: Oils Id
- `get_currency_id - pay_currency_id`: Chaos Id
- `detailsId`: Unique Name
- `icon`: Png Photo
- `chaosValue`: Chaos Value
- `exaltedValue`: Exalted Value
- `divineValue`: Divine Value
- `id`: Unique Item Id

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

# Incubators

# Scarabs

# Fossils

# Resonators

# Essences

# Divination Cards

# Prophecies

# Skill Gems

# Base Types

# Helmet Enchants

# Unique Maps

# Maps

# Unique Jewels

# Unique Flasks

# Unique Weapons

# Unique Armours

# Unique Accessories

# Beasts
