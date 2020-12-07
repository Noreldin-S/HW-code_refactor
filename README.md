Description of my work


Link:
https://noreldin-s.github.io/HW-code_refactor/

Header:

HTML sheet:
In line #10 I wrote “Horisean” in title.
In line #15 I changed div for header for semantic HTML elements.
In line #20 I changed div to nav. Nav: is and element represents a section pf a page that links to another page.

CSS Sheet:
In all headers I replaced “.Header” with “Header”, Since I Changed in HTML sheet “div” to “Header” and removed Class=”Header”.
In line # 37 and # 41, I changed div to nav, to match the HTML sheet.



Main:

HTML sheet:
In line #38 I Added “main” instead of “div”, for the paragraph’s sections. Main: represents the main content of the body.
For each paragraph in lines #42, #49, and #56 I added a section for each. Section: thematic grouping of content. Each section is identified by an id.
For each image I also added an alt to describe what the image is about
I Also changed the class to “Main-image” since they all have the same details

CSS sheet:
Since I changed all classes “Main-image” in HTML sheet, no need to have them 3 times in CSS, so I deleted them and kept only 1 to simplify the CSS sheet from unnecessary lines. Lines #115, #125, and #130.



Aside:

HTML sheet:
I added in line #66 Aside instead of div. Aside: represents a section of a page that consists of content that is tangentially related to the content around the aside element. 
In aside since Class=”benefits”  there is no need to specify each benefit with a different class name, since they all will have the  same CSS details. In Lines #69, #76, and #83. This will also, simplify the CSS from unnecessary lines. Like I did in Main

CSS sheet:
Since I changed in HTML sheet all classes “benefits-lead”, “benefits-brand”, and “benefits-cost” to just “benefits”. I no longer needs in CSS sheet a line with details for each one so I deleted the extra ones and just kept 1 of them. Lines #97, #102, and #108.



Footer:

HTML sheet:
No need to have a “div” with  Class:”Footer”, I can simply replace “div” with “Footer”. Line #91

CSS sheet:
I applied the same change in CSS to match the HTML. Since footer is no longer a class, I changed “.footer” to just  “footer”. Line#136, and #143.

<img src=“screenshot/Screenshot_2020-12-06_184752.png” width="700" height=“500”>