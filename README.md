# LOTR Character Relationship Network

![OIP](https://user-images.githubusercontent.com/67926222/177038865-4ed85c58-b5c0-4d6e-bc75-3690becd3faf.jpg)

# Table of contents
1. [Introduction](#introduction)
2. [Files](#files)
    1. [Characters](#characters)
    2. [Books](#books)
    3. [Notebook](#notebook)
    4. [Markdown](#markdown)

##  Introduction <a name="introduction"></a>

This project utilises NLP and network analysis to produce a character relationship network for the Lord of the Rings book series. This project was inspired by <a href="https://github.com/thu-vu92/the_witcher_network">this repo</a> which conducted a simialr analysis for the characters in the Witcher book series.

![lotr_community](https://user-images.githubusercontent.com/67926222/177049622-abf72109-13ec-4c0c-8dcc-73fa1bffa8cf.png)

## Files <a name="files"></a>

### Character Names <a name="characters"></a>

This project relies heavily upon the JSON file of character names taken from <a href="https://www.scarymommy.com/lord-of-the-rings-names">here</a>. Although if a better list is available, we should use that list. There may also be some work to develop a csv files that contains alternate names.

### Books <a name="books"></a>

The Books folder contains text files of the three books:

 * The Fellowship of the Ring 
 * The Two Towers 
 * The Return of the King

### LOTR Network Notebook <a name="notebook"></a>

This is a Jupyter notebook that conducts all the analysis, including generating the network graphs and centrality data. Most of the code foe this project was written here.

### Network Viz Markdown <a name="markdown"></a>

The Rmarkdown file is a run-through of how the data visualisations were made. The identically named HTML file is the knitted version of this document.



