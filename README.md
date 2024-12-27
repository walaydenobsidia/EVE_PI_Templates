## EVE PI Templates
Complete set of PI templates for EVE Online. The design strategy is to mine your P0 and tier it up to P1. Then take your P1 and ship it to P2/P3/P4 factories to efficiently produce PI with the least amount of headache as possible.

Screenshots from left to right. 

Miners + P1 Factories (All Planets), P2/P3 Factories (All Planets), P4 Factories (Barren/Temperate Planets)

<img src="https://github.com/user-attachments/assets/1e225447-8125-4815-b8f1-11bc87d1bdf2" width="250">
<img src="https://github.com/user-attachments/assets/cd8b122f-eea0-47b5-b0de-53dc8befa1f6" width="250">
<img src="https://github.com/user-attachments/assets/fca8822a-5f55-4399-8d7d-c728d10a63e8" width="250">

## Future Plans
1. 1 Extractor Mining Variant
2. P0 -> P2 Mining Variant

### How to use these templates.
1. Navigate to `/users/<user>/Documents/EVE/PlanetaryInteractionTemplates`
2. Unzip and paste all json files in the folder above.
3. Refresh your templates menu in game.

### Dependencies
1. Currently this feature is in beta and will need to be enabled in the `Feature Previews` ESC menu setting.

<img src="https://github.com/user-attachments/assets/119a17c1-eb65-4fde-9832-2f397eb53ad0" width="480">

### Skill Recommendations
| Skill Names | Miner | Factory |
|-|-|-|
| Command Center Upgrades | V | V |
| Interplanetary Consolidation | IV | V |
| Planetology | V | 0 |
| Advanced Planetology | IV | 0 |
| Total SP | 2,199,295 | 2,048,000 |

### Best Estimate Template PG and CPU Usage

| Level | CPU | PG |
|-|-|-|
| 0 | 1675 | 6000 |
| 1 | 7057 | 9000 |
| 2 | 12136 | 12000 |
| 3 | 17215 | 15000 |
| 4 | 21315 | 17000 |
| 5 | 25415 | 19000 |
<table>
<tr><th>Miner + P1 Template</th><th>7x Links</th></tr>
<tr>
<td>
  
| Structures | CPU | PG |
|-|-|-|
| Extractors | 800 | 5200 |
| Basic Reactors | 800 | 3200 |
| Storage | 500 | 700 |
| Starport | 3600 | 700 |
| Total | 5700 | 9800 |
| | | |
| | | |
| | | |
| CCU5 Remainder | 19715 | 9200 |
| Extractor Heads x1 | 110 | 550 |
| Extractor Heads x10 | 1100 | 5500 |
| Extractor Heads x12 | 1320 | 6600 |
| Extractor Heads x14 | 1540 | 7700 |
| Extractor Heads x16 | 1760 | 8800 |

</td>
<td>
  
| Radius | Link Length | CPU | PG |
|-|-|-|-|
|2500|31|149|103|
|5000|61|191|135|
|7500|91|233|166|
|10000|121|275|198|
|12500|151|317|229|
|15000|181|359|261|
|17500|211|401|292|
|20000|241|443|324|
|22500|271|485|355|
|25000|301|527|387|
|27500|331|569|418|
|30000|361|611|450|

</td></tr> </table>

*WARNING* Based on the numbers above, with CCU5, x16 Extractor heads, the mining template will be PG overloaded on planets larger than 15k. To use this template on larger planets or with CCU4, reduce your extractor head count.

<table>
<tr><th>P2/P3 Factory</th><th>1 Factory 12x Links</th><th>2 Factory 24x Links</th></tr>
<tr>
<td>
  
| Structures | CPU | PG |
|-|-|-|
| Adv. Factory x12 | 6000 | 8400 |
| Starport | 3600 | 700 |
| Total | 9600 | 9100 |
| CCU2 Remainder | 2536 | 2900 |
| CCU5 Remainder | 15815 | 9900 |

| Structures | CPU | PG |
|-|-|-|
| Adv. Factory x24 | 12000 | 16800 |
| Starport x2 | 5200 | 1400 |
| Total | 17200 | 18200 |
| CCU5 Remainder | 8215 | 800 |

</td>
<td>
  
| Radius | Length | CPU | PG |
|-|-|-|-|
|2500|31|255|176|
|5000|61|327|230|
|7500|91|399|284|
|10000|121|471|338|
|12500|151|543|392|
|15000|181|615|446|
|17500|211|687|500|
|20000|241|759|554|
|22500|271|831|608|
|25000|301|903|662|
|27500|331|975|716|
|30000|361|1047|770|

</td>
<td>
  
| Radius | Length | CPU | PG |
|-|-|-|-|
|2500|31|509|352|
|5000|61|653|460|
|7500|91|797|568|
|10000|121|941|676|
|12500|151|1085|784|
|15000|181|1229|892|
|17500|211|1373|1000|
|20000|241|1517|1108|
|22500|271|1661|1216|
|25000|301|1805|1324|
|27500|331|1949|1432|
|30000|361|2093|1540|

</td></tr> </table>

*WARNING* Based on the numbers above, with CCU5, 2 factories on 1 planet, your command center will be overloaded on planets with a radius large than 12,500 km. Remove factories to accommodate larger planets.

<table>
<tr><th>P4 Factory</th><th>1 Factory 8x Links</th><th>2 Factory 16x Links</th></tr>
<tr>
<td>
  
| Structures | CPU | PG |
|-|-|-|
| High-Tech Factory x8 | 8800 | 3200 |
| Starport | 3600 | 700 |
| Total | 12400 | 3900 |
| CCU3 Remainder | 4815 | 11100 |
| CCU5 Remainder | 13015 | 15100 |

| Structures | CPU | PG |
|-|-|-|
| High-Tech Factory x16 | 17600 | 6400 |
| Starport x2 | 5200 | 1400 |
| Total | 22800 | 7800 |
| CCU5 Remainder | 2615 | 11200 |

</td>
<td>
  
| Radius | Length | CPU | PG |
|-|-|-|-|
|2500|31|170|118|
|5000|61|218|154|
|7500|91|266|190|
|10000|121|314|226|
|12500|151|362|262|
|15000|181|410|298|
|17500|211|458|334|
|20000|241|506|370|
|22500|271|554|406|
|25000|301|602|442|
|27500|331|650|478|
|30000|361|698|514|

</td>
<td>
  
| Radius | Length | CPU | PG |
|-|-|-|-|
|2500|31|340|235|
|5000|61|436|307|
|7500|91|532|379|
|10000|121|628|451|
|12500|151|724|523|
|15000|181|820|595|
|17500|211|916|667|
|20000|241|1012|739|
|22500|271|1108|811|
|25000|301|1204|883|
|27500|331|1300|955|
|30000|361|1396|1027|

</td></tr> </table>

### Factory - Max Inputs
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
    <td>1,374 - P3, 9,160 - P1</td>
  </tr> 
</table>

### Factory - Max Ouputs
Once your factories are finished process your imports you will be left with these tiered up units.
<table>
  <tr>
    <th>P2 (2 inputs)</th>
    <th>P3 (2 inputs)</th>
    <th>P3 (3 inputs)</th>
    <th>P4 (3 inputs)</th>
    <th>P4 (3 inputs P3/P1)</th>
  </tr>
  <tr>
    <td>3,285</td>
    <td>1,998</td>
    <td>1,332</td>
    <td>185</td>
    <td>229</td>
  </tr> 
</table>

### FAQ/Troubleshooting
1. You will notice that the factories will be specified as Barren only. You can indeed use these on other planets, when you apply the template, the system will auto convert the factories to the planet specific types needed.
2. The json files are touchy and can be corrupted easily. Edit them at your own risk and make backups.
3. ALL templates will be available on ALL toons as long as they are in the folder above.
4. Yes all routes are configured. Drop your PI in the starport and your factories turn on. WOOT WOOT!
5. PI takes into account planet radius which effect link CPU/PG usage. View the tables I created above to get a best estimate of what your going to use on what size of planet.
6. P2/P3 factories can be used on any planet, Gas planets are not recommended due to their size, but it can be done in a pinch.
7. P4 factories can only be used on Barren and Temperate planets.
8. You can place 2 factories on each planet with CCU V.
9. If you would like to use these templates with lower CCU, you will need to edit the value `"CmdCtrLv": 5,` in the json to the CCU value of your toon. Save and refresh your templates in game and they will be updated.
10. When using the mining templates you will find that the routes out of the extractors to the storage unit are missing. The is expected behavior because of the way CCP designed the system. You will need to set your extractor heads and then create your P0 routes back to the storage unit. No other user intervention should be required. https://github.com/DalShooth/EVE_PI_Templates/issues/2
