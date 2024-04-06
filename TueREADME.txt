Thank you for using my template! Read through this file to get started and optimize your usage of this template.

This template was created with DBLs and CLBs on the TU/e in mind. It can be adopted to work for any course or project, but specific care was put in creating this template in accordance with the writing manual of 20 march 2018 that is used for DBL projects (as of 2022). This manual (and thus template) may now be outdated, so always check possible changes.

The template consists of a few files that attempt to create a organised and beautiful report while maintaining user-friendly.

First, the 'main.tex' loads in all the .tex files for the preamble, title page and different sections. It is also responsible for adding a ToC, bibliography and appendices. 

Secondly, in the 'General' folder you can add packages to the 'Preamble.tex' and add references in the 'References.bib' files.
The 'Settings.tex' file contains all the predefined formatting, so if anything is not to your liking it can be changed here. Most importantly, here you can edit the title, subtitle and authors among other things for the front page.
An attempt was made to make this as user-friendly as possible, and comments are used to explain everything, but a decent understanding of LaTeX is advised if you desire to change anything. In this file a comment can be found stating that the code after a certain line is not essential. One could remove all the code from there onward to (pretty much) revert to default LaTeX behaviour.

Next, in the chapters folder a .tex file can be found for each chapter. These are numbered so they remain in the same order for easier navigation. To add a chapter, simply add a .tex file and name it 'x. <title>.tex' where x is the chapter number (for chapters) or letter (for appendices) and <title> any name you like. Don't forget to also add the chapter in the 'main.tex' file using

\input{Chapters/x. <title>.tex}
\newpage

A few chapters are already predefined based on the writing manual. There is a front page, list of symbols, introduction and appendix entry template. Other chapters can also be added by copying and renaming the '2. Copy me.tex' file. Finally, the 'Z. Template.tex' contains inspiration for formatting tables, images, text citations etc. It also functions to preview the template. Feel free to use it as a reference or delete it. 

Finally, in the 'Figures' folder you can put figures for use in the report. Make sure to always reference to figures using \includegraphics{Figures/x. <title>/figurename} where 'x. <title>' is the subfolder the image is located in. The '0. General' folder contains figures used for creating the template. Moving or removing this folder is not recommended. 

I hope you find this template useful.
Happy writing!