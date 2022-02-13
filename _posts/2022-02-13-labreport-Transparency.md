Lab 3: We Persist
=================

## Regular Expressions ##

_The input regular expression is before the --> the subsition follows --> The edited text._

1) (;) --> , --> The Epoch Times, New York ed., New York (NY)
"La Voz Bilingüe", Denver, Colo.
Jewish Advocate, Boston
Washington Informer, Washington, [D.C.]
News from Indian Country, Hayward, WI.?
Afro - American, 5 Star edition, Baltimore, Md.
Diverse Issues in Higher Education, Fairfax Virginia
The Gay &amp, Lesbian Review Worldwide, Boston, MA
"The Hispanic Outlook in Higher Education, [Paramus N.J

2) (") --> --> The Epoch Times, New York ed., New York (NY)
La Voz Bilingüe, Denver, Colo.
Jewish Advocate, Boston
Washington Informer, Washington, [D.C.]
News from Indian Country, Hayward, WI.?
Afro - American, 5 Star edition, Baltimore, Md.
Diverse Issues in Higher Education, Fairfax Virginia
The Gay &amp, Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, [Paramus N.J

3) ([?[()&.]) --> -->The Epoch Times, New York ed, New York NY
La Voz Bilingüe, Denver, Colo
Jewish Advocate, Boston
Washington Informer, Washington, DC]
News from Indian Country, Hayward, WI
Afro - American, 5 Star edition, Baltimore, Md
Diverse Issues in Higher Education, Fairfax Virginia
The Gay amp, Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

4) (, New York ed,) --> -->The Epoch Times, New York NY
La Voz Bilingüe, Denver, Colo
Jewish Advocate, Boston
Washington Informer, Washington, DC]
News from Indian Country, Hayward, WI
Afro - American, 5 Star edition, Baltimore, Md
Diverse Issues in Higher Education, Fairfax Virginia
The Gay amp, Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

5) (Colo) --> CO -->The Epoch Times, New York NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston
Washington Informer, Washington, DC]
News from Indian Country, Hayward, WI
Afro - American, 5 Star edition, Baltimore, Md
Diverse Issues in Higher Education, Fairfax Virginia
The Gay amp, Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

6)(DC]) --> DC --> The Epoch Times, New York NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro - American, 5 Star edition, Baltimore, Md
Diverse Issues in Higher Education, Fairfax Virginia
The Gay amp, Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

7) (Md) --> MD -->The Epoch Times, New York NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro - American, 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax Virginia
The Gay amp, Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

8)(Virginia) --> VA --> The Epoch Times, New York NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro - American, 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax VA
The Gay amp, Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

(9) (amp,) --> and --> The Epoch Times, New York NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro - American, 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax VA
The Gay and Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

10) ( - ) --> - -->The Epoch Times, New York NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro-American, 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax VA
The Gay and Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

11) (k N) --> k, N -->The Epoch Times, New York, NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro-American, 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax VA
The Gay and Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

12) (x V) --> x, V --> The Epoch Times, New York, NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro-American, 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax, VA
The Gay and Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

13)(s N) --> s, N -->The Epoch Times, New York, NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro-American, 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax, VA
The Gay and Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus, NJ

14)(n, 5) --> (n 5)The Epoch Times, New York, NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro-American 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax, VA
The Gay and Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

15) (n\n) --> n, MA\n The Epoch Times, New York, NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston, MA
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro-American, 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax, VA
The Gay and Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

16) (s NJ) --> s, NJ --> The Epoch Times, New York, NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston, MA
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro-American, 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax, VA
The Gay and Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus, NJ

17) (n, 5) --> n 5 -->The Epoch Times, New York, NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston, MA
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro-American 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax, VA
The Gay and Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus NJ

18) (s N) --> s, N --> The Epoch Times, New York, NY
La Voz Bilingüe, Denver, CO
Jewish Advocate, Boston, MA
Washington Informer, Washington, DC
News from Indian Country, Hayward, WI
Afro-American 5 Star edition, Baltimore, MD
Diverse Issues in Higher Education, Fairfax, VA
The Gay and Lesbian Review Worldwide, Boston, MA
The Hispanic Outlook in Higher Education, Paramus, NJ
 
19) (, ) --> , --> The Epoch Times,New York,NY
La Voz Bilingüe,Denver,CO
Jewish Advocate,Boston,MA
Washington Informer,Washington,DC
News from Indian Country,Hayward,WI
Afro-American 5 Star edition,Baltimore,MD
Diverse Issues in Higher Education,Fairfax,VA
The Gay and Lesbian Review Worldwide,Boston,MA
The Hispanic Outlook in Higher Education,Paramus,NJ


## Reflection ##

# Seeing the Relation Between Text, Human, and Machine with Transparency #

I found playing with Regular Expressions to be incredibly fruitful! Solving this complex problem was almost fun to me. It forced me to take a closer look at the text in question and find similarities. Through "cleaning" this data, I was able to ask questions about the dataset. For instance, I noticed that most of these publications took place on the upper East Coast in the United States. Is this a publishing hub or a mere coincidence? While the data cleaning was laborious, as many of the readings for this week intimate--I began to understand how data cleaning creates durability for future researchers. This data set, now as a csv file, is more accessible to scholars, and much of the original sentiment remains intact. During this process, I felt much like the researchers for _What's on the Menu?_:I wanted to begin "processing enough values quickly enough to 'get on with it'" (Rawson and Munoz).

Aside from my eagerness to data clean, our discussion of OCR in class caused me to slow down and truly reflect about the relation between text, human, and machine. Recently, I have been tracing a new and pressing keyword for me throughout Digital Humanities thinking: _transparency_. Thankfully, through open access projects such as the Babysitter’s Project, among others, we are able to see transparency in the way that data is processed and presented to us. 

I’m interested in the way that I can promote an ethos of transparency in my own Digital Humanities data collection and collaborations to create more meaningful and lasting knowledge production. In Ryan Cordell’s “Why You (A Humanist) Should Care About Optical Character Recognition,” I felt called out and excited in his call to action for interdisciplinary collaboration to improve OCR technology. Near the end of his 2019 piece, he writes: “There is enormous potential in OCR research for meaningful important collaboration across a range of fields but particularly across the humanities, libraries, and computer science. For me this is the central reason humanists should care about OCR: not to bemoan its current state, but to help imagine its future” (Cordell). To be able to contribute to the future of a growing field in a meaningful way excites me. I feel privileged to collaborate at the intersection between cutting edge digital humanities, historical Early Modern texts, to create afterlives of texts and tools, however that may be imagined—with transparency.

Katie Rawson and Trevor Muñoz, “Against Cleaning,” from _Debates in the Digital Humanities_ 2019 (2019)

Ryan Cordell, “Why You...Should Care About OCR” (Jan 19, 2019)

