# nhs-hospital-admissions
Number of admissions to non-psychiatric/non-obstetric hospitals in Edinburgh.

Statistics provided by NHS Information Services Division:  http://statistics.gov.scot/data/hospital-admissions

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/nhs-hospital-admissions.git
```

Install npm dependencies

```
cd nhs-hospital-admissions
npm install
```

Run the API (from the nhs-hospital-admissions directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
