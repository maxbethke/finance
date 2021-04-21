# finance

I started this project to get a grip on my personal finances and be better organised with it.
Since no one did what I wanted, I wrote a program for it myself.
In Web-Development I had the most skin, so I ended up realizing my ideas with a website.
This site could read .CSVs from my bank, link those transactions to categories according to preset keywords in the paymemt details and generate a detailed financial statement as PDF.
I used to print this every month and tweak my expenses on that. It was really helpful.
The problem was, that it was really tideous to log into every bank, download a CSV for every account. Also the links were not always made.
This lead me to stop using and developing it further.

In the following I want to gather ideas for future development.

## Requirements

* User can create categories in a tree structure
  * categories can have infinite children
* User can match keywords to categories
* User can import a .CSV file with transactions
  * lines can be excluded
  * columns can be macthed to datafields
    * this configuration can be saved and reused, as its not gonna sta the same for each bank
  * trancactions get matched to categories based on keywords
* A report can be generated based on a variable timeframe
  * the report shows all categories that had movement in that timeframe
  * it shows the sum of the movements
  * it shows a total sum
* a visualization of the cashflow can be generated for a variable timeframe (sankey diagram)

## Resources
https://github.com/d3/d3-sankey : Use to generate a sankey diagram to visualize cashflow
