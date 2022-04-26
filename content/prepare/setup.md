---
section: Prepare Your Transcript
nav_order: 1
title: Transform Your Transcript Into a Google Sheet
topics: GitHub; Optional Software
---

- [Paste Your Transcript Into Google Sheets](#sheets)
- [Separate the Cells](#cells)


{:.pt-4 .mt-4 #sheets}
***

## Step 3: Paste Your Transcript Into Google Sheets

- Create a new Google Sheet

- In the first row, title four columns `timestamp`, `speaker`, `words`, and `tags`

- In a new browser tab, open your transcript as a Google Doc

- Copy all of the text of the transcript (leave out any biographical information at the beginning)

- Switch back to the Google Sheet you created

- Click on the cell underneath `speaker` 

- Click on `Edit` > `Paste Special` > `Paste Values Only`

{% include figure.html img="/prep/transcript1.png" caption="Edit > Paste Special > Paste Values Only" alt="a screenshot of pasting text in google sheets" width="100%" %}

- This should paste all the transcript text into the rows of the second column

- **Note**: Your transcript rows should ***not*** have a space between them. If you *do* have spaces between your rows, see below.

{% capture spacing %}
### Removing Spacing Between Rows

If the text you paste into your Google Sheet looks like this...

{% include figure.html img="/prep/transcript15.png" caption="Transcript With Spaces" alt="a screenshot showing how to edit a markdown file on GitHub" width="100%" %}

...you need to remove the space between paragraphs in your Google Doc. Follow the steps below:

{:.pt-3}
- Return to the Google Doc version of your transcript

{:.pt-1}
- Select all of the transcript text

{:.pt-1}
- In the top right of the screen, look for the `line spacing` button (three horizontal lines next to a vertical arrow). In the dropdown options, click on `Custom spacing`.

{% include figure.html img="/prep/transcript16.png" caption="Line Spacing" alt="a screenshot showing how to edit a markdown file on GitHub" width="100%" %}

- A `Custom spacing` popup will appear. Make sure the text boxes to the right of `Before` and `After` have values of `0`. Click `Apply`:

{% include figure.html img="/prep/transcript17.png" caption="Custom spacing" alt="a screenshot showing how to edit a markdown file on GitHub" width="100%" %}

- Now follow the steps above to copy and paste this text into your Google Sheet

{% endcapture %}
{% include bootstrap/alert.md text=spacing color="warning" %}

{:.pt-4 .mt-4 #cells}
***

## Separate Your Cells

{:.pt-4}
### Add a Separator
{:.pb-3}

- Open Find and Replace: 

    - Press `ctrl` + `f` (on PC) or `cmd` + `f` (on Mac)

    - A search box should appear in the top right of your screen. Click on the `More options` button to the right of the search box (three vertical dots). A box labeled `Find and replace` will appear in the middle of your screen.
    
{% include figure.html img="/prep/transcript19.png" caption="More options" alt="a screenshot of pasting text in google sheets" width="75%" %}

{:.pt-2}
- In the `Find` box, enter the initials of the first speaker (ex. `RS`)

- In the `Replace` box, enter the initials of the first speaker, plus an asterisk (`*`) (ex. `RS*`)

{% include figure.html img="/prep/transcript20.png" caption="Find and Replace" alt="a screenshot of pasting text in google sheets" width="75%" %}

- Click the `Replace all` button. Then click `Done`

- Repeat the steps above for the initials of the second speaker and the speakers' full names

- Your spreadsheet should now look like this:

{% include figure.html img="/prep/transcript18.png" caption="Add a Separator" alt="a screenshot of pasting text in google sheets" width="100%" %}

{:.pt-4}
### Separate
{:.pb-3}

- If they aren't selected already, select the cells you just pasted, so that your sheet looks like this:

{% include figure.html img="/prep/transcript21.png" caption="Select Cells" alt="a screenshot of pasting text in google sheets" width="100%" %}

- Click on `Data` > `Split Text to Columns`

{% include figure.html img="/prep/transcript22.png" caption="Data > Split Text to Columns" alt="a screenshot of pasting text in google sheets" width="100%" %}

- A little box labeled `Separator:` will appear near the bottom of your screen. Click on the arrows to the right of `Detect Automatically`

{% include figure.html img="/prep/transcript23.png" caption="Separator" alt="a screenshot of pasting text in google sheets" width="100%" %}

- Select `Custom` from the list of choices that appears.

- A box should appear labeled `Custom separator`

- Enter an **asterisk (`*`) followed by a space (` `)** into this box.

{:.alert .alert-danger .text-center .mx-5}
Make sure **your asterisk is followed by a space**! Otherwise your transcript might not work right for the website.

{% include figure.html img="/prep/transcript24.png" caption="Enter an asterisk (*) followed by a space ( )" alt="a screenshot of pasting text in google sheets" width="100%" %}

- The text should separate into a new column automatically:

{% include figure.html img="/prep/transcript25.png" caption="Separated Text" alt="a screenshot of pasting text in google sheets" width="100%" %}




