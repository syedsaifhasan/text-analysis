# Text Analysis

In this project, we refer to the term text analysis to the process of automatically extract topics or recovery the
topic structure within a corpus of textual data. There are two approaches of doing this: 1) text classification
where supervised learning algorithms are used to classify a set of corpus to a known topic; 2) topic modeling
where unsupervised learning methods are used to cluster a set of corpus and generate topics for each cluster.
The idea of text analysis can apply to a wide range of domains regardless of the length and form of the
data. We can apply topic modeling or text classification techniques to analyze short to medium text like
tweets [1] or user’s comment [2], to long article like scientific articles [3], or even apply to enhance software
traceability [4] and so on. With the explosion of textual data in the web (blog post, online reviews, tweets,
and etc.), there is simply impossible to extract topics and group all of them by human reviewers. Luckily,
we can use machine learning to automate the process. \\

We are in particular interested in exploring several embedding methods for supervised learning and
unsupervised learning text analysis techniques. We report the implementation of both topic classification
and topic modeling algorithms. For topic classification, we can evaluate model’s performance by directly
computing the precision, recall and F-1 score. However, for topic modeling, it is difficult to compute those
quantitative measurement because the generated words for each cluster do not really match the ground-truth
labels. Though, there are other metrics such as the Coherence Value to check the quality of a topic model.
Also, we use various visualization methods to manually look up the results on several topic clusters. \\

## References

[1] L. Hong and B. D. Davison, “Empirical study of topic modeling in twitter,” in Proceedings of the First
Workshop on Social Media Analytics, SOMA ’10, (New York, NY, USA), p. 80–88, Association for
Computing Machinery, 2010.
[2] D. Ramamonjisoa, “Topic modeling on users’s comments,” in 2014 Third ICT International Student
Project Conference (ICT-ISPC), pp. 177–180, 2014.
[3] C. Wang and D. M. Blei, “Collaborative topic modeling for recommending scientific articles,” in Proceedings of the 17th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining,
KDD ’11, (New York, NY, USA), p. 448–456, Association for Computing Machinery, 2011.
[4] H. U. Asuncion, A. U. Asuncion, and R. N. Taylor, “Software traceability with topic modeling,” in 2010
ACM/IEEE 32nd International Conference on Software Engineering, vol. 1, pp. 95–104, 2010.
