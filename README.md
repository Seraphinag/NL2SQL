# NL2SQL(Chinese)
Dataset for training models to convert Chinese into structured language

Explanations for each folder：

1、Annotation template----Annotation template format for the entire dataset

2、Othere datasets----Some other data sets reference.You can extract some from them according to your needs

3、json file----This is a file converted into json format. You can process it directly through python, but this is only part of my processing.

4、stopwords----Provide some brief Chinese stopwords.

5、keyword_extraction_results.ipynb----Related codes for keyword extraction.

6、keyword_extraction_results/semantic_dependency_analysis_results_train.json----Intermediate processing data file.

This is mainly for processing Chinese. If you want to process English, you can, but the effect may not be as good as some other advanced research results, and it is difficult to surpass. In this process, the related processing models I used are: roberta_chinese_base, base2, lilt-xlm-roberta-base, which can be downloaded from hugging face.
