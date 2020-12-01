# Biomedical-Text-Summarization
A combination of k-means clustering and Apriori frequent itemset mining on the concepts obtained using application of UMLS concept mapping on Biomedical Text to achieve summarization.


Throughout the last decade, the scientific community has been increasingly paying close attention to document summarization. Quite recently, because of the immense growth of knowledge available to doctors and researchers in medicine, through the vast and increasing number of published papers, electronic medical records, etc. it has attracted the attention of the medical research community.

  In this project, we implement a graph representation-based text summary technique using the Unified Medical Language System (UMLS), an ontology information database from the National Library of Medicine (NLM). A combination of k-means and apriori frequent itemset mining is used.  For clustering related sentences, the K-means with cosine similarity algorithm is used. The Apriori algorithm is then implemented to discover the frequent itemsets between the clustered sentences. Finally, to construct the summary, the crucial sentences from each cluster are chosen using the discovered frequent itemsets.


  For the evaluation step, we query wikipedia to gather biomedical data. The rouge score which is a popular measure for text analysis is used to compare the proposed method with the existing methods such as the Gensim, TextRank and Cosine method. We particularly use the Rouge-1, Rouge-2 and Rouge-L for the comparison.
  
  
Download the metamap library from here: [Metamap](https://metamap.nlm.nih.gov/MainDownload.shtml)
