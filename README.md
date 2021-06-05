# Introduction

The music and theory of 16th century England lies in an “in-between” that provides a fruitful ground for the questions of tonality, modality, and its effective qualities. 

# Backgroud

## A Brief Introduction to Renaissance Music Theory
While the scope of this paper does not include a full analysis or explanation of music theory in the Renaissance, there are two important concepts needed to understand its implications: Gamut and Mode. The Gamut, a shortened version of "gamma ut," is the solmization of the lowest note on the medieval letter notation system (Morley, 1597). Like the musical staff used for notation today, musicians in the sixteenth century would place letters on a series of lines and spaces to help them determine what notes a musician should sing. They are labeled with the letters A-G. In order to interpret the Gamut, musicians must know the intervallic pitch content associated with the letters; this is the context that allows them to understand what these letters mean. This is similar to the way that letters apart have little meaning, but when placed in word. The letters for the Gamut can be seen on the left side of the diagram that appeared in Morley's A Plaine and Easie Introduction to Practicall Musicke (1597):

<img width="417" alt="Morley Gamut" src="https://user-images.githubusercontent.com/72164586/120899953-7d998200-c5ef-11eb-9dda-32accb481d07.png">

[*The Gamut as displayed in Morley's A Plaine and Easy Introduction To Music*](https://chmtl.indiana.edu/tme/16th/MOR1597A_02GF.gif)

The Renaissance conception of pitch space, or how notes relate to one another, contextualizes pitches together through their intervallic relationship through the hexachord. The hexachord has six syllables that a singer can use: ut, re, mi, fa, sol, and la, taken from the phrase "Ut queant laxis."  The distance between mi-fa always indicates a semitone (half-step) while the others (ut-re, fa-sol, sol-la) are whole tone (whole step). Therefore, if a singer is able to name one note with a letter and a syllable from the hexachord, they can determine the intervals surrounding that note. For example, E mi indicates that the letter above (F fa) will be a half-step. The letter below (D re) will be a whole step lower. The full name of a note can be found by reading from left to right on chart of the gamut.

<img width="481" alt="Screen Shot 2021-06-05 at 2 11 06 PM" src="https://user-images.githubusercontent.com/72164586/120904158-e3920380-c607-11eb-971b-fd58533a751e.png">
*The Hexachord Solfege Syllables with their Intervallic Structure*

With this logic, the hexachords could start on one of three letters: C (natural hexachord), F (soft hexachord), and G (hard hexachord). Because not all pieces remained in the small space of six notes, the meant singers needed to mutate the hexachord to sing a full song as they may encounter the semi tone between E-F and B-C for example. 

Along with the gamut and hexachords, a clief was also used to help identify where notes would be sung. 


## Text Selection

The Gamut and the understanding of it was one of the primary ways that musicians conceived pitch space, or the way that pitches are perceived in relation to one another. While there is clearly an influence of continental ideas in many texts involving music theory in England during the 16th century, one significant change English theorists made from their Continental counterpoints was changes in solmization that lead to a change in English musicians understandings of how the gamut worked.  

The texts chosen for this project were taken from the [Texts on Music in English from the Medieval and Early Modern Eras (TME)](https://chmtl.indiana.edu/tme/). The website is maintained by the Center for the History of Music Theory and Literature (CHMTL) at the Indiana University Jacobs School of music. The project itself initiated and started by Peter M. Leffert (School of Music, University of Nebraska-Lincoln) with th goal of collecting and transcribing major texts about music from the fourteenth through seventeenth century in electronic form. For this project the texts chose were from the sixteenth and seventeenth century as this was a time of great change and development in the field of music theory and pedagogy in England at the time (_____). Three texts were chosen for both their importance in the field of music theory and their authors importance in music history.

The first text chosen was William Bathe’s A Briefe Introduction to the Skill of Song. Though no date is written on the manuscript, the work is thought to be written around 1596 due to its inclusion in Maunsell's 1595 catalogue (Huray, 2001). In her book Music Theory in Seventieth Century England, Rebecca Herissone comments that there was an “increasing awareness that modern pitch structure was based on the seven-note scale.” The English were increasingly concerned with the practicality of teaching people to sing as indicated by the use of words such as “Practical” or “brief” in the titles of their treatises. This treatise was important to musical thought in England due to Bathe’s application of the “Rule of Ut.” While the rule follows the traditional view that “Ut,” the lowest note of the hexachord may be placed on either C, F, or G, he concludes that this naming, be applied to any equivalent letter on the gamut. This allows Bathe to generate three “scales” that encompass three different keys: one with no flats, one flat, and two flats.

<img width="386" alt="Screen Shot 2021-06-05 at 2 18 50 PM" src="https://user-images.githubusercontent.com/72164586/120904336-f48f4480-c608-11eb-8489-fe5b35bc6c67.png">

Bathe’s signatures do not imply keys in the same way that we understand them today. A signature with no flats today implies C Major or A Minor, but the signature in Bathe’s work determines the solfege but not a modal final. This development notes the chaning views of pitch space in 16th Century England and relects an move away from the conception of "mode" that is discussed in other texts of the period. 

The second text for this project was writte by Thomas Morley, who was heavily involved in music making in England. He acted not only as a teacher, but a composer, translator, arranger, and editor His Plaine and Easie Introduction to Practicall Musicke from 1597 is largely considered to be one of the most, if not the most, important treatise on music written in English from the period. The text is interesting not only for its discussion of practical musical topics, abscense of explanations of mode, or mix of English and Italian ideas, but also its use of dialogue form, perhaps referencing the Italian theorist Gioseffo Zarlino’s Le istitutioni harmoniche (1558). 


# Methodology

Most research done within the analysis of music theory texts involves close reading of the text to identify main ideas and descriptions of important musical topics such as mode or meter. This paper will supplement close reading with the use of distant reading and topic modeling to gain new insight into how these two authors discuss music and what concepts are common across their work. While there has been some work done in the fields of music theory and musicology, there are barriers in place that can prevent the use of tools for larger computational practice to be difficult to implement. 

One major setback is the lack of textual material associated with music theory in electronic forms. While the work done on projects such as Texts on Music in English from the Medieval and Early Modern Eras or Thesaurus Musicarum Latinarum are providing sources for this work, they are not optimized for different types of textual analysis and require cleaning and preparation before they can be used effectively. 


## Tools and Techniques

### Voyant

In order to perform distant reading, the tool Voyant was used. [Voyant](https://voyant-tools.org/docs/#/guide/about) is a web-based tool for evaluating digital texts created by Stéfan Sinclair and Geoffrey Rockwell. It allows users to uplaod digital text files for processing in a variety of ways including determining collates, visualizing trends, and compare documents across the given corpus. 
 
For this project, Voyant was used to determine recurring words, their context, and relationships to others concerning different aspects of pitch space such as solfege or clefs. The goal was to understand the use of words from a larger level to supplement interpretations of conecpts derived through close reading. 
 
### MALLET
MALLET is a open source tool for natural language processing and topic modeling created by Andrew McCallum . Its use in this project was to determine what areas (topics) both Morley and Bathe discuss in their treatises. The topics were trained over the entier corpus and then applied to both Morley and Bathe individually.

## Preparing Texts

To prepare the texts for this project, the links, and annotations listed on the TME needed to be removed and the files needed to be split into documents that were readable by both Voyant and MALLET. This process was determined primarily based on the sections laid out by TME. 

Morley’s book is divided into three major parts:  Teaching to Sing, Treating to Descant, 
Treating of Composing or Setting of Songs which models three important aspects of becoming a well rounded musician in the renaissance. Due to this clear division of the book, the book itself was split into four documents, reflecting these three of instruction sections and the end matter as its own document. Bathe’s portion of the Coprus is divided into two parts: A Briefe Introduction to the Skill of Song (1589, reprint ca. 1596) and A Brief Introduction to the True Art of Music. This leads to the creation of six primary documents for use in Voyant.

|Document Title|Author|Title|
|-|-|-|
|morley_01|Thomas Morley|Teaching to Sing|
|morley_02|Thomas Morley|Treating to Descant|
|morley_03|Thomas Morley|Treating of Composing or Setting of Songs|
|morley_04|Thomas Morley|End Matter|
|bathe_01|William Bathe|A Briefe Introduction to the Skill of Song|
|bathe_02|William Bathe|A Brief Introduction to the True Art of Music|

*Documents Used for Voyant* 

Along with the preperation of texts was the preperation of a stopword list that was tailored for Middle English. This was done through looking through the texts for common English words with varient spellings (i.e. any for anies). Due to the specific nature of the texts, there was also consideration for common words that may have distinct meanings in music such as "re," wich acts as a solfege syllable and not as commonly to refer to something concerning something else. Once the corpus was uploaded to Voyant, the stoplist was adjusted once more to remove any words missed by hand. This also lead to the addition of the names in Morley's text to the coprus as they were not as important to the corpus as a whole as the individial book. 

The documents for Mallet were reduced to contain 1-2 sentences per document to allow for more percieces topics in training the model. 

# Results

## The Corpus 
Between all six documents, [the coprus](https://voyant-tools.org/?corpus=f8d87652557f789fe522e47988f701e1) contains 85,664 total words with 6,314 of those words being unique word forms. Morley's documents are significantly longer than Bathe which may indicate that through the process of distant reading, Morley's texts will be more heavily weighted. Of the three main sections of Morley's book, the section on Composing and Setting Songs was the longest with about 10,000 more words than the next longest document. 

|Rank|Document Title|Word Count|
|-|-|-|
|1|morley_03|24816|
|2|morley_01|14024|
|3|morley_02|17580|
|4|morley_04|16177|
|6|bathe_01|6978|
|6|bathe_02|6089|

*Voyant Document Rank, Title, and Word Count listed from Largest to Smallest*

The most used word in the corpus is the word Note* (adjusted to include both the singular and plural form of the word). This note is used extensively by both Bathe and Morley and is generally used with the same conceptual understanding as a word to describe 

<img width="473" alt="Screen Shot 2021-06-05 at 3 10 13 PM" src="https://user-images.githubusercontent.com/72164586/120905568-29eb6080-c610-11eb-83b6-692ae8516311.png">


<img width="445" alt="Screen Shot 2021-06-05 at 3 13 23 PM" src="https://user-images.githubusercontent.com/72164586/120905627-99f9e680-c610-11eb-81f5-686defe0af44.png">



## Coprus Topics

The topics for the coprus were generated using Mallet and running through 3000 iterations with 15 topics and the Optimize Interval set to 30. While some topics generated were less useful, there were 6 of particular interest in the case of identifying patters in the coprus: 

|Rank|Document Title|Topic Name|Topic Words
|-|-|-|-|
|1|0.23261|Teaching|philomathes master notes marg sing haue pray goe giue note time begin speake praie musicke singing tune till manie saie|
|2|0.18054|Practice|haue set make part wil downe vpon hath true vse beene musicke notes good reason thinke rest likewise made sing |
|4|0.15847|The Gamut|note place sol standeth notes flat euery rule gam sharp named aboue bee order places names verse vnder called song |
|5|0.14802|Meter|time perfect prolation lesse proportion moode signe pricke stroke set vnperfect euery semibriefe tripla dupla semibriefes notes master downe numbers |
|6| 0.03|Intervals|fift kind fourth tunes tune diapason aboue diuide key elami halfe diapente ancient lowest vnder euery diuided kinds highest kindes |

The Teaching Topic is the most waited topic, reflecting the larger text in the corpus generated by Morley. It reflects both the names of Philomathes (student) and the MAster in relation to singing, notes and instructions such as "begin." This topic is easily paired with teh second most weighted being the Practice topic that indicates general instructions of "setting down a note" or explaining how a musician might think through an idea. Despite the influence of Morley in the Coprus, 


![image](https://user-images.githubusercontent.com/72164586/120905105-11c61200-c60d-11eb-8cc7-fffb2511571a.png)

# The "Scale of Music"

<img width="465" alt="Screen Shot 2021-06-05 at 1 39 11 PM" src="https://user-images.githubusercontent.com/72164586/120903450-6cf30700-c603-11eb-8517-2d3f9b47cfb6.png">

<img width="425" alt="Trend Graph of Scale, Cleifes, and Keye in Morley" src="https://user-images.githubusercontent.com/72164586/120900791-192cf180-c5f4-11eb-9d04-a529dba6752d.png">

# The "Scale of Music"

# Conclusions



# References


```markdown


# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
