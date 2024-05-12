# README - LaTeX Project - Basic

# What is this? 

This repo contains a template project for LaTeX along with a short guide on how to use LaTex for writing. The ZIP file available for download has a folder with a root tex file and a README folder with a guide on how to use the template and LaTeX in general. The README.pdf file walks through the contents of the tex files and what each bit of code does, as well as how to use the packages.

# What if I have suggestions / need help with something?

For questions regarding this project specifically or suggestions on things to include in the template/guide, you can create an issue on GitHub or email me at vmariani@udel.edu . 

For help with LaTeX in general or a specific package, I reccomend a few resources: 

1. LaTeX, along with many programming languages, has extensive tutorials and guides available online. Overleaf in particular has a lot of good resources on basic LaTeX usage which are usually pretty high in a google search.
2. Every package in LaTeX has documentation that comes with it - you can either google "latex [package name]" and look for the CTAN page for the package, or if you have TeXLive installed on your system you can put ```texdoc [package name]``` into your terminal to pull it up. Several packages also have various cheatsheets / short guides available online if you search for it. 
3. TeX Stack Exchange (https://tex.stackexchange.com/) is a forum where you can ask specific questions to more experienced users or browse previous questions that have been answered (which also usually are high up on a google search). If you do ask a question, be sure to include a "minimal working example" of the problem you're having, which is a block of code that at a minimum will reproduce the error you have.

For help with using LaTeX for linguistics, Pomona College Linguistics has a very good reference guide on Overleaf (https://www.overleaf.com/latex/templates/pomona-linguistics-quick-reference-guide/jthrqbrktmrd), and you can see the code alongside the guide itself. This project is meant to be a bit more brief that that one, but if something in there seems helpful let me know so I can include a similar bit in here. 

# Planned Revisions

1. Add a section on accessing documentation and help with LaTeX packages 
2. Add a section on instaling LaTeX or using OverLeaf
3. Add a link to Charis SIL (the font used in the document, which is designed to include the entire IPA and various orthographies)
   
     a. Link: https://software.sil.org/charis/download/
   
     b. I also reccomend installing "Charis SIL Compact" for use in Word and other programs - https://software.sil.org/lcgfonts/download/

4. Add a section on including graphics using ```graphicx```
5. Add more information that is specific to Linguistics:

     a. General

         1. Using the IPA

               i. Using ```fontspec``` (what's used in the template) - type IPA directly into the code, see https://vincentnmariani.com/wp-content/uploads/2023/09/typing-in-ipa-.pdf for how to type IPA symbols on your computer

               ii. Using ```tipa``` (older method) - use commands in LaTeX to input IPA glyphs

         2. Glossed examples with ```linguex``` or ```gb4e```

   
     a. Syntax / Morphology:
   
         1. Drawing trees with ```forest```

     b. Phonology / Phonetics

         1. Making vowel charts
   
         2. Creating tableaux with ```ot-tableau```

         3. Creating autosegmental diagrams with ```tikz``` (```tikz``` is an extremely powerful diagram drawing package for more than just this!)

     c. Semantics

         1. Creating formulae for formal semantics

   
