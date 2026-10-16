## Klindi Karaj · Junior Python developer, Padova

I build backend web apps in Python. My main project, DataScrub, is a SaaS I built and deployed by myself: it cleans messy CSV files for virtual assistants and e-commerce teams.

**Open to junior developer roles**, remote or in Veneto.\
Contact: karaj.klindi@gmail.com

### DataScrub

Takes a messy CSV export and returns a clean file. Live, in beta.

- FastAPI and pandas backend with 150+ automated tests
- 5 cleaning profiles, a free tier up to 1,000 rows, and a Pro plan with Stripe Checkout and webhooks
- Stateless: the app keeps no copy of uploaded files
- I chose to leave phone numbers without a country code unchanged and flag them in a `phone_status` column. Guessing the country would corrupt international lists.

[Live app](https://datascrub.up.railway.app/)

### OddsLab

Compares bookmaker odds with Poisson and Elo models and flags the odds that look mispriced. School capstone, finished in 2026.

- Python engine that pulls data from 4 external APIs, a 10-table MySQL schema, and a PHP dashboard with Chart.js
- I added fuzzy matching on team names, so results from football-data.org and balldontlie.io attach to the right game

[Code](https://github.com/klindikaraj/OddsLab)

**Stack:** Python, FastAPI, pandas, pytest, SQL/MySQL, PHP, JavaScript, HTML/CSS, Git\
**Also used:** Java, Stripe API, Railway, Cisco networking\
**Education:** Technical high school diploma in Computer Science & Telecommunications, ITI F. Severi, Padova (2026)\
**Spoken languages:** Italian (native), English (B2)
