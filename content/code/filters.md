---
section: Code and Download
nav_order: 2
title: Create the Filters
topics: Content; Markdown
---


## Step 5: Create Your Filters.CSV (optional)

The filters.csv file will communicate with the tags you enter into the the `tags` field of your transcript's CSV to create the tool's color-coded visualizations (seen below). 

{:.clearfix}
{% include bootstrap/figure.md img="howto/wrigley-viz.png" caption="Picture of visualization created through filters.csv" alt="A visualization of Robert Wrigley's transcript, as enabled by the Filters.CSV" class="border-0 w-50" link="/oral-history-as-data/subjects.html?id=wrigley" %}


- Open this blank [spreadsheet](https://docs.google.com/spreadsheets/d/1qPU-7LFZrIWcLiHuTqnlbnRD1869SJalJ5OCL7tGtzE/edit#gid=0){:target="_blank"}. 
- Click the "file" icon and choose "make a copy." 
- In the "tag" column write out the tags you wish to include in the transcript.
- In the "description" column write out a brief description of that tag. 
- When you're finished create a new .csv by clicking on the "file" icon, hovering above "download", and selecting "comma-separated values". 
- Rename this file: `filters.csv` and upload it into your GitHub repository's `_data` folder. (Instructions in our next step.)
    - Note that you will want to continue to edit this file as you add more transcripts and more codes 