# CJS_Project
This project contains scrapers for pending murder cases from Indian courts' website, data gathered for five districts in a span of three days in the first week of December 2022, and analysis of that data.

### Inside *District wise scrapers* folder:
- Scrapers written using Playwright (mostly) for pending murder cases from courts of five different districts in Maharashtra state of India. 
- The data on the website gets updated every single day.
- The data was scraped within a span of three days in the first week of December 2022.

### Inside *original scrapes* folder:
- A folder named after each district. 
- Some districts have multiple district-level courts operating inside its limit.
- Therefore, each folder contains files of every district-level court in the district that folder is named after.
- The subfolder named *JOINED_FILES* contains consolidated data of all disitrict-level courts in that district.
- You are free to either used the original files or use the consolidated files.
