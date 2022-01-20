# Scolopax Minor Migration Data Visualization
This was a just-for-fun project to visualize the migration patterns of the American Woodcock (Scolopax Minor) as collected via satellite telemetry in a four year study by Joseph Moore at the University of Arkansas (references below).  I've always found wildlife migrations interesting.  Migrations happen each year all over the world, not just the Maasai Mara or the Serengeti.  In fact, there is a good chance one goes through your back yard!

The repository contains the data wrangling and data visualization notebooks.  I found the imageio package in python particularly useful for time series data visualization - it can do the heavy computational lifting when matplotlib animations fall short.


https://user-images.githubusercontent.com/75851788/150395419-adbe5629-0253-43aa-94db-18942b768b7b.mp4

The visualization shows short summer/winter trips as well as spring/fall migration routes and stop over points.  Interpolation over large gaps in data are likely due to poor satellite signal caused by a dense forest canopy.  Stationary observations near the end of the study show where birds reached some unknown fate.

## References
Moore JD, Andersen DE, Cooper TR, Duguay JP, Oldenburger SL, Stewart CA, Krementz DG. 2021. Data from: Migration phenology and patterns of American woodcock in central North America derived using satellite telemetry. Movebank Data Repository. https://doi.org/10.5441/001/1.8764q39q

Moore JD, Andersen DE, Cooper T, Duguay JP, Oldenburger SL, Stewart CA, Krementz DG. 2021. Migration phenology and patterns of American woodcock in central North America derived using satellite telemetry. Wildlife Biol. 2021(1):wlb.00816. https://doi.org/10.2981/wlb.00816

Moore JD, Andersen DE, Cooper TR, Duguay JP, Oldenburger SL, Stewart CA, Krementz DG. 2019. Migratory connectivity of American woodcock derived using satellite telemetry. J Wildlife Manage. 83(7):1617-1627. https://doi.org/10.1002/jwmg.21741

Moore JD, Cooper TR, Rau R, Andersen DE, Duguay JP, Stewart CA, Krementz DG. 2019. Assessment of the American woodcock singing-ground survey zone timing and coverage. Proceedings of the Eleventh American Woodcock Symposium 11. 181-192. https://doi.org/10.24926/AWS.0124
