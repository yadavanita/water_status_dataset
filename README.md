# Repository
## Indian Surface Water quality dataset

Raw data of water quality index has been collected from the official website of [ENVIS](http://www.cpcbenvis.nic.in/water_quality_data.html#) Centre on Control of Pollution Water, Air and Noise, which is hosted by [Central Pollution Control Board](http://cpcb.nic.in/) and sponsored by [Ministry of Environment and Forest](http://moef.nic.in/), Govt. Of India.

Data contains the water quality of lakes, ponds and tanks (statewise) with various H2O parameters.

After collecting yearly data separately, formatting and clubbing has been done. There were so many missing records and  inconsistency. Hence, a lot of data cleaning has been done. After analyzing important factors responsible for algal presence, dataset is converted into desired format.

There are total 1473 rows. Each observation contains information on 26 variables.

Description of these 26 variables are as follow:
* code &nbsp; &nbsp; &nbsp;: station code of the location from where the data is collected.
* year &nbsp; &nbsp; &nbsp;        : year at which data is collected.
* tmin &nbsp; &nbsp; &nbsp;        : minimum temperature. 
* tmax &nbsp; &nbsp; &nbsp;        : maximum temperature.
* tmean &nbsp; &nbsp; &nbsp;       : mean temperature.
* domin &nbsp; &nbsp; &nbsp;       : min Dissolved oxygen (mg/l) (water quality criteria > 4 mg/l ).
* domax &nbsp; &nbsp; &nbsp;       : max Dissolved oxygen (mg/l) (water quality criteria > 4 mg/l ).
* domean &nbsp; &nbsp; &nbsp;      : mean Dissolved oxygen (mg/l) (water quality criteria > 4 mg/l ).
* bodmin &nbsp; &nbsp; &nbsp;      : min Biochemical Oxygen Demand (mg/l) (water quality criteria < 3 mg/l )
* bodmax &nbsp; &nbsp; &nbsp;      : max Biochemical Oxygen Demand (mg/l) (water quality criteria < 3 mg/l )
* bodmean &nbsp; &nbsp; &nbsp;      : mean Biochemical Oxygen Demand (mg/l)(water quality criteria < 3 mg/l )    
* phmin &nbsp; &nbsp; &nbsp;       : min ph value of surface water.
* phmax &nbsp; &nbsp; &nbsp;      : min ph value of surface water.
* phmean &nbsp; &nbsp; &nbsp;       : min ph value of surface water.
* cmin &nbsp; &nbsp; &nbsp;        : min conductivity of surface water (µmhos/cm).
* cmax &nbsp; &nbsp; &nbsp;        : min conductivity of surface water (µmhos/cm).
* cmean &nbsp; &nbsp; &nbsp;       : min conductivity of surface water (µmhos/cm).
* nmin  &nbsp; &nbsp; &nbsp;       : min nitrate-n + nitrite-n (mg/l)
* nmax &nbsp; &nbsp; &nbsp;        : max nitrate-n + nitrite-n (mg/l)
* nmean &nbsp; &nbsp; &nbsp;       : mean nitrate-n + nitrite-n (mg/l)
* fcmin &nbsp; &nbsp; &nbsp;       : min fecal coliform (MPN/100ml) (water quality criteria < 2500 MPN/100ml )
* fcmax &nbsp; &nbsp; &nbsp;       : max fecal coliform (MPN/100ml) (water quality criteria < 2500 MPN/100ml  )
* fcmean &nbsp; &nbsp; &nbsp;      : mean fecal coliform (MPN/100ml)(water quality criteria < 2500 MPN/100ml  )
* tcmin &nbsp; &nbsp; &nbsp;       : min total coliform (MPN/100ml) (water quality criteria > 5000 MPN/100ml )
* tcmax &nbsp; &nbsp; &nbsp;       : max total coliform (MPN/100ml) (water quality criteria > 5000 MPN/100ml  )
* tcmean &nbsp; &nbsp; &nbsp;      : mean total coliform (MPN/100ml)(water quality criteria > 5000 MPN/100ml  )
