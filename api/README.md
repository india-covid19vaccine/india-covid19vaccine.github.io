# india-covid19vaccine

## Last updated data til 3rd May, 2021. No longer maintained.

**If you find it useful, please follow and star !**

**[@sanyam-git](https://github.com/sanyam-git)**

[View on Github](https://github.com/india-covid19vaccine/india-covid19vaccine.github.io)  

(see [documentation](#documentation) and download respective CSV data from [here](https://india-covid19vaccine.github.io/csv/))

#### National Level Data
|data|url|
|--|--|
|national_latest|[https://india-covid19vaccine.github.io/api/national_latest.json](national_latest.json)|
|national_timeline|[https://india-covid19vaccine.github.io/api/national_timeline.json](national_timeline.json)|
|state_latest|[https://india-covid19vaccine.github.io/api/state_latest.json](state_latest.json)|
|state_timeline|[https://india-covid19vaccine.github.io/api/state_timeline.json](state_timeline.json)|

#### State Level Data
|state/UT|state_code|url|
|--|--|--|
| A & N Islands        | AN         | [https://india-covid19vaccine.github.io/api/AN.json](AN.json) |
| Andhra Pradesh       | AP         | [https://india-covid19vaccine.github.io/api/AP.json](AP.json) |
| Arunachal Pradesh    | AR         | [https://india-covid19vaccine.github.io/api/AR.json](AR.json) |
| Assam                | AS         | [https://india-covid19vaccine.github.io/api/AS.json](AS.json) |
| Bihar                | BR         | [https://india-covid19vaccine.github.io/api/BR.json](BR.json) |
| Chandigarh           | CH         | [https://india-covid19vaccine.github.io/api/CH.json](CH.json) |
| Chhattisgarh         | CG         | [https://india-covid19vaccine.github.io/api/CG.json](CG.json) |
| Dadra & Nagar Haveli | DN         | [https://india-covid19vaccine.github.io/api/DN.json](DN.json) |
| Daman & Diu          | DD         | [https://india-covid19vaccine.github.io/api/DD.json](DD.json) |
| Delhi                | DL         | [https://india-covid19vaccine.github.io/api/DL.json](DL.json) |
| Goa                  | GA         | [https://india-covid19vaccine.github.io/api/GA.json](GA.json) |
| Gujarat              | GJ         | [https://india-covid19vaccine.github.io/api/GJ.json](GJ.json) |
| Haryana              | HR         | [https://india-covid19vaccine.github.io/api/HR.json](HR.json) |
| Himachal Pradesh     | HP         | [https://india-covid19vaccine.github.io/api/HP.json](HP.json) |
| Jammu & Kashmir      | JK         | [https://india-covid19vaccine.github.io/api/JK.json](JK.json) |
| Jharkhand            | JH         | [https://india-covid19vaccine.github.io/api/JH.json](JH.json) |
| Karnataka            | KA         | [https://india-covid19vaccine.github.io/api/KA.json](KA.json) |
| Kerala               | KL         | [https://india-covid19vaccine.github.io/api/KL.json](KL.json) |
| Ladakh               | LA         | [https://india-covid19vaccine.github.io/api/LA.json](LA.json) |
| Lakshadweep          | LD         | [https://india-covid19vaccine.github.io/api/LD.json](LD.json) |
| Madhya Pradesh       | MP         | [https://india-covid19vaccine.github.io/api/MP.json](MP.json) |
| Maharashtra          | MH         | [https://india-covid19vaccine.github.io/api/MH.json](MH.json) |
| Manipur              | MN         | [https://india-covid19vaccine.github.io/api/MN.json](MN.json) |
| Meghalaya            | ML         | [https://india-covid19vaccine.github.io/api/ML.json](ML.json) |
| Mizoram              | MZ         | [https://india-covid19vaccine.github.io/api/MZ.json](MZ.json) |
| Nagaland             | NL         | [https://india-covid19vaccine.github.io/api/NL.json](NL.json) |
| Odisha               | OD         | [https://india-covid19vaccine.github.io/api/OD.json](OD.json) |
| Puducherry           | PY         | [https://india-covid19vaccine.github.io/api/PY.json](PY.json) |
| Punjab               | PB         | [https://india-covid19vaccine.github.io/api/PB.json](PB.json) |
| Rajasthan            | RJ         | [https://india-covid19vaccine.github.io/api/RJ.json](RJ.json) |
| Sikkim               | SK         | [https://india-covid19vaccine.github.io/api/SK.json](SK.json) |
| Tamil Nadu           | TN         | [https://india-covid19vaccine.github.io/api/TN.json](TN.json) |
| Telangana            | TS         | [https://india-covid19vaccine.github.io/api/TS.json](TS.json) |
| Tripura              | TR         | [https://india-covid19vaccine.github.io/api/TR.json](TR.json) |
| Uttar Pradesh        | UP         | [https://india-covid19vaccine.github.io/api/UP.json](UP.json) |
| Uttarakhand          | UK         | [https://india-covid19vaccine.github.io/api/UK.json](UK.json) |
| West Bengal          | WB         | [https://india-covid19vaccine.github.io/api/WB.json](WB.json) |


## Documentation
#### Commonly used terms in data :
- `total_sessions` : total number of vaccination sessions conducted
- `total_doses` : total number of vaccination doses administered (currently India is administering two doses per person)
- `total_vaccinated` : total number of people who are given at least one dose of the vaccine
- `total_fully_vaccinated` : total number of people fully vaccinated/all doses given

#### [national_latest](national_latest.json)
Provides latest vaccination data at national level

#### [national_timeline](national_timeline.json)
Provides timeline of vaccination data at national level

#### [state_latest](state_latest.json)
Provides latest vaccination data at state level

#### [state_timeline](state_timeline.json)
Provides timeline of vaccination data at state level

#### statewise_data
Provides separate timeline data for each state.

syntax : `https://india-covid19vaccine.github.io/api/<state_code>.json`

ex :  https://india-covid19vaccine.github.io/api/RJ.json
