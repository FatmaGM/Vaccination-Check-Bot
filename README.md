# Vaccine-Bot
A minimal python bot that interface with MOH Website -below- to collect Vaccination Status.
https://covid19.moh.gov.om/#/check-certificate

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)



## Table of Contents

- [Background](#background)
- [Technical Breif](#technical-brief)
- [Usage](#usage)
- [Resources](#Resources)
- [License](#license)

## Background

From the first of Septemper 2021, the Supreme COVID Commite passed regulation prohibiting the entry  to any public venue or workplaces wihout proof of COVID Vaccination. Corporate and government institutes are mandated to check the vaccine status of thier employees and visitors alike, before they are allowed to enter workplace.

This utility is made to help organization on collecting Vaccinatino Status details including: Number Doses, Type of Vaccine, Location and the date where it was taken. The takes a batch of civil ids from CSV file and pass to MOH website to collect the vaccine details.

## Technical Breif
This code base is built using Node.js and will require node and npm to be avaible on your machine. The script uses Puppeteer to control a headless browser instance to fetch the required data. 

## Usage
1. Clone this repo to your machine.

```sh
 git clone https://github.com/FatmaGM/Vaccination-Check-Bot.git 
```
2. cd into the cloned dirctory:

```sh
cd Vaccination-Check-Bot
```
## License

[MIT](LICENSE) © Fatma Bait Ishaq
{"mode":"full","isActive":false}
