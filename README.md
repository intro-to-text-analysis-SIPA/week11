# Week 11: Text analysis: Named Entity Recognition
This week, we will learn how to apply Named Entity Recognition (NER) to text files. NER locates and classifies named entities mentioned in unstructured text into preset categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages, and other categories. It's a useful way to quickly parse out the who, what, where, when, how much, etc… in a large body of text. We will use the spaCy Python library to perform NER. 

- Topics covered: 
    - What is Named Entity Recognition (NER)?
    - What are practical applications of NER?
    - How to perform NER with newspaper data?
    - How to use this method with other text data sources?
- Curriculum for this session:
    - Melanie Walsh, _Introduction to Cultural Analytics_, [Named Entity Recognition](https://melaniewalsh.github.io/Intro-Cultural-Analytics/05-Text-Analysis/12-Named-Entity-Recognition.html)
- Assignments due before class:
   - Work through the curriculum for the upcoming week's session in a Jupyter Notebook. Download your Jupyter Notebook as "ipynb" file (Go to "File", "Download as", "Notebook (.ipynb)"), and [upload](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository) the file to the weekly GitHub assignment link.
        -  You are welcome to use the dataset provided in the curriculum link or use a dataset of your choice. 
- Additional readings/resources (not required, but useful!):
    - Tutorials:
        - Brandon Rose: [Entity Extraction and Network Analysis](http://brandonrose.org/ner2sna)
        - Geeks for Geeks: [Named Entity Recognition](https://www.geeksforgeeks.org/named-entity-recognition/)
        - Mattingly, William._ [Introduction to Named Entity Recognition](http://ner.pythonhumanities.com)_, 2021 (2nd ed.).
        - Towards Data Science: [NER for Extracting Stock Mentions on Reddit](https://towardsdatascience.com/ner-for-extracting-stock-mentions-on-reddit-aa604e577be)
    - Explainers:
        - Super.AI: [What is named entity recognition (NER) and how can I use it?](https://medium.com/mysuperai/what-is-named-entity-recognition-ner-and-how-can-i-use-it-2b68cf6f545d)
        - Towards Data Science: [Named Entity Recognition: Applications and Use Cases](https://towardsdatascience.com/named-entity-recognition-applications-and-use-cases-acdbf57d595e)
    - Studies:
        - Fields, Sam, Camille Lyans Cole, Catherine Oei, and Annie T Chen. "Using Named Entity Recognition and Network Analysis to Distinguish Personal Networks from the Social Milieu in Nineteenth-Century Ottoman-Iraqi Personal Diaries." _Digital Scholarship in the Humanities_, August 8, 2022, fqac047.[ https://doi.org/10.1093/llc/fqac047](https://doi.org/10.1093/llc/fqac047).
            - This article employs NER and network analysis to study Joseph Mathia Svoboda's social interactions, as well as his observations of his broader social milieu.
        - Molina-Villegas, Alejandro, Victor Muñiz-Sanchez, Jean Arreola-Trapala, and Filomeno Alcántara. "Geographic Named Entity Recognition and Disambiguation in Mexican News Using Word Embeddings." _Expert Systems with Applications_ 176 (August 15, 2021): 114855.[ https://doi.org/10.1016/j.eswa.2021.114855](https://doi.org/10.1016/j.eswa.2021.114855).
            - This study shows that relationships between geographic and semantic spaces arise when applying word embedding models over a corpus of documents in Mexican Spanish. 
        - Vychegzhanin, Sergey, and Evgeny Kotelnikov. "Comparison of Named Entity Recognition Tools Applied to News Articles." In _2019 Ivannikov Ispras Open Conference (ISPRAS)_, 72-77, 2019.[ https://doi.org/10.1109/ISPRAS47671.2019.00017](https://doi.org/10.1109/ISPRAS47671.2019.00017).
            - A review of different NER tools.
