## EVE PI Templates
Complete set of PI templates for EVE Online. The design strategy is to mine your P0 and tier it up to P1. Then take your P1 and ship it to P2/P3/P4 factories to efficiently produce PI with the least amount of headache as possible.

Screenshots from left to right. 

Miners + P1 Factories (All Planets), P2/P3 Factories (All Planets), P4 Factories (Barren/Temperate Planets)

<img src="https://github.com/user-attachments/assets/1e225447-8125-4815-b8f1-11bc87d1bdf2" width="250">
<img src="https://github.com/user-attachments/assets/cd8b122f-eea0-47b5-b0de-53dc8befa1f6" width="250">
<img src="https://github.com/user-attachments/assets/fca8822a-5f55-4399-8d7d-c728d10a63e8" width="250">

### Dependencies
1. Currently this feature is in beta and will need to be enabled in the `Feature Previews` ESC menu setting.

<img src="https://github.com/user-attachments/assets/119a17c1-eb65-4fde-9832-2f397eb53ad0" width="480">

### Skill Requirements
... in development, coming soon TM ...

### Template PG and CPU Usage
<table>
<tr><th>Command Center Capacity </th><th>Miner Template</th><th>7x Links</th></tr>
<tr>
<td>

| Level | CPU | PG |
|-|-|-|
| 0 | 1675 | 6000 |
| 1 | 7057 | 9000 |
| 2 | 12136 | 12000 |
| 3 | 17215 | 15000 |
| 4 | 21315 | 17000 |
| 5 | 25415 | 19000 |

</td>
<td>

| Structures | CPU | PG |
|-|-|-|
| Extractors | 800 | 5200 |
| Basic Reactors | 800 | 3200 |
| Storage | 500 | 700 |
| Starport | 3600 | 700 |
| Total | 5700 | 9800 |
| | | |
| L5 Remainder | 19715 | 9200 |
| Extractor Heads x1 | 110 | 550 |
| Extractor Heads x10 | 1100 | 5500 |
| Extractor Heads x12 | 1320 | 6600 |
| Extractor Heads x14 | 1540 | 7700 |
| Extractor Heads x16 | 1760 | 8800 |

</td>
<td>

| Radius | Link Length | CPU | PG |
|-|-|-|-|
| 2500 | 31 | 105 | 154 |
| 5000 | 61 | 140 | 196 |
| 7500 | 91 | 168 | 238 |
| 10000 | 121 | 203 | 280 |
| 12500 | 151 | 231 | 322 |
| 15000 | 181 | 266 | 364 |
| 17500 | 211 | 294 | 406 |
| 20000 | 241 | 329 | 448 |
| 22500 | 271 | 357 | 490 |
| 25000 | 301 | 392 | 532 |
| 27500 | 331 | 420 | 574 |
| 30000 | 361 | 455 | 616 |

</td></tr> </table>

### Factory Starport Max Inputs
The inputs below will allow you to max fill your starports, and when finished there will be no left overs.
<table>
  <tr>
    <th>P2 (2 inputs)</th>
    <th>P3 (2 inputs)</th>
    <th>P3 (3 inputs)</th>
    <th>P4 (3 inputs)</th>
    <th>P4 (3 inputs P3/P1)</th>
  </tr>
  <tr>
    <td>26,280 - P1</td>
    <td>6,660 - P2</td>
    <td>4,440 - P2</td>
    <td>1,110 - P3</td>
    <td>1,110 - P3, 17,520 - P1</td>
  </tr> 
</table>


### How to use these templates.
1. Navigate to `/users/<user>/Documents/EVE/PlanetaryInteractionTemplates`
2. Unzip and paste all json files in the folder above.
3. Refresh your templates menu in game.

### FAQ/Troubleshooting
1. You will notice that the factories will be specified as Barren only. You can indeed use these on other planets, when you apply the template, the system will auto convert the factories to the planet specific types needed.
2. The json files are touchy and can be corrupted easily. Edit them at your own risk and make backups.
3. ALL templates will be available on ALL toons as long as they are in the folder above.
4. Yes all routes are configured. Setup your extractor heads and hit start, drop your PI in the starport and your factories turn on. WOOT WOOT!
5. PI takes into account planet radius. These templates were made at a specific radius. I have not tested these on different sizes. However, if you run into power issues on your miners, reduce the amount of extractor heads you are using.
6. P2/P3 factories can be used on any planet, Gas planets are not recommended due to their size, but it can be done in a pinch.
7. P4 factories can only be used on Barren and Temperate planets.
