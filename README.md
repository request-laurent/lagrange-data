# The Infinite Lagrange data collection

This project aims to put all the data from the Infinite Lagrange game into a structured file. This data can be used to automate a wiki or to make applications.

This project took a lot of time, please mention the source of the data if you use it.

If you find any problems or missing things, please use the issues section

Available resources objects :
- [Ship](#ship).
- [Systems](#systems).

## Ship

| Attribute                | Type     | Description                                |
|:-------------------------|:---------|:-------------------------------------------|
| `id`                     | integer  |  Unique ship ID                            |
| `aircraftGroupNum`       | integer  |  Number of aircraft in the group           |
| `capacity`               | integer  |  Transport capacity                        |
| `commandPoint`           | integer  |  Command Point                             |
| `company`                | i18n     |  Company                            |
| `crystal`                | integer  |  Crystal cost                              |
| `description`            | i18n     |  Description                        |
| `deuterium`              | integer  |  Deuterium cost                            |
| `history`                | i18n     |  History                            |
| `hp`                     | integer  |  Ship HP                                   |
| `image`                  | string   |  Image name                                |
| `maxShip`                | integer  |  Maximum number of ships that can be built |
| `metal`                  | integer  |  Metal cost                                |
| `moribound`              | number   |  Percentage of returns to base once destroyed |
| `name`                   | i18n     |  Full name                          |
| `proverbe`               | i18n     |  Proverbe                           |
| `rating`                 | array    |  Array of rating (Anti ship, Anti aircraft, Siege, Support, Survivability, Strategic) |
| `row`                    | string   |  Row position                              |
| `shipTypeName`           | i18n     |  Ship type                                 |
| `shortName`              | i18n     |  Short name                                |
| `size`                   | integer  |  Size                                      |
| `speed`                  | integer  |  Speed                                     |
| `systems`                | array    |  Array of [Systems](#systems)                          |
| `timeCost`               | integer  |  Construction time in seconds              |
| `typeName`               | i18n     |  Variante type name                        |
| `variante`               | string   |  Variante code                             |

## Systems

| Attribute                | Type     | Description                                |
|:-------------------------|:---------|:-------------------------------------------|
