# Sea Urchin is a Beloved Sushi Topping in Japan. Find Out the Best State to Try it in the U.S.
The article is [here](https://naokatoh.github.io/sea_urchin/)

## Overview
![(ウニ)すし](https://cdn.emojidex.com/emoji/seal/(ウニ)すし.png "(ウニ)すし")


**??What's sea urchin = uni??**  
- Sea urchin, or *uni* (pronounce ooo-nie) is popular sushi topping in Japan. 
- I saw some restaurants in NYC serves uni *nigiri* but little I knew about uni in the US.
- In this project, I analyzed the sea urchin landings in the US and found that California produces the most sea urchins.
- Looking closed the Californian data, I realized that the landings decreased dramatically due to ocean environment change, which was resulted from climate change.
- Ironically, because of the decline of the edible sea urchin population, non-edible purple sea urchins flourished in the Californian Coast. 

## What I did with which skill
- Python (BeautifulSoup, Selenium, pandas, ggplot) :for data analysis
- datawrapper :for data viz

- **Thing that I tried and feel satisfied**: Finding relevant datasets what I looked for😊 Datawrapper skills and data biz😊 Feel more confident using html/css😊
- **Thing that I tried but couldn't complete**: I found Japan Aerospace Exploration Agency’s Earth observation satellite database and succeeded to downloading sea surface temperatures rise images in the California Coast [G\-PortalTop](https://gportal.jaxa.jp/gpr/) but found it extremely difficult to dealing with .h5 file to adapt them on the shapefile 😥 (I tried to create a map with QGIS)


## Files
- ```urchin_state_dw.xlsx```is a table I used to make the first chart in the [article](https://naokatoh.github.io/sea_urchin/).
- See complete file at ```uni_state.csv```
- ```uni_price.csv``` is a table I used to make the second chart in the [article](https://naokatoh.github.io/sea_urchin/).
- ```uchin_landing_us.ipynb```here I analyzed the landing data from [NOAA Database](https://www.fisheries.noaa.gov/foss/f?p=215:200:17118210909997:Mail:NO:::) and other sourceses
- ```uni_price.ipynb``` here I analyzed the landing and ex-vessel price data from [Red Sea Urchin Enhanced Status Report 2.The Fishery](https://marinespecies.wildlife.ca.gov/red-sea-urchin/the-fishery/) by scraping the website to get a table. 

## Reference
- [NOAA Database](https://www.fisheries.noaa.gov/foss/f?p=215:200:17118210909997:Mail:NO:::)  
- [Red Sea Urchin Enhanced Status Report 1.The Species](https://marinespecies.wildlife.ca.gov/red-sea-urchin/the-species/)  
- [Red Sea Urchin Enhanced Status Report 2.The Fishery](https://marinespecies.wildlife.ca.gov/red-sea-urchin/the-fishery/)  
- [The collapse of Northern California kelp forests will be hard to reverse](https://news.ucsc.edu/2021/03/kelp-forests-norcal.html)  
- [California Sea Urchin Are Destroying Coastal Kelp Forests \- The New York Times](https://www.nytimes.com/2021/10/04/dining/california-sea-urchin-kelp-coastline.html)  
- [Sushi Ishikawa](https://www.ishikawanyc.com/) :I have never tried this sushi restaurantbut but looks super authentic and utterly beautiful🥰  


## Licence

MIT

## Author

[Nao Hidaka Kato](https://github.com/naokatoh)
