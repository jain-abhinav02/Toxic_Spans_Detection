# SemEval-2021 Task 5: Toxic_Spans_Detection

### SemEval
[SemEval](https://semeval.github.io/) is a series of international natural language processing (NLP) research workshops whose mission is to advance the current state of the art in semantic analysis and to help create high-quality annotated datasets in a range of increasingly challenging problems in natural language semantics. Each year's workshop features a collection of shared tasks in which computational semantic analysis systems designed by different teams are presented and compared. SemEval is sponsored by the SIGLEX Special Interest Group on the Lexicon of the Association for Computational Linguistics. \
SemEval-2021 : https://semeval.github.io/SemEval2021/

---
### Toxic Span Detection

The Toxic Spans Detection task concerns the evaluation of systems that detect the spans that make a text toxic, when detecting such spans is possible. Moderation is crucial to promoting healthy online discussions. Although several toxicity (a.k.a. abusive language) detection datasets (Wulczyn et al., 2017; Borkan et al., 2019) and models (Schmidt and Wiegand, 2017; Pavlopoulos et al., 2017b; Zampieri et al., 2019) have been released, most of them classify whole comments or documents, and do not identify the spans that make a text toxic. But highlighting such toxic spans can assist human moderators (e.g., news portals moderators) who often deal with lengthy comments, and who prefer attribution instead of just a system-generated unexplained toxicity score per post. The evaluation of systems that could accurately locate toxic spans within a text is thus a crucial step towards successful semi-automated moderation. \
\
For more information, visit the following links \
Task website : https://sites.google.com/view/toxicspans \
Codalab page : https://competitions.codalab.org/competitions/25623 \
Task Github repo : https://github.com/ipavlopoulos/toxic_spans 

---
### Solution Approach
Our solution is built upon RoBERTa language model and Conditional Random Fields (CRF). We pre-trained RoBERTa on Civil Comments dataset, enabling it to create better contextual
representation for this task. We also employed the semi-supervised learning technique of selftraining, which allowed us to extend our training dataset. In addition to these, we also identified some pre-processing steps that significantly improved our F1 score. Our proposed system achieved a rank of 41 with an F1 score of 66.16%. 


Link to the paper : https://aclanthology.org/2021.semeval-1.118/

---
### Team members :

1. [Thakur Ashutosh Suman](https://github.com/ashutoshsuman99)
2. [Abhinav Jain](https://github.com/jain-abhinav02)

---
All of our work on this task has been saved on the following drive link
https://drive.google.com/drive/folders/1Ttt11uJB8DYpOy4o0klfrN4ix9PZr2FD?usp=sharing


