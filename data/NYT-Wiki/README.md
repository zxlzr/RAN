# Dataset
You could download the dataset from  [GoogleDrive](https://drive.google.com/open?id=1ck3clj1twYug7eURAnIFjto_dMOz3T8I). 

The dataset contains four files, including source.txt, train.txt, valid.txt, test.txt, common_relation.txt. The structures of source.txt, train.txt, valid.txt, test.txt are homogeneous. source.txt is  derived from  [NYT-Wikidata](https://github.com/thunlp/PathNRE/tree/master/data) which align Wikidata  with New York Times corpus (NYT) and  train.txt, valid.txt, test.txt are derived from [Wikipedia-Wikidata](https://github.com/UKPLab/emnlp2017-relation-extraction) which align Wikidata with   Wikipedia.


Each line in those files is a instance, containing a entity pair and a corresponding sentence. The first element in each line is the id of the head entity, and the second element is the id of the tail entity. The subsequent two elements are the name of head and tail entity respectively, and the fifth element is the relation type. The later part in each line is a sentence corresponding with this entity pair.

The common_relation2id.txt records the name of all relation types, each name resides in a line.
