# Is semantic similarity a good predictor of an inference relation between propositions? An attemp at training a classifier on US2016D1Reddit corpus 📖

**Summary**:
I calculate vector representations (meaning aproximation) of propositions from US2016D1Reddit corpus. I then calculate semantic similarity between pairs of propsitions A and B, some of which are premise-conclusion pairs while some are not. Finally I try to create a neural network which takes semantic similiarity of A and B pair as input and predicts whether A and B are premise-conlusions pairs.  
<br/>  

For more details read the article (in Polish, unpublished) describing the project and the code:  
[Article_SemanticSimiliarity _and_argumentation.pdf](https://github.com/WojtekPachowiak/Argumentation_SemanticSimiliarity_Python/files/6258989/Article_SemanticSimiliarity._and_argumentation.pdf)

The code on Google Collaboratory:  
https://colab.research.google.com/drive/13lJb_aUPstlC6i_F1e-xcNk8S9H4Dw_f?usp=sharing

The main idea and parts of code are taken from:  
https://github.com/atka555/argument-mining

<br/>
In order to run the code yourself, you need to download the "corpus_US2016D1reddit.zip" file. Next, in project code you need to change the line "maps = glob.glob("<YOUR_PATH>/US2016D1reddit/\*.json")" to match the location of the file on your computer.

If you don't want to use Google Collaboratory you can donwload the .py file provided in this repository.  
<br/>

### Preview images (read the artcle in order to understand what they mean):
![CosSimBox](https://user-images.githubusercontent.com/50328147/113594283-c8227080-9637-11eb-8dc1-fad3a6209fcb.png)
