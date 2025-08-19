# Using FIA Survey Data to Track Changes in Island-wide Tree Populations

I attempted to estimate changes in island-wide populations of *Cocos nucifera* and *Cycas micronesica* between the two FIA survey reports currently available. My results are shown in the two figures below.

After generating these figures, it became obvious that I needed to look at the raw data instead of the crunched data in the survey reports. Then I remembered that I had already done change analysis with FIA data several years ago.
Code and data are in [this GitHub repository](https://github.com/aubreymoore/SQLite-database-for-Guam-Forest-Inventory) and results are shown in Figure 3, below.

My analysis only 3 significant changes were detected:
* *Cycas circinalis* significantly decreased
* *Hibiscus tiliaceus* significantly increased
* *Vitex parviflora* significantly increased

## Notes

The cycads observed on Guam were actually *Cycas micronesica*, not *C. circinalis*.

It appears that the FIA sampling scheme, when applied to Guam, results in sample sizes too small to measure changes such as high mortality of coconut palms from an island-wide coconut rhinoceros beetle infestation and high mortality of *Neisosperma oppositifolia* (=*Ochrosia oppositifolia*)  which were killed by a fungus.
These die-offs occuerred between 2002 and 2013 and were obvious to anyone working in Guam's forests.

In addition, a ten-year sampling frequency is too long to adequately monitor rapid changes occurring in Guam's forests.

![](../images/coconut_palm_population_guam.png)

Figure 1. Island-wide population estimates for coconut palm on Guam estimated by the US Forest Service from Forest Inventory Assessment surveys performed in 2002 and 2013.
Note that different metrics were used in the two surveys.
The 2002 estimate comes from Donnegon et al. 2004, page 16, Table 5: Estimated number of live trees on forest land by species and diameter class. They reported a total of 1,162,494 live coconut palms growing on forest land on Guam during 2002.
The 2013 estimate comes from Lazaro et al. 2020, page 7, Tabel 2: Estimated number of trees on Guam, by species. They simply reported their estimate of the total number of coconut palms on Guam during 2013 as 1,464,000 with a sampling error of 528,000.

![](../images/coconut_palm_population_guam.png)

Figure 2. Island-wide population estimates for *Cycas micronesica* on Guam estimated by the US Forest Service from Forest Inventory Assessment surveys performed in 2002 and 2013.
Note that different metrics were used in the two surveys.
The 2002 estimate comes from Donnegon et al. 2004, page 16, Table 5: Estimated number of live trees on forest land by species and diameter class. They reported a total of 1,571,556 live *Cycas micronesica* plamts growing on forest land on Guam during 2002.
The 2013 estimate comes from Lazaro et al. 2020, page 7, Tabel 2: Estimated number of trees on Guam, by species. They simply reported their estimate of the total number of *Cycas circinalis* on Guam during 2013 as 624,000 with a sampling error of 242,000. I assume that *C. circinalis* is used in error and that it should be *C. micronesica*.

![](https://github.com/aubreymoore/SQLite-database-for-Guam-Forest-Inventory/blob/master/change_analysis.png)

Figure 3. Changes in island-wide tree population estimates between 2002 and 2013 using USFS FIA data for Guam.
The analysis detected significant changes in population for only 3 species. 
