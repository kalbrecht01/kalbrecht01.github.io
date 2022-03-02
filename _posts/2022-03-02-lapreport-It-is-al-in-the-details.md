It is all in the Details!
=========================

## Personal Reflection ##

_This lab was a little frustrating for me, simply because the long string of python intimidated me. I kept putting it off because of this anxiety. However, once I got the courage up to tackle it, it was a lot easier than I had expected--very much like a language *translation* excercise--or a language *transformation* excercise._

1) As we discussed in class, the function is not quite perfect because it splits up the contraction "let's" into two separately defined words. From the r package documentation "**\W** Matches any character which is not a word character." Therefore, the function is asking it to split everywhere there is not a alphabetic character. This is why it splits "let's" on the apostrophe, interpreting that this is significant punctuation delineating words, like the other commas we see in this text. From what I can gather about the function of **+** it seems to imply repetition of some sort. It seems to indicate what follows the **\W** character, repeated. For instance of I had: _,hello_ the **\W** indicates (identify the alphabetic character after the comma) and the **+** indicates (keep repeating, continue looking for alphabetic characters). _This is my best hypothesis, but I may have missed the mark._

2) Yes, the function worked as expected. ['be', 'not', 'afeard', 'the', 'isle', 'is', 'full', 'of', 'noises', 'sounds', 'a  nd', 'sweet', 'airs', 'that', 'give', 'delight', 'and', 'hurt', 'not', ''] Here is the beginning of Caliban's speech to Stephano and Trinculo in _The Tempest_. I simulate the line break that came out in the Jypter notebook, but I later realized that everything worked well. The double '' at the end perhaps is because the sentence ends in a period and the function is trying to capture the space after the period. I would like to call this my _ghost word_--which is very _Hamlet_esk. I would like to know more about my _ghost word_ in the future!

3) The output of this script is a sample of the corpus in this study--10 eebo texts from the "eebo-test" value that have been analyzed and organized according to the larger python code, analyzed for _virtu_ versus _vertu_ counts and organized in a table to show these comparative counts along with metadata about author, publication date, xml file name and date.

4) So honestly, I had a hard time figuring this question out, so I turned to RegEx to help me out. The best that I can understand is that this function is trying to filter out the *20*s in the date sequence, or at least any dates after 2000. Perhaps this is intended to eliminate <date> tags the a TEI encoder may have written into the TEI files here in the last 22 years. In theory, this would help the function narrow on actual publication dates rather than encoding dates.
![image](https://user-images.githubusercontent.com/98132386/156391225-7b67edd9-f329-4746-82e0-f0e3f616a8e4.png)

## Translation and Transformation ##
  
To return to my earlier reflection on the relation between *translation* and *transformation*, I am interested in our conversation about how to make coding accessible for a broad range of reasearch in different disciplines from the humanities to social sciences. As I have gotten deeper into the depth of the Digital Humanities, I sometimes which that I had a computer science background--which perhaps comes out of anxieties about the academic job market.  Benjamin Schmidt in his work, "Do Digital Humanities Need to Understand Algorithims?" writes, "Put, simply: digital humanists do not need to understand algorithms _at all._ They do need, however, to understand the transformations that algorithms attempt to bring about" (Schmidt). According to Schmidt and to my own exploration through this lab, I don't have to be an expert at regular expressions or at Python to answer my research questions. 
And these research questions don't have to exist in isolation--they are transferable to the undergraduate classroom (which I hope to eventually be my professional home).

This week, I taught Jessica Rosenburg's chapter "Poetic Language, Practical Handbooks, and the 'vertues' of Plants" in my ENG 106 course "Humans and Nature: An Alliance." Rosenburg writes, "vertue plays a key role in drawing and ultimately undermining the fraught boundary between art and nature" (61). I'm interested in this idea of a blurry or fraught boundary between not only "art" and "nature" but also between the "humanities" and "computer science." Can we learn something from vertue as we blur these boundaries. My students certainly appreciated seeing the graph created by this project and interogating the etymology of the word virtue. Perhaps the *translations* or *transformations* that DH offers can simply be communicating what literary scholars do to a broader audience such as the first-year writing classroom. 

# Works Cited #

Rosenburg, Jessica "Poetic Language, Practical Handbooks, and the 'vertues' of Plants" _Ecological Approaches to Early Modern English Texts_ Ashgate Publishing, Ltd., 2015.
  
Schmidt, Benjamin M. “Do Digital Humanists Need to Understand Algorithms?” from _Debates in the Digital Humanities_ 2016

Shakespeare, William. “The Tempest, Act III, Scene II [Be not afeard]” _Poets.org._ https://poets.org/poem/tempest-act-iii-scene-ii-be-not-afeard Accessed on 2 Feb. 2022.
  
# My Dataset #

Torn Apart _Seperados_ data set 1
