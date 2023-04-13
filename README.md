# DS340_NLP
DS340 Natural Language Processing <br>
Tristan Robinson <br>
Semester Project Introduction

Throughout the course of this semester, I will seek to break down the linguistics and design of Magic: the Gathering trading cards in hopes of discovering what, if anything, can be attributed to its thirty-year longevity and success. I hope to find trends of game design throughout the three decades of development and refining. I also want to investigate how its players discuss the game both amongst themselves online and to non-players through promotional writing. 

# Dataset Information
Magic: the Gathering card data is the best case scenario for research, and in my opinion a data scientist's dream: someone has already done all the work for us! <br>
This someone is  <a href="https://scryfall.com/">Scryfall</a>, a fan-made card database used by players to search through over thirty years of cards to find the perfect one for a given deck. Users can specify their search by virtually any feature of a card, including name, color, cost, expansion, and even price. I have used this site for years as a player, and now I will use it as a Natural Language Processing researcher. <br>
Scryfall offers an API, as well as <a href="https://scryfall.com/docs/api/bulk-data">bulk data files</a> which contains data on every card arranged neatly on a single JSON file. I will be using the "Oracle Cards" file as it contains the most up-to-date version of the card without duplicates. If, however, I do desire duplicates, I will opt to use the "Default Cards" file. <br>
The terms of using this data is fairly straightforward and suited to our interests, as the data is provided from the company which creates MTG, Wizards of the Coast, to Scryfall for, among other things, research purposes. As long as I do not claim Scryfall or Wizards of the Coast is endorsing my work, charge money or require another service for access to my work, or create a whole new game, I am free to use this data as I please. <br>
The raw file is a 109 MB JSON file which contains several parameters about a card I will remove for the final cleaned dataset. I intend to only keep the name of the card, the year it was released, the rules text of the card, and its color. So, aside from some simple column removals, I will not be altering this dataset much at all. <br>


TODO - will become more detailed as time goes on and I learn techniques. <br>
Preprocess data, split into desired categories (year, color, popularity, etc.) <br>
perform desired analysis <br>


