---
section_id: Customize Your Site
nav_order: 5
title: Create Interview Pages
topics: Front Matter; Navigation
---

## Creating a Markdown File

##### Go to the `_transcripts/` directory: 

- Navigate back to the root of your repository by clicking on `<> Code ` at the top left of the page.
- Click on the folder that says "_transcripts" 
{% include bootstrap/figure.md img="howto/transcripts.png" caption="" alt="_transcipts button" class="w-50" %}

##### Make a copy of one of the Markdown files in the directory: 

- Open up any of the .md file examples that are in this folder
- Navigate to the button that says "raw" and click it
{% include bootstrap/figure.md img="howto/raw.png" caption="" alt="raw file button" class="w-50" %}
- Copy the text inside of the file you opened
{% include bootstrap/figure.md img="howto/newcopyandpaste.png" caption="" alt="raw file text" class="w-50" %}

##### Create a new Markdown file for your transcript by pasting and then editing your copied text:  

- Go back to your _transcripts directory by clicking back two pages in your browser.
- Click the "Create New File" button
{% include bootstrap/figure.md img="howto/createnewmd.png" caption="" alt="create new file button" class="w-50" %}
- Name this file the same name you named your transcript file, but be sure to put `.md `rather than `.csv`, as it's extension.  

{% include bootstrap/figure.md img="howto/mdname.png" caption="" alt="name field in new markdown file" class="w-50" %}

{:.alert .alert-info .mb-4}
You are creating a markdown file; [more on Markdown here](https://www.markdownguide.org/). 
Jekyll uses the markdown file as the basis for creating web pages. All the information stored between the two `---` at the top and then down a bit is called frontmatter. This frontmatter is written in a language called YAML, which is a [a human-readable language for writing/storing data variables](https://en.wikipedia.org/wiki/YAML). (You'll work with some `.yml` files later as well)

- Paste the text you copied from the raw file you opened earlier into this new file.
{% include bootstrap/figure.md img="howto/beforemd1.png" caption="Pasted text before editing" alt="pasted text in new .md file" class="w-50" %}
- Edit the variables in the frontmatter between the `---` lines ) to fit your data -- be sure that the object-id option is the same as the filename (without the extension) of your transcript. 
{% include bootstrap/figure.md img="howto/aftermd2.png" caption="File after being edited for new file" alt="new .md file text after being edited for new file" class="w-50" %}

{:.alert .alert-warning .mb-4}
NOTE: if the "object-id" field is different than the name of your transcript CSV file in the _data/transcripts folder, the tool will not work. The transcript file will have an extension (.csv) but the object-id should not have an extension. So if the transcript is called `doe_john.csv`, then the object-id for the corresponding Markdown file should be `doe_john`.

##### Commit your changes:

- Write a commit message, briefly describing the changes you made and then commit them at the bottom.
- Once you are done, navigate to your new file, it should look like the example below
{% include bootstrap/figure.md img="howto/comletemd.png" caption="" alt="the newly created md file" class="w-50" %}

