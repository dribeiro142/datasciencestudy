# Data Science Study

It's my attempt to learning this amazing field.


Actually, my studies is guided by book Data Science from Scratch, by Joel Grus.

In this learning process I will apply some concepts related to 
Clean Code, Design Patterns and so on.

Enjoy it. 

# A Social Network for Data Scientists

The project suggested by Author is a fake Social Network for Programmers.
The main goal is to explore a fake data to understand the "mindset" of a Data Scientist.

## Organization

I divided the project in some classes

- NetworkDataBase.py
- NetworkDataLoader.py
- InMemoryData.py
- AnalysisData.py
- Utils.py

## The Flow of Analysis

### 1° Load the Data

Here, we create an Abstract Class **(NetworkDataBase)** 
with the main methods of **accessing the data**.
We use a **Loader Abstract** class to help in access of the data. 
This class was created because this example can **evolve to other 
forms of access** such as **Database**, **CSV files**, et cetera.



