# Data Sources for FC Barcelona Performance & Financial Analysis

## Performance Statistics (La Liga & Champions League)

- Description: Season-Level stats to show performance trends over the years including Goals-For, Goals-Against, Rank/ Stage Reached, xG, xGA,...
- Source: [FBref](https://fbref.com/en/squads/206d90db/Barcelona-Stats)
- Method: Simple scraping method in pandas "read_html()" to get table(s) from websites that have static HTML tables

## Transfer spending

- Description: Season-by-season transfer expenditures in 10 years
- Sources: [TransferMarkt](https://www.transfermarkt.us/fc-barcelona/alletransfers/verein/131)
- Method: Compiled manually from TransferMarkt reports, and cleaned data in Excel

## Salary Cap / Squad Cost Limit

- Description: Annual squad cost limit comparison between FC Barcelona and Real Madrid in La Liga
- Sources: [La Liga](https://www.laliga.com/en-GB/transparency/economic-management/squad-cost-limit)
- Method: Compiled manually from La Liga Official Reports, and cleaned data in Excel
