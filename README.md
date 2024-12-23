# Virginia Minni's website
## Install jekyll to create and run the project locally
This is the instruction: https://jekyllrb.com/docs/
## Create the website project and edit it
We often edit the md files to update information and sometimes edit main.css to change the layout.

### .md files
These files are the contents of each page, we have index.md, research.md, teaching.md, policy.md, which are corresponding to home page, research page, teaching page and policy page. <br>

**Links** <br>
For example (links opening **in the same tab**):
```
[Making the Invisible Hand Visible: Managers and the Allocation of Workers to Jobs](/assets/docs/Minni_JMP.pdf) <br>
November 2024, *Working Paper* | [[PDF](/assets/docs/Minni_JMP.pdf)] | [Supplementary Materials](/assets/docs/Minni_Managers_Supplementary.pdf)

*Revise and Resubmit*, **Quarterly Journal of Economics**
```
This is part of the research.md. <br>
`[name](path)`: when we want to link the paper to a file, we need to use this format `[name]` and its corresponding path `(###)`. Usually, we put the files in the folder /asset/docs/, but we can put them anywhere only if we change the corresponding path.

For example (links opening **in new tabs**):
```
<a href="/assets/files/Minni_JMP.pdf" target="_blank" rel="noopener noreferrer">Making the Invisible Hand Visible: Managers and the
Allocation of Workers to Jobs</a>
```
we need to change the path `href=""`, edit names and keep others unchanged.

**Abstract** <br>
For creating the bottom[abstract] :

```
 <a href="#" class="toggle-abstract" data-target="abstract-1" style="text-decoration: underline; color: #990000;">[Abstract]</a>

```
Corresponding abstract:

```
<div id="abstract-1" style="display: none; margin-top: 10px;">
 <em>Abstract:</em> Why do managers matter for firm performance? This paper provides evidence of the critical role of managers in matching workers to jobs within the firm using the universe of personnel records from a large multinational firm. The data covers 200,000 white-collar workers and 30,000 managers over 10 years in 100 countries. ....
</div>

```
we need use `<em>` to represent italic here, `<b>` for bold. The most important thing for each abstract is to create a unique data-target for the button and id for abstract (they should be the same), which cannot be repeated in the .md.

**Font** (for normal situations): 
Bold: `**text**` or`__text__` <br>
Italic: `*text*` or `_text_` <br>
Bold and Italic: `***text***` <br>
Strikethrough: `~~text~~`<br>

`<br>`: breaklines <br>
Once we **insert a link**, the names or titles will automatically be underlined and be red which I have set down in the main.css.

### main.css (assets/css/main.css)
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
It is the structure of the website, including scripts for phone version, for abstracts.

### _config.yml

It includes some settings.

### uchicagoicon
please check _layouts/default.html
`<!-- <link rel="icon" type="image/svg+xml" href="/assets/images/uchicago_shield.svg"> -->`  <br>
if we need change the blank icon to uchicago icon, please delete the comment symbols.  <br>
`<link rel="icon" type="image/svg+xml" href="/assets/images/uchicago_shield.svg"> `









