---
title: "Introduction to editing"
teaching: 0
exercises: 0
questions:
- "How to create and edit a Wikidata item?"
objectives:
- Be able to create and edit a Wikidata entry
- Understand properties and relations, and where to find lists of approved properties and relations
- Be able to add new statements that link to other items
- Understand property constraints

keypoints:
- "First key point. (FIXME)"
---


{% include links.md %}

## 3.1 Introduction

Here we will work in the test instance of Wikidata so you will not break anything. Also keep in mind that the editing history is kept in Wikidata so error can also be easily fixed there. The test instance is cleaned regularly.

## 3.2 Create a new item

In the following we will create new items. In order to avoid to fill wikidata with test entries, we will used the test instance (https://test.wikidata.org/)  and not the official, production version (https://wikidata.org/).

- Goto the test version at https://test.wikidata.org/

![Front Page of the test instance](../fig/Screenshot_test_instance_front_page.png) 

- Click "[Create a new Item](https://test.wikidata.org/wiki/Special:NewItem)" link on the left site.

![Empty create form of the test instance](../fig/Screenshot_test_instance_empty_create_page.png) 

- Fill out the form - You can now add an entry about anything you want like an institution, a book, a research article or and author. For this exercise, we will generate an entry of the physisist Richard Feynman. You can also add yourself (if you feel famous enough). We choose "en" in the *Language* drop-down menu, write "Richard Feynman" in the *Label* field, "American theoretical physicist" in the *Description* field and "Richard Phillips Feynman" in the *Aliases* field.
- Once we are done we click on "Create"

You can compare the entry that you have generated on the test instance with the current version of the item in Wikidata ([Q39246](https://www.wikidata.org/wiki/Q39246)).

![Wikidata Feyman](../fig/Screenshot_Wikidata_Richard_Feynman_excerpt.png)

One of the most famous books written by Richard Feyman is his autobiobliography "Surely You're Joking, Mr. Feynman!". Let's create an item for this book. This is very similar to the creation of the item about Feynman himself.

- Go to the test instance at https://test.wikidata.org/
- Click on "[Create a new Item](https://test.wikidata.org/wiki/Special:NewItem)" link on the left site.
- Fill out the form - We choose "en" in the *Language* drop-down menue, write "Surely You're Joking, Mr. Feynman!" in the *Label* field, "book by Richard Feynman" in the *Description* field and leave the *Alias* field blank
- Once we are done, we click click on "Create"
 
![Wikidata Feyman](../fig/Screenshot_test_instance_create_Joking.png)  
![Wikidata Feyman](../fig/Screenshot_test_instance_Joking_fresh.png)  
![Wikidata Feyman](../fig/Screenshot_Wikidata_Joking.png)  

https://www.wikidata.org/wiki/Q2743592


## 3.3 Add statements

- Data types: 
    - String
    - Properties
    - Quantity
    - Time
    - URL
    - And many more https://www.wikidata.org/wiki/Help:Data_type

- Click add statement
- Fill a property and a values

- Some suggestions for statements:
    - "instance of" (P31) - "book", "scholarly article"
    -  "publication date" (P577) 

Have a look again at Origin of Species to get inspiration: https://www.wikidata.org/wiki/Q20124

## 3.4 Community norms [examples of how other libraries have used?]
