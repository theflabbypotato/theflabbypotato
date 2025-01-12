## Hello!

Hello, my name is Evan Zhang!

I'm currently a freshman at Dartmouth College interested in studying Computer Science and Music.  Please feel free to look at around at some of the repos here!

# Private Repos:

I have some projects I've made in C and Java that I have stored as private repos:
Please just let me know if you want access!  (email: evzhang05@gmail.com or evan.l.zhang.27@dartmouth.edu)

## Leveraging YOLOv8 Deep Learning Model for Barnacle Detection:

I developed and trained a YOLOv8 object detection model to identify and count barnacles based on hand-annotated images in CVAT.  Iteratively improved the model’s performance by augmenting the dataset and refining annotations.

- Iteration 1: Initial dataset of ~20 images resulted in low confidence (~0.015).
- Iteration 2: Enhanced dataset with ~50 more images and augmented the data with rotated images, improving model confidence to 0.6–0.7.
- Iteration 3: Added hundreds more manually annotated images, totaling 250, achieving >0.8 confidence with pretty effective detection results.

## Space Adventure:

Space Adventure is a Space-Themed Game where the player wanders around exploring a spaceship. The goal is to ultimately figure out how to entire the cockpit and move the spaceship to a mysterious green portal.

I made this game to learn about VR/AR development in Unity. I watched tutorials by Valem Tutorials on Youtube which was super helpful. The majority of the assets here come from Valem.

**Parts of the Project**

- Built the environment using space prefabs
- Lighting
- Grabbing script for objects and interactions
- Movement and teleportation on right hand
- Button and door interaction
- Ladder
- Wheel and lever for "moving" the spaceship
- Game story with narration
- Menu and UI
- In-game audio
- Optimizing build (like baking)

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
