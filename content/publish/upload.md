---
section: Publish and Connect
nav_order: 1
title: Upload Your Spreadsheets
---

## Upload Your Transcript

##### Go to the `_data/transcripts/` directory: 

- Click on the `_data` folder, which will take you to a new page. 
- Then click into the `transcripts` folder. 

##### Drag your transcript(s) onto the webpage to upload them:

- Find the transcript spreadsheet/CSV file or files you created and downloaded in the [Prepare Your Data Section]({{ 'howto/prepareyourdata.html' | relative_url }}). 
    - Make sure the transcript CSV is titled something simple, and that it's all lowercase and has no spaces or special characters. E.G. `doe_john.csv` (And make sure it has a `.csv` extension!)
- Drag the file or files onto the web page -- the page will change when you drag it onto the webpage to say "Drop to Upload Your Files". Drop the file to upload it!
    - Alternatively, you can push the "Add File" dropdown button at the top right of your screen, and then select the file(s) you'd like to upload.

##### Commit your upload/changes to add the file(s):

- Once it's uploaded, you'll need to commit your change to make it permanent. Commit your upload at bottom of page by scrolling to the bottom of the page and clicking "commit new file". 
{% include bootstrap/figure.md img="howto/commit_file.png" caption="" alt="" class="w-50" %}
- Below is what the CSV should look like after you've committed it into your GitHub repository. 
{% include bootstrap/figure.md img="howto/github_csv.png" caption="This is how the CSV should look after you paste it into the new file and commit it." alt="complete and committed csv in github" class="w-50" %}


{:.alert .alert-warning .mb-4}
NOTE: If the CSV has a problem, GitHub will show you an error message that will say: "We can make this file beautiful and searchable if this error is corrected:" After that phrase, they will also point out a line number that is causing the problem. Open the file up by clicking on the pencil icon in the top right of the file area. Go to the line indicated and see if there's an obvious error. If you can't get it fixed, go back to your Google Sheet and see if there's anything to clean up. Even if there is nothing wrong, re-download the file as a CSV, rename it to the new title, then drag it back to the page as you did above. Hopefully one of these steps clears up the problem. 

