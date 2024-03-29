# Clustering

Introduction

Do you ever find yourself spending too much time trying to group or organize PDF documents based on their patterns (not content)? It can be a tedious task, especially when done manually by eye-balling each document. Our goal is to simplify this process by automating it through clustering techniques.

Why it Matters

Imagine having a stack of PDFs with similar layout structures, but you need to organize them efficiently. By automating the clustering process, we can save valuable time and effort.

Approach

Extracting Information: We'll use a library "pdfplumber" to extract the layout information from PDFs. This library is handy because it can also provide us with coordinates for each text element, aiding in understanding the layout.

Exploratory Data Analysis (EDA): Once we have the layout information, we'll analyze it to understand the patterns and structures present in the documents. EDA : [Click here](https://github.com/Fauzanpaimen/Exploratory-Data-Analysis-Document-Clustering)

Data Cleaning and Preparation: Before applying any clustering algorithms, it's essential to clean and prepare the data. This involves removing any noise or irrelevant information that might interfere with the clustering process and factorized text with coordinate.

Clustering Using K-means Algorithm: We'll employ the K-means algorithm, a popular method for clustering data. By utilizing the Euclidean distance similarity metric, we can group similar documents together based on their layout patterns.

Reference : [Click here for more information](https://www.researchgate.net/publication/324794105_Document_Clustering_Based_On_Text_Mining_K-Means_Algorithm_Using_Euclidean_Distance_Similarity)

Concept : [Click here for more information](https://www.canva.com/design/DAF8WJlUKlk/ZVmdMDs8gLG-HhE18AHaGQ/view?utm_content=DAF8WJlUKlk&utm_campaign=designshare&utm_medium=link&utm_source=editor)

