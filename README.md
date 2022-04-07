# BooleanRetrievalModel
A simple CLI-based Boolean Retrieval Model that processes boolean, positional and phrase queries using C++
To run this cpp file, Visual Studio Code is required.

Additionally, as C++ does not include a built in stemming library, an online stemming library by the name of oleanderstemminglibrary (which has been included in the zip) must be included in the same directory as the code at the time of execution, alongside the Abstracts folder (unzipped) and the Stopword-List.txt file as well.

NOTE: The code may take upto 5-10 seconds to run, so please wait in case it doesn't do anything initially, it is not broken.

This code supports queries of the form:

{Boolean/Complex Boolean}

1. w1 
2. not w1
3. w1 and/or w2
4. w1 and/or not w2
5. w1 and/or w2 and/or w3
6. w1 and/or not w2 and/or w3
    w1 and/or w2 and/or not w3
7. w1 and/or not w2 and/or not w3

{Proximity Queries}

8. w1 w2 /n (n being the distance between w1 and w2) 

{Phrase Queries}

9. w1 w2 w3

