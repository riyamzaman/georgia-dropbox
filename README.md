# 2020 Georgia Election Drop Box Distribution Explorer
This visualization was created to explore whether election drop box distribution had an impact on voter turnout in Georgia's 2020 general election. A custom Georgia tileset was built using QGIS and Mapbox. The map is rendered with Mapbox GL JS.

A look at the dashboard:

![alt text](https://i.ibb.co/TK06pVT/ga-drop-box-preview.png)

If you hover over a county, you can view the following turnout and drop box information:
- Turnout percentage (out of total registered voters)
- Total number of ballots cast
- Total number of registered voters
- Total number of registered voters that did not vote (non-voters)
- Drop box count
- Average number of registered voters per drop box
- Difference between the number of non-voters and average number of registered voters per drop box. (This metric was included to see the degree of an excess number of non-voters even if an additional drop box in the county were to be added.)

![alt text](https://i.ibb.co/K2jsCwz/Screenshot-1.png)

You can also click on each yellow dot, which represents a drop box location, to learn about what its hours and notes/restrictions were (if available).

![alt text](https://i.ibb.co/Mg0Cckc/drop-box-preview.png)

Note: These are drop boxes that were active for Georgia's 2020 general election in November. The additional drop boxes that have been since added for the January 2021 runoff election are not included.

Sources:
- https://faq.georgiavoter.guide/en/article/absentee-ballot-drop-box-locations
- https://results.enr.clarityelections.com/GA/105369/web.264614/#/access-to-races
