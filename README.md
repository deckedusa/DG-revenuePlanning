# DG-revenuePlanning

Code used to:
1) generate daily pacing of the revenue planning
2) writing the result to the DW

If planned revenue changed:
1) Note: version 1 (= $110M) and 2 (=$120M)
2) drop data from the warehouse for the dates planned revenue changed (table ANALYST.temp.planned_rev_pacing_2)
3) rerun the notebook

How to run:
1) fill out revenue planning here: https://docs.google.com/spreadsheets/d/1jkSOgczjP2O4gYKI6P8iw0SDmxMzOGpl98_9IW0tZkg/edit#gid=0
2) Run the fivetran connector: google_sheets.revenue_planning
3) change parameters in notebook accordingly
4) run the notebook
