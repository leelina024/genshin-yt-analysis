## **Genshin Impact YouTube Scrape Analysis**
Using Selenium to scrape Genshin Impacts EN [YouTube channel](https://www.youtube.com/c/GenshinImpact "Genshin Impact's YouTube channel").

Obtained title, view count, duration (seconds), and approximate date posted for every video posted on their channel.

Cleaned and analyzed to find trends/patterns with viewships and duration. 

![Example](https://i.imgur.com/C2gWUop.png)

`As of 2022-06-02 21:08:17 Thursday`

------------


### Cleaning Data
|Column|Cleaning Done|
|-----------|--------|
|Views | • Removed "views" <br> • Converted to integer |
|Upload Date|• Used datetime <br>• Subtracted time from today |
|Duration| • hh:mm:ss format <br>• Converted to seconds only|

------------
### Visualizing Data
Used Tableau.

|Table|Attributes|
|-----------|--------|
|Special Program| • Special Program <br>• Viewership |
|Version Trailer|• Version Trailer <br>• Viewership |
|Character Teaser| • Character Teaser/Tale <br>• Viewership|
|Character Demo| • Character Demo <br>• Viewership|
|OSTs/Albums| • OSTs/Abums/EP <br>• Viewership|

