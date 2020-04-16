# financial-statement-preprocessing
Extracting information from financial statement

#Requirement
alphalens==0.3.2
nltk==3.3.0
numpy==1.13.3
ratelimit==2.2.0
requests==2.18.4
scikit-learn==0.19.1
six==1.11.0
tqdm==4.19.5

#Code Structure
1. Download document 10-KS (from www.sec.gov)
2. Clean data using BeautifulSoup
3. Analysis the data with many methods such as Bag of Word, Jaccard Similarity
4. Evaluate Alpha Factors
