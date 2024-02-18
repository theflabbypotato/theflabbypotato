## Hello!

Hello, my name is Evan Zhang!

I'm currently a freshman at Dartmouth College interested in studying Computer Science and Music.  Please feel free to look at around at some of the repos here!

# Private Repos:

I have some projects I've made in C and Java that I have stored as private repos:
Please just let me know if you want access!  (email: evzhang05@gmail.com or evan.l.zhang.27@dartmouth.edu)

## TSE (C):

Is basically like its own little search engine

First part of making a Tiny Search Engine:
The crawler crawls a website and retrieves webpages starting with a specified URL. It parses the initial webpage, extracts any embedded URLs and retrieves those pages, and crawls the pages found at those URLs, but limits itself to some threshold number of hops from the seed URL, and avoids visiting any given URL more than once. It saves the pages, and the URL and depth for each, in files.

Second part, Indexer:
The Indexer uses indexer.c to make the .index file. Then uses indextest.c to write the contents to a new file For indexer.c, the main function simply makes the variables, then calls parseArgs and indexBuild, then exits zero. indexBuild calls indexPage, which scans a webpage document to add its words to the index.

Third part, Querier:
The query engine responds to requests (queries) from users. The query processor module loads the index file and searches for pages that include the search keywords. Because there may be many hits, we need a ranking module to rank the results (e.g., high to low number of instances of a keyword on a page).

## Viterbi (Java):

Program makes use of the Viterbi Algorithm to categorize words into certain parts of speech. Utilizes data from Brown texts to train and test (in test subfolder)

Running Sudi.java enables the user to input words separated by a space and outputs the part of speech each word is.

Ex: Type a few words (separated by a space) to get the order of parts of speech: (input) I like eating chicken every day [PRO, V, VG, N, DET, N]

## Data Structure Implementation (C):

Implementing a Set, Counter, and Hashtable in C.
