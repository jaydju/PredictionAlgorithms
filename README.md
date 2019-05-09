# Prediction

"Prediction of student behavior has been a prominant area of research in learning analytics and a major concern for higher education institutions and ed tech companies alike. It is the bedrock of [methodology within the world of cognitive tutors](https://solaresearch.org/hla-17/hla17-chapter5/) and these methods have been exported to other areas within the education technology landscape. The ability to predict what a student is likely to do in the future so that interventions can be tailored to them has seen major growth and investment, [though implementation is non-trivial and expensive](https://www.newamerica.org/education-policy/policy-papers/promise-and-peril-predictive-analytics-higher-education/). Although some institutions, such as [Purdue University](https://www.itap.purdue.edu/learning/tools/forecast.html), have seen success we are yet to see widespread adoption of these approaches as they tend to be highly institution specific and require very concrete outcomes to be useful."

## Project Description

In this project, I built various models to predict student course dropout and then compared the performance of those models. The three models tested are the CART Model, the Conditional Inference Tree Model, and C50. We find that C50 performs the best based on ROC metrics. 

CART Tree
![](CART Tree.png)

Conditional Inference Tree
![](Conditional Inference Tree.png)

C50 Model
![](C50 Winnowing.png)

## References

[Adhatrao, K., Gaykar, A., Dhawan, A., Jha, R., & Honrao, V. (2013). Predicting Students’ Performance Using ID3 and C4. 5 Classification Algorithms. International Journal of Data Mining & Knowledge Management Process, 3(5).](https://arxiv.org/ftp/arxiv/papers/1310/1310.2071.pdf)

[Brooks, C. & Thompson, C. (2017). Predictive modelling in teaching and learning. In The Handbook of Learning Analytics. SOLAR: Vancouver, BC](https://solaresearch.org/hla-17/hla17-chapter5/)

[The caret package](https://topepo.github.io/caret/train-models-by-tag.html)

[The C50 package](https://topepo.github.io/C5.0/)

[Pradhan, C. (2016). What are the differences between ID3, C4.5 and CART? Quora](https://www.quora.com/What-are-the-differences-between-ID3-C4-5-and-CART)

## Videos

[Jalayer Academy. (2015). R - Classification Trees (part 1 using C5.0)](https://www.youtube.com/watch?v=5NquIfQxpxk)
