## Record Linkage

### why record linkage ?
Record linkage is the act of linking data sets from different sources regarding the same entity with avoiding the fuzzy duplicated values.
Many data mining and machine learning projects require information from ***various data sources*** to be integrated and linked before they can be used for further analysis.

A crucial task of such ***data integration*** is to identify which records refer to the ***same real-world entities*** across databases when  ***no common identifiers***, ***keys*** or ***consistent IDs*** are available and records can contain errors and variations.


### Why join don't work ?! 

suppose that here are ***duplicates values*** in both Data Frames and the features or columns are ***differently named*** or the data may be ***collected manually*** and are ***prone to typos***. a regular ***join()*** or ***merge()*** functions will not work in this case. ***This is where record linkage comes in***. 

![images](https://user-images.githubusercontent.com/84151016/155808405-460f2314-1191-43ea-abbf-2ad552d6a02e.png)


## Record linkage proccess.

![record linkage](https://user-images.githubusercontent.com/84151016/155808252-e6c44653-afaa-4df8-9bd1-dd37a6f8760b.jpeg)

1- Generating pairs

2- Comparing the DataFrames

3- Finding matching pairs

4- The final evaluation step is the quality of the linked records 

Read the documentation file and PDF files in the same repository for better understanding.


![1-Figure1-1](https://user-images.githubusercontent.com/84151016/155808899-33b6579f-5455-4f00-a7f6-87300906b2e1.png)


## Resources:
http://www.bristol.ac.uk/media-library/sites/cmm/migrated/documents/problinkage.pdf
https://arxiv.org/pdf/2003.04238.pdf
https://cdn.oreillystatic.com/en/assets/1/event/290/New%20directions%20in%20record%20linkage%20Presentation.pdf
http://axon.cs.byu.edu/~randy/pubs/wilson.ijcnn2011.beyondprl.pdf
http://www2.stat.duke.edu/~rcs46/linkage/
https://archive.ics.uci.edu/ml/datasets/Record+Linkage+Comparison+Patterns
http://users.cecs.anu.edu.au/~Peter.Christen/Febrl/febrl-0.3/febrldoc-0.3/node6.html



