# Approximate deduplication at scale: LSH to the rescue

## Description
Recent advancements in deep learning have opened a pandora box of applications utilising NLP tehcniques to solve buisness problems. But one of the important tasks starts at the pre-processing stage which involves deduplicating similar documents. Though one can use various algorithms like jaccard distance, cosine distance, jaro winkler, levenshtein distance(depending on the document size and the nature of data) to find the similarity among documents, scaling them to a dataset of around millions is not a very time optimsed approach as the number of operations scale in the order of O(N^2). In this talk I will talk about LSH and minhash based deduplication approach which at a small comprise on accuracy can quickly reduce the problem to O(N) complexity, which when put in actual numbers reduced our pre-processing time from around 48 hours to around 15 mins for a problem involving deduplicating millions of company names.

## Duration
- [ ] 30 min
- [x] 45 min

## Audience
> This talk is intented for people who are interested in ML engineering especially in NLP domain and basic familiarity in Python, probability and algorithms should be sufficient enough.

## Outline
- Detailed description of the problem statement
	- Application of deduplication in practical cases
 - Walthrough of the results and time complexity of the solution based on LSH
	 - Using Minhash based LSH in python
	 - Performance improvement as compared to naive approach
	 - Comparative analysis of results obtained from probabilistics and determinsitic approaches
- Minhash based document similarity 
	- Abstraction of Similarity of documents
	- Jaccard similarity and its approximation my Minhash
-  Theoretical understaning of how LSH works
	- Selecting the signature size and bucket size


## About Myself
I have around 5 years of exprience in machine Learning domain with exposure to multiple industries like Fintech, Insurtech and eCommerce. I have worked on differnt problem statements like recommendation engines, lead generation and information extarction. I personally like to work on developing machine learning products and one of the product we developed at my last company is currently used on millions of financial transactions daily.
 LinkedIn: [https://www.linkedin.com/in/chirag-yadav-85227340/](https://www.linkedin.com/in/chirag-yadav-85227340/)

---

- [ ] Don't record this talk.
> Check this if you don't want your talk to be recorded.