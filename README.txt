Way to run my file( example query, no slashes, 3 arguments):
"python3 TFIDF.py allqueries.json cacm.rel project1-index"

Krovetz stemming + Stopword( to remove words like 'there', 'this') removal for Vocab
Stopword removal + Krovetz stemmming for queries
I am using log with base 2 for my idf values
Results will be pushed in batches( not in one go)

Output mentions query no,  document number, ranking,and Cosine similarity in that order
Time taken to finish working on cacm100 index( 2250 words, 100 docs, 59 queries) was roughly 7-7.5 mins


Contents of Project1 folder: TFIDF.py , README file, report.pdf( also submitted on Gradescope),outputokapi.txt( cacm100 for okapi), tdfidfoutput(cacm100 for tfidf), tfidfoutputfullcorpus( whole corpus for tfidf)
REMARK: Stemming does decrease the vocab size, but aggressively increases the size of retrieved list( more matching)
Thereby making the runtime go up.
