# HackatonZakupki
## Task
build intelligent cluster for the analysis of procurement objects and their attributes using artificial intelligence
## Solution
- clear string columns
- lemmatization words
- build embeddings by TF-IDF on description columns
- use cosinus similarity with input description to find similar descritption in database
- sorted by value of cosinus similarity
- analyst recevied data for recomendation to provider
## Technology
- Pandas, numpy, seaborn, matplotlib, sklearn,
- lemmatization (pymystem3)
- build embeddings with TF-IDF (TfidfVectorizer from sklearn)
## Model Output
- Provider enter neccesery dicriprion and output similary goods
![image](https://user-images.githubusercontent.com/41813477/193901242-4af8401f-6b84-4dfa-a947-c6862f0a0a2a.png)
- Model analys the received data
- *Distribution the mean price among similar categories*
![image](https://user-images.githubusercontent.com/41813477/193564078-b7937eca-9963-4e4f-82bf-a947c88c6f40.png)
- *Сountry with biggest count in category*
![image](https://user-images.githubusercontent.com/41813477/193564637-447ce6bd-44d5-4a3a-9bdd-7a7b0c52ac36.png)
- *Contry with biggest competition in category*
![image](https://user-images.githubusercontent.com/41813477/193565104-c03a3803-5154-45a3-8dc5-47efed6b73cb.png)
- *Distribution price in category*
![image](https://user-images.githubusercontent.com/41813477/193565341-32dfaaaf-8b0c-49b1-8a73-42f79e2660f4.png)
- *top 15 provider with biggest count sale*
![image](https://user-images.githubusercontent.com/41813477/193565540-df00e4f2-0102-4bbe-94a7-17a985883055.png)
## Result
**The supplier can make the most correct business policy based on the analysis and review of analogue products**
