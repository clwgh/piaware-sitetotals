# piaware-sitetotals
Extract Aircraft Reported and Positions Reported totals from a FlightAware stats URL

Bash script which takes a FlightAware stats URL in the form `https://uk.flightaware.com/adsb/stats/user/username#stats-nnnnnn` and extracts the **Totals** for the **Aircraft Reported** and **Positions Reported** from the rolling 31-day stats tables shown.

Enter the site stats URL in the correct format where indicated in the script. Note that the full site URL should include any country-specific subdomain, eg `uk.flightaware.com`.

These numbers can be used for further scripting.

![AircraftReported](https://github.com/clwgh/piaware-sitetotals/assets/115202757/2fa5ed34-676e-4ed0-8a2d-c633ce9ca48b)
![PositionsReported](https://github.com/clwgh/piaware-sitetotals/assets/115202757/ccd641a9-5023-466a-b9ab-910d943a91d3)

```
$ ./sitetotals 
Getting totals for Site nnnnnn
Aircraft reported: 128 1481 1446 1549 1626 1465 1431 1435 1399 1425 1584 1568 1537 1443 1451 1452 1412 1577 1560 1539 1606 1494 1554 1534 1622 1583 1527 1421 1485 1420 1477
Positions reported: 10680 263651 269503 293014 294414 263112 253775 254256 247161 258050 290318 300565 275459 262911 258642 260305 241720 284723 282449 289531 269129 260909 281058 275313 290715 292221 293727 270390 259290 271587 262885
```
