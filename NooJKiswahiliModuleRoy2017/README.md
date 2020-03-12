THE NooJ KISWAHILI MODULE

The NooJ Kiswahili Module is dedicated to the memory of the late mwalimu Jean de Dieu Karangwa (1962-2017), Assistant Professor of Kiswahili at INALCO, Paris, France and my former Kiswahili teacher.

Proper citation may be: 
2017. Mathieu Roy. NooJ Kiswahili Module V. 1.0: electronic Kiswahili-English dictionary and morphological grammar of Kiswahili for Free Non-Commercial Use.
Distributed under Creative Commons Licence: https://creativecommons.org/licenses/by-nc-sa/3.0/

You can download it freely at http://www.nooj4nlp.net/ or http://www.nooj-association.org/
(see “Linguistic Resources”).

ABOUT THE DICTIONARY
Which Kiswahili is it?
Kiswahili is generally described as the bantu language G42 in Malcom Guthrie’s classification. But this continentally spread language is diverse from East Africa to Central Africa. Kiswahili ni nyama ya tembo, kila mtu anachumia pake according to Alphonse Lenselaer in the presentation of his Swahili-Français dictionary. It’s a fact that there are many varieties of Kiswahili, to the point that we can seriously talk of Viswahili. Here we have described the Standard Swahili, or Kiswahili sanifu. This is the more widely understood and spoken variety. This is also the written Kiswahili for the medias, law and East African Schools. Finally, it’s the variety used in Dar es Salaam, the economic capital city of Tanzania. Historically the Standard Swahili has originated with the Kiswahili used in Zanzibar also known as Kiunguja.
Working with Standard Kiswahili means setting aside the Nairobi Sheng, Kiswahili varieties from the Democratic Republic of Congo (Kisangani Kiswahili, Ituri Kiswahili, Kivu Kiswahili, Katanga Kiswahili), and Northern Kenyan varieties such as Kiamu (Lamu island) and Kimvita (Mombasa City), despite their importance in the history of literature. However, formalization allows us to develop tools for these varieties in a succeeding step.

The dictionaries entries and English translations are mainly based on the Internet Living Kiswahili Dictionary data whose proper citation is:

2008. M. Benjamin, editor. Swahili-English Kamusi Project Wordlist for Free Non-Commercial Use, Kamusi Project International.
Distributed under Creative Commons Licence: https://creativecommons.org/licenses/by-nc-sa/3.0/

The Kamusi project was a collaborative, open and international project directed by Martin Benjamin of Yale University, USA (now at Polytechnique, Lausanne, Switzerland). Many top Kiswahili scholars contributed as well as non-academic experts. The Kamusi project mixed various dictionaries, published or working papers, and expanded by continuous updates from East Africa. The documents were available at www.kamusi.org as .txt files.

A PERL script written by Mirko Westermeier (computer science researcher, Münster University, Germany), available at https://github.com/Feh/kamusi-cli (retrieved the 29th of July 2017) allowed me to convert these text files into a SQLite database and to process it with SQL requests to create NooJ dictionaries entries with a special focus on lemmatization and formalization of generative rules of inflexed or derived words when the entries in the Kamusi Project were already flexed and derived for the most frequent words forms.

The dictionary is made of 4 sub-dictionaries:
Adjectives: 3063 entries (13889 derived entries)
Nouns: 25280 entries (47171 derived entries)
Verbs: 16484 entries (65727 derived entries)
Other categories: 2525 entries (2771 derived entries)

Each one is associated with a .nof derivational and/or flexional description. The need to use this type of generative dictionaries has required a new formalization of the entries that are written in a specific format for NooJ that enable lemmatization. The passage from the SQLite database to NooJ dictionaries is my work and have been realized with appropriate SQL requests.

ABOUT THE GRAMMAR
The grammar is made of numerous specialized graphs. They have been written by me who is the sole author of the work. The focus is on the morphology of the verb module. All conjugated verbs are detected if they are in the verb dictionary. All tenses are included: time, aspect and mode. Some graphs are also made for nouns, like the one that add a -ni locative suffix to translate each noun to a locative class 16, 17 or 18 expressing an idea of location in time or space.

ABOUT THE TEST TEXT
The text to test the module is an extract from the autobiography of the famous Tanzanian author Mathias E. Mnyampala (1917-1969):

Maisha ni kugharimia © Mathias E. MNYAMPALA 2014 (mswada) © Mathieu ROY na DL2A - Buluu Publishing 2014 (uhariri) ISBN : 979-10-92789-29-4
Sample reproduction has been authorized for NooJ.

THIS IS VERSION 1.0
It works, it has been rigorously designed but… science is always an unending quest as it has been underlined in the now classical epistemological works of Karl Popper. These formalizations of the Kiswahili language are very far from being dogmatic, and are on the contrary very likely to evolve with time and further research.
NooJ software evolves itself and is now shifting from a code written in JAVA, .NET etc. to RA language. RA is a source of new powerful possibilities. The RA version is a new adventure in itself to say the least.
Lemmatization can go deeper, too, with extra work and could be a matter of several research theses or articles.
Finally, I hope this Kiswahili NooJ Module might be a basis of work for others. This work is free for non-commercial use and it can be transformed and adapted to reach further horizons in Kiswahili linguistics.

Ninawatakieni kazi njema!
Paris, France
Summer 2017
Mathieu ROY (PhD, African studies) 
e-mail: roy AT dl2a DOT eu
