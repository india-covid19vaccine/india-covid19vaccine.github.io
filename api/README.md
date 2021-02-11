# india-covid19vaccine
### (Contribute to the [project](https://github.com/india-covid19vaccine/india-covid19vaccine.github.io) !)

Tracking the COVID-19 vaccination details PAN India (all of the data is collected from official government websites and other reliable sources, which are mentioned in the data itself)

API endpoints that returns data in JSON format :

|data|url|
|--|--|
|national|[https://india-covid19vaccine.github.io/api/national.json](national.json)|
|national_timeline|[https://india-covid19vaccine.github.io/api/national_timeline.json](national_timeline.json)|
|state|[https://india-covid19vaccine.github.io/api/state.json](state.json)|
|state_timeline|[https://india-covid19vaccine.github.io/api/<state_code>.json](#statetimeline)|

Download respective CSV data [here](https://india-covid19vaccine.github.io/csv/).

## Documentation
### national
Provides latest vaccination data at national level

    [
      {
        "total_sessions":36572,
        "total":2029480,
        "population":1371360350,
        "last_updated":"0800, 27/1/2021",
        "ref":"https://pib.gov.in/PressReleasePage.aspx?PRID=1692596"
      }
    ]

### national_timeline
Provides timeline of vaccination data at national level

    [
      {
        "date":"25/1/2021",
        "sessions":7764,
        "total_sessions":36378,
        "count":408305,
        "total":2023809,
        "ref":"https://pib.gov.in/PressReleasePage.aspx?PRID=1692463"
      },
      {
        "date":"26/1/2021",
        "sessions":194,
        "total_sessions":36572,
        "count":5671,
        "total":2029480,
        "ref":"https://pib.gov.in/PressReleasePage.aspx?PRID=1692596"
      }
    ]

### state
Provides latest vaccination data at state level

    [
      {
        "state":"A & N Islands",
        "state_code":"AN",
        "vaccinated":2369,
        "population":417036,
        "last_updated":"0800, 27/1/2021",
        "ref":"https://pib.gov.in/PressReleasePage.aspx?PRID=1692596"
      },
      {
        "state":"Andhra Pradesh",
        "state_code":"AP",
        "vaccinated":156129,
        "population":53903393,
        "last_updated":"0800, 27/1/2021",
        "ref":"https://pib.gov.in/PressReleasePage.aspx?PRID=1692596"
      }
    ]

   
### state_timeline
Provides timeline of vaccination data separately at state level

|state|state_code|url|
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

