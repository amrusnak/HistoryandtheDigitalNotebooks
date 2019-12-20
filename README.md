# HistoryandtheDigitalNotebooks

This is the repository for python scripts used for project for History and the Digital
(course given 19 Fall at EPFL, by Jérôme Baudry)

## Inside out of 19th century US patents
Patent documents are special. They are technical documents that contain detailed specification on how each invention works. At the same time, you can observe society of that time by reading patent documents at a distance.
Then can we find these out through classic statistical approach and machine learning techniques?

### Evolution of Late 19th century US and Patents
19th century was a period of huge change for the US, having urbanization on side and evolution of industry on the other. More and more people flocked to cities and heavy industries were gaining more and more influence.
How were these social phenomena reflected in the statistical summary of patent documents? How it differed in different types of industries or regions?

### Finding Buzzword of 19th century US by textual clustering
We can see though patent metadata which industries were the lead in late 19th century US. But can we discover buzzwords of that time, in each industry? It is a huge work to be done by human historians. How about we adopt some automated ways to find the buzzwords? 

### Dataset:
US patent documents from 1869-1900
US decennial census data for top 100 urbanized places (1870-1900)

### Notebook description
population.ipynb : processing population data into plain dataframe
group_by_decade.ipynb : grouping patent documents according to their publication year.
patent_metadata_studies.ipynb : studying patent metadata and relating them with population. 
