HW6 (Parts 4) 
=============
###### Part4: 
Presumably, you are not pleased that in Patr3 your program had to discount possibly genuine occurrences of title. Describe an approach using MaxEnt that would do better. You might want to use data such as: the token uder consideration starts with a capital letter and the token after is a last_name, the token under consideration starts with a capital letter and the two tokens after are first_name followed by a last_name, the token under consideration starts with a capital letter and the token after is a first_name, the token under consideration starts with a lower_case letter, the token under consideration is a verb, the token under consideration is the first token of a sentence. Any other relevant data? Please think carefully about this.

Briefly sketch out the approach: list all the data you are considering, create the features out of this data, assign some weight to each feature constructed from the data and explain how you would use this to decide whether to assign a word to title or non-title. Although the weights are random, they should reflect your judgment about the relative strength of the evidence that data provides for deciding whether some token is a title or not.

Initial list of titles: Mister, Mr., Mrs., Professor, Doctor, Dr., President, Reverend, Rev., General, Colonel, Chairman

First names: John, Peter, Luke, Matthew, Simon, Saul, Sarah, Ruth, Nalini, Priya, Amit, Rahul, Narendra, Yuan, Shufeng, Luming, Ying, Yinxue, Juan

Last names: Smith, Jones, Bush, Cliton, Nixon, Liu, Khan, Kim, Chang, Deng, Patel, Kumar, Agarwal, Gandhi, Rodriguez

Notes
=============
Run main.jape for homework 6 (part 4) and click annotation "TitleWithWeight" to see all possible titles. 

See the comments in person_title_with_weight.jape for the definition of different weights.

Screenshots
=============
![screenshot1](https://github.com/qiaoshun8888/NLP_HW6/blob/master/screenshot1.png)

![screenshot2](https://github.com/qiaoshun8888/NLP_HW6/blob/master/screenshot2.png)
