## Record Linkage
### implementation of recordlinkage.
Many data mining and machine learning projects require information from ***various data sources*** to be integrated and linked before they can be used for further analysis.

A crucial task of such data integration is to identify which records refer to the same real-world entities across databases when  ***no common identifiers***, ***keys*** or ***consistent IDs*** are available and when records can contain errors and variations.

Record linkage is the act of linking data sets from different sources regarding the same entity with avoiding the fuzzy duplicated values.


#### Why join does't work ?! 

suppose that here are ***duplicates values*** in both Data Frames and the features or columns are ***differently named*** or the data may be ***collected manually*** and are ***prone to typos***. a regular ***join()*** or ***merge()*** functions will not work in this case. ****This is where record linkage comes in***. 

read the documentation file and PDF files in the same repository
