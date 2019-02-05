# Gearset-Challenge
## ASSUMPTIONS
- At the beginning of the document there is always a title followed by a line break to separate it from the text. <br /> <br />
- I assume that the font in italics can not go before or after a text in bold since the combination of the two does not exist in the code. However, it could be implemented by creating a new font with "Font.BOLDITALIC". <br /> <br />
- Prior to the paragraph creation statement, there may or may not be another instruction to determine the font of the new paragraph.
The typography, the margins of the document and the line spacing of the paragraphs have been determined from checking the similarity with the example provided by Gearset. <br /> <br />
- I assume that before and after indenting a text, a line break is added. When changing the indentation a second time in a paragraph, I assume that a new one is created with the counter indentation when adding the new value entered in the input. <br /> <br />
- In the instruction ".nofill" I have decided to add the paragraph to the document and to reset its information and content since, by default, the paragraph is ".nofill" and if the instruction is called, this is because “.fill” has been called previously. Therefore, we must add that justified text and start a new one that is not justified. 
## HOW TO RUN IT
- To test the project, you must add the folder called Gearset-Challenge-master in the C: directory. <br /> <br />
- The input file should have this path: C:\Gearset-Challenge-master\input.txt 
## THINGS TO IMPROVE
- I would like to implement the indentation function in another way with less code or using other structures from the iTextSharp libraries that I do not know quite well. <br /> <br />
- Moreover, I think that creating the functions of the instructions separately is a good idea, but I would also like to do it in a more compact way.
