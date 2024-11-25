Healthcare Tweets Sentiment Analysis:
   
**Project Overview**
Millions of healthcare-related tweets are posted daily, offering valuable insights but remain largely unstructured and unlabelled. This study tackles the challenge of classifying these tweets using a semi-supervised machine learning approach implemented in the Apache Spark distributed computing framework. Two big data solutions—global self-supervised learning and local semi-supervised learning—were developed to label tweets and classify them efficiently.

**Problem Statement**
The large volume of unstructured and unlabelled tweets presents challenges for meaningful analysis in healthcare discussions. Traditional labeling methods are labor-intensive and time-consuming, necessitating scalable and efficient solutions. Additionally, short and noisy text, such as tweets, complicates the use of conventional text classification techniques.

**Approach**
Bi-term topic modeling was combined with human annotation to create labels from a sample of healthcare-related tweets. A Naive Bayes classifier was trained on the labeled dataset using both global self-supervised and local semi-supervised learning methods. Apache Spark was leveraged to ensure scalability and distributed processing for handling large datasets.

**Results and Impact**
The global self-supervised approach achieved an accuracy of 82%, slightly below the baseline model's 84%, while the local approach reached 77%. Despite scalability challenges, the study highlighted the potential of distributed frameworks to analyze big data and stressed the importance of high-quality training data. These findings provide a foundation for improving tweet classification and supporting better decision-making in public health resource allocation.
