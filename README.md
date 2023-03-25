# poe.ninja API

Hi! I compiled **poe.ninja API** to use in projects

| Category | API |
| --------- | ------ |
| Currency | https://poe.ninja/api/data/currencyoverview?league=LEAGUE-NAME&type=Currency |
| Fragment | https://poe.ninja/api/data/currencyoverview?league=LEAGUE-NAME&type=Fragment |
| Oils | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Oil |
| Incubators | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Incubator |
| Scarabs | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Scarab |
| Fossils | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Fossil |
| Resonators | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Resonator |
| Essence | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Essence |
| Divination Cards | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=DivinationCard |
| Prophecies | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Prophecy |
| Skill Gems | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=SkillGem |
| Base Types | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=BaseType |
| Helmet Enchants | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=HelmetEnchant |
| Unique Maps | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueMap |
| Maps | https://poe.ninja/api/data/itemoverview?type=Map&league=LEAGUE-NAME |
| Unique Jewels | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueJewel |
| Unique Flasks | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueFlask |
| Unique Weapons | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueWeapon |
| Unique Armours | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueArmour |
| Unique Accessories | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=UniqueAccessory |
| Beasts | https://poe.ninja/api/data/itemoverview?league=LEAGUE-NAME&type=Beast |

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
    "paySparkLine": {{"data": [],"totalChange": 42.25},},
    "receiveSparkLine": {"data": [],"totalChange": -3.92},
    "chaosEquivalent": 143915.04,
    "lowConfidencePaySparkLine": {{"data": [],"totalChange": 42.25},},
    "lowConfidenceReceiveSparkLine": {{"data": [],"totalChange": -3.92},},
    "detailsId": "mirror-of-kalandra"},
],
"currencyDetails": [
    {"id": 22,
    "icon": "https://web.poecdn.com/gen/image/WzI1LDE0LHsiZiI6IjJESXRlbXMvQ3VycmVuY3kvQ3VycmVuY3lEdXBsaWNhdGUiLCJ3IjoxLCJoIjoxLCJzY2FsZSI6MX1d/7111e35254/CurrencyDuplicate.png",
    "name": "Mirror of Kalandra",
    "tradeId": "mirror"},
]
```
