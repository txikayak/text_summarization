# text_summarization
Aim: An extractive text summarization for PubMed article abstracts

Citation: The core of this extractive text summarization is based on Ng Wai Foong's post: Extractive Text Summarization Using spaCy in Python https://medium.com/better-programming/extractive-text-summarization-using-spacy-in-python-88ab96d1fd97

Modifications from my side: 
1) Tracking case sensitive terms and replace them in the summary 
2) Replacing "We" to "The authors" and "Our" to "The authors'" 
3) Normalized "Conclusion:" etc into "In conclusion" and give additional weights to these sentences 
4) Additional text cleaning
