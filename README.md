# Virginia Minni's website
## Install jekyll to create and run the project locally
This is the instruction: https://jekyllrb.com/docs/
## Create the website project and edit it
We often edit the md files to update information and sometimes edit main.css to change the layout.

### .md files
These files are the contents of each page, we have index.md, research.md, teaching.md, policy.md, which are corresponding to home page, research page, teaching page and policy page. <br>
For example:
```
[Making the Invisible Hand Visible: Managers and the Allocation of Workers to Jobs](/assets/docs/Minni_JMP.pdf) <br>
November 2024, *Working Paper* | [[PDF](/assets/docs/Minni_JMP.pdf)] | [Supplementary Materials](/assets/docs/Minni_Managers_Supplementary.pdf)

*Revise and Resubmit*, **Quarterly Journal of Economics**
```
This is part of the research.md. <br>
`[name](path)`: when we want to link the paper to a file, we need to use this format `[name]` and its corresponding path `(###)`. Usually, we put the files in the folder /asset/docs/, but we can put them anywhere only if we change the corresponding path.

Bold: `**text**` or`__text__` <br>
Italic: `*text*` or `_text_` <br>
Bold and Italic: `***text***` <br>
Strikethrough: `~~text~~`<br>

`<br>`: breaklines

### main.css 
This file contains all the styling. This is a tutorial website: https://developer.mozilla.org/en-US/docs/Learn/CSS
For example: 
```
/* General body styling */
body {
    font-family: 'Spectral', serif; 
    line-height: 1.7; /* Adjust for readability */
    margin: 0;
    padding: 0;
    color: #000; /* Text color */
    background-color: #ffffff; /* Background color */
  }
```

we can set the font here, 'Spectral' is a google font, so I added its link in the default.html.
We can change the margin, color and any other related functions here. The tutorial website is great for learning to how to edit layout because it shows us the potential styles if choosing different number or type.

### default.html
It is the structure of the website.

### _config.yml

It includes some settings.






