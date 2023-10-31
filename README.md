**Camera trap data from northwest Arkansas**

Data Description

This data set contains wildlife detections from game cameras at 103 different residential study sites in Northwest Arkansas. Each row represents a wildlife detection on motion-triggered game camera.

**Yard:** Each time a camera was deployed in the field, it was given a unique ID number.”.

**Date of Detection**: The date the camera detected this particular wildlife occurrence. 

**Time of Detection**: The time that the camera detected this particular wildlife occurrence. 

**Species Detected**: The species that was present in the photo. 

**Number of Species Detected in the Photo**: How many of that particular species were present in the photo.

**Sunset Time:** Time of sunset for that day and location, calculated in R via suncalc package: Thieurmel B, Elmarhraoui A (2022), \_suncalc: Compute Sun Position, Sunlight Phases, Moon Position and Lunar Phase\_. R package version 0.5.1, <https://CRAN.R-project.org/package=suncalc>

**Sunrise Time:** Time of sunrise, similar to that above.

**Number of Bird Feeders:** Number of any type of bird feeders in a yard (i.e. seed feeders, hummingbird feeders, dried fruit).

**Area of Garden (m^2):** Area of all maintained garden areas, in m2.

**Fence Type:** If a camera was within a fence, it was given a score between 1-4, 1 being the least restrictive to wildlife passage and 4 being the most. 0: Not in a fence, 1: Barbed wire, 2: Open slat fence, 3: 4ft Chain-link or Privacy, 4: 6ft Chain-link or Privacy

**Poultry Presence:** Presence (1) or absence (0) of purposefully kept poultry in a yard.

**Relative Abundance of Dogs:** Number of domestic dogs detected divided by trap nights.

**Relative Abundance of Predators:** Number of bobcats, coyotes, red and gray foxes detected at a camera site divided by the number of trap nights.

**Forest Cover Within 400m of camera (km^2):**  We used ArcGIS to create 400m radius buffers around each camera and then measured the total amount of forest cover within each buffer based on National Land Cover Database (Dewitz, J., 2019, National Land Cover Database (NLCD) 2016 Products: U.S. Geological Survey data release, <https://doi.org/10.5066/P96HHBIE>.)

**Open Land Cover within 400m of camera (km^2):** Similar to above, but area of open land, land used for parks, cemeteries, and lawn space, within 400 m buffer**.**

**Agricultural Land Cover within 400m of camera** (km2): Similar to amount of forest, but area of land used for agricultural purposes within 400 m buffer.

**Developed Land Cover within 400m of camera** (km2**):** Similar to amount of forest, but area of developed land within 400 m buffer.

**Maximum Housing Unit Density within a 400m buffer (Houses/**km2**):** Using the SILVIS Housing Data Layer (Hammer, R. B., Stewart, S. I., Winkler, R. L., Radeloff, V. C., & Voss, P. R. (2004). Characterizing dynamic spatial and temporal residential density patterns from 1940–1990 across the North Central United States. *Landscape and Urban Planning*, *69*(2-3), 183–199. <https://doi.org/10.1016/j.landurbplan.2003.08.011>) we calculated the number of housing units within the 400m buffer around the camera.

**Year:** Year that the camera was active in the specific yard.

**Simpson Diversity:** Simpson diversity calculated for each yard, including all wild mammalian species. Simpson diveristy index calculated to range from 0-1 where 1 is the most diverse and 0 is the least diverse.

**Richness:** Richness calculated for each yard, including all wild mammalian species.

**Mesopredator Richness:** Richness calculated for each yard, including all mesopredator mammalian species.

**Mesopredator Diversity:** Simpson diversity calculated for each yard, including all mesopredator mammalian species.

**Herbivore Richness:** Richness calculated for each yard, including all herbivore mammalian species.

**Herbivore Diversity:** Simpson diversity calculated for each yard, including all herbivore mammalian species.

**Forest Cover Within 1.5km of camera (**km2**):**  We used ArcGIS to create 400m radius buffers around each camera and then measured the total amount of forest cover within each buffer based on National Land Cover Database (Dewitz, J., 2019, National Land Cover Database (NLCD) 2016 Products: U.S. Geological Survey data release, <https://doi.org/10.5066/P96HHBIE>.)

**Open Land Cover within 1.5km of camera (**km2**):** Similar to above, but area of open land, land used for parks, cemeteries, and lawn space, within 1.5km buffer**.**

**Agricultural Land Cover within 1.5km of camera (**km2**):** Similar to amount of forest, but area of land used for agricultural purposes within 1.5km buffer.

**Developed Land Cover within 1.5km of camera (**km2**) (High and Medium):** Similar to amount of forest, but area of developed land within 1.5km buffer. High and medium represent the combination of the high and medium categories given in the NLCD layer, these were combined to represent 50-100% cover.

**Developed Land Cover within 1.5km of camera (**km2**) (Low):** Similar to amount of forest, but area of developed land within 1.5km buffer. Low represents the category given in the NLCD layer, this layer represents 20-49% cover.

**Number of Water Sources:** Number of supplemental water sources provided in a yard, this includes any water source that was actively maintained by the homeowners.

**Area of Potential Den Sites (**m2**):** Area under sheds or outbuildings and under decks less than 1m off the ground.

**Volume of Brush Piles (**m3**):** Volume of brush piles in residential yards.

**Volume of Firewood Piles (**m3**):** Volume of firewood piles in residential yards.

**Area of Compost Piles (**m2**):** Area of compost pile within residential yards.

**Temperature # (**℉)**:** All columns labeled with “Temperature” followed by a number 1-15, represents the average temperature (℉) over a 7- day period, this data was gathered from publicly available data from a NOAA weather station located at the Fayetteville Experimental Station (<https://www.noaa.gov/climate>). Week one includes May1-May 7 and the rest of the weeks follow consecutively. 

**Precipitation # (in):** All columns labeled with “Precipitation” followed by a number 1-15, represents the average precipitation (inches) over a 7- day period, this data was gathered from publicly available data from a NOAA weather station located at the Fayetteville Experimental Station (<https://www.noaa.gov/climate>). Week one includes May1-May 7 and the rest of the weeks follow consecutively. 

**Usage Note:**

All data from Year to Precipitation was added into the second version of the data.
