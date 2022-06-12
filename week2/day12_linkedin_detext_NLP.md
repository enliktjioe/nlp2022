# LinkedIn DeText: A Deep NLP Framework for Intelligent Text Understanding

https://youtu.be/yXxGOcVomGM?list=PLk9rX6zZMSNGpXODGlN6jwYMV70K-5O5n

https://github.com/linkedin/detext

## Search and Recommender Systems

<img src="img/day12_linkedin_detext_NLP/image-20220612211853003.png" alt="image-20220612211853003" style="zoom:50%;" />

Example

![image-20220612211918622](img/day12_linkedin_detext_NLP/image-20220612211918622.png)

<img src="img/day12_linkedin_detext_NLP/image-20220612211939427.png" alt="image-20220612211939427" style="zoom:50%;" />



LinkedIn Search and Recommendation Ecosystem
![image-20220612212029390](img/day12_linkedin_detext_NLP/image-20220612212029390.png)



## Deep Learning for NLP

- NLP in Search and Recommender Systems
  ![image-20220612212244471](img/day12_linkedin_detext_NLP/image-20220612212244471.png)
-  Large amounts of text data
  ![image-20220612212421248](img/day12_linkedin_detext_NLP/image-20220612212421248.png)
- Understanding Text Semantics
  <img src="img/day12_linkedin_detext_NLP/image-20220612212446469.png" alt="image-20220612212446469" style="zoom:50%;" />
  - Software engineer = programmer ?
- Benefits of Deep NLP
  <img src="img/day12_linkedin_detext_NLP/image-20220612212528879.png" alt="image-20220612212528879" style="zoom:50%;" />
- Challenge of Designing a Deep NLP Framework
  ![image-20220612212627153](img/day12_linkedin_detext_NLP/image-20220612212627153.png)



## DeText Framework

- Goals
  ![image-20220612212727210](img/day12_linkedin_detext_NLP/image-20220612212727210.png)
- DeText Framework Design
  ![image-20220612212952947](img/day12_linkedin_detext_NLP/image-20220612212952947.png)
  ![image-20220612213014939](img/day12_linkedin_detext_NLP/image-20220612213014939.png)



## Applications: Ranking

- Search systems at LinkedIn
  ![image-20220612213055140](img/day12_linkedin_detext_NLP/image-20220612213055140.png)
- Ranking for Search Systems: An Example
  ![image-20220612213219782](img/day12_linkedin_detext_NLP/image-20220612213219782.png)
  - Experiments
    ![image-20220612213355238](img/day12_linkedin_detext_NLP/image-20220612213355238.png)
  - Online Deployment
    ![image-20220612213342121](img/day12_linkedin_detext_NLP/image-20220612213342121.png)
- Two-Pass Ranking: Solution to Large # of Documents
  ![image-20220612213425040](img/day12_linkedin_detext_NLP/image-20220612213425040.png)
- LiBERT - BERT Serving Solution 1
  ![image-20220612213453205](img/day12_linkedin_detext_NLP/image-20220612213453205.png)
  - Latency Performance
    ![image-20220612213652003](img/day12_linkedin_detext_NLP/image-20220612213652003.png)
  - Relevance Performance
    ![image-20220612213723455](img/day12_linkedin_detext_NLP/image-20220612213723455.png)
- Embedding Precomputation - BERT Serving Solution 2
  ![image-20220612213750186](img/day12_linkedin_detext_NLP/image-20220612213750186.png)
  - Offline Latency Test
    ![image-20220612213811319](img/day12_linkedin_detext_NLP/image-20220612213811319.png)
  - Online Deployment Summary
    ![image-20220612213826965](img/day12_linkedin_detext_NLP/image-20220612213826965.png)
- Classification Applications at LinkedIn
  ![image-20220612213847641](img/day12_linkedin_detext_NLP/image-20220612213847641.png)
  - Example: Query Intent Classification
    ![image-20220612213919278](img/day12_linkedin_detext_NLP/image-20220612213919278.png)
  - Results
    ![image-20220612213931124](img/day12_linkedin_detext_NLP/image-20220612213931124.png)



## Conclusions

![image-20220612214117303](img/day12_linkedin_detext_NLP/image-20220612214117303.png)



## References

![image-20220612214124480](img/day12_linkedin_detext_NLP/image-20220612214124480.png)

