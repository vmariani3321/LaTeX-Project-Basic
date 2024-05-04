# README - LaTeX Project - Basic

# What is this? 
This repo contains a template project for LaTeX along with a short guide on how to use LaTex for writing. The ZIP file available for download has a folder with a root tex file and a README folder with a guide on how to use the template and LaTeX in general. The README.pdf file walks through the contents of the tex files and what each bit of code does, as well as how to use the packages.

# Planned Revisions

1. Add a section on accessing documentation and help with LaTeX packages (Tip: You can google any package, i.e. "latex package forest" and go to the CTAN page to access documentation. If you have TeXLive installed, you can also go to the terminal and use ``` texdoc [package name] ``` to pull it up.)
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

   
