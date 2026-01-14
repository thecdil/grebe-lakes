# grebe-lakes project

The website data was original derived from Anne Yen's research spreadsheet "2023_grebes_lit_review_table_WORKING_MASTER.xlsx".
This data was refined and broken into component parts to drive the website features.
The contents are described in the "grebe_project-data-dictionary.xlsx".

There is three main tables:

- "grebe-lake-table.csv" - each row represents one lake, containing its identifiers, location, characteristics, and summary statistics. Each lake has a unique id "lakeid" used to connect related records.
- "grebe-surveys-table.csv" - each row represents one survey. It is connected to one or more lakes using the "lakeid" key. 
- "grebe-lake-sources.csv" - each row represents one source of information. It is connected to one or more lakes using the "lakeid" key.

When the website builds, each row in the grebe-lake-table will become an web page.
Using the lakeid, it will pull in information from grebe-surveys-table and grebe-lake-sources to display on the page (along with information contained in the row for the lake). 
This is controlled by the "_layouts/item/lake.html" template.
Other pages from the site pull data from the grebe-lake-table to generate visualizations and browsing options.
