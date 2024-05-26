# [Brave Goggle](https://search.brave.com/help/goggles) for University and College Websites

*A Goggle is a custom configuration for the [Brave Search Engine](https://search.brave.com/)*

The idea is that university websites tend to host personal sites of students and professors which contain significantly better content than the modern web.

This repository has 2 separate Goggles: 
- USA only
- Worldwide

`domains.txt` (10310 domains) and `usa_domains.txt` (2354 domains) contain just raw lists of domains created using `filter.ipynb`, which also has all the code for goggle generation.

Note that some of the websites have changed or no longer work, I didn't bother cleaning them up or anything.

Here are the [Docs](https://github.com/brave/goggles-quickstart/blob/main/getting-started.md#goggles-syntax) and [Quickstart Guide](https://github.com/brave/goggles-quickstart/blob/main/goggles/quickstart.goggle) for making Goggles (custom search result configuration) for the [Brave search engine](https://search.brave.com/goggles)

The stuff I made is under MIT License, so is [Hipo's dataset](https://github.com/Hipo/university-domains-list/) which I used.

# Other Lists and Datasets
(Other datasets that I also considered but ended up not using)
- [USA colleges by UT Austin?](https://mally.stanford.edu/~sr/universities.html)
- [Worldwide by Hipo](https://github.com/Hipo/university-domains-list)
- [University and College Webpage list by *Searchenginesmarketer*](https://searchenginesmarketer.com/company/resources/university-college-list/)

# Some thoughts

For higher quality results one could refine a list of "top" universities from around the world, and exclude any small ones.

Due to the language divide, a majority of entities on the list will never actually show up or contribute to the results. There is probably a better way to handele this caveat.