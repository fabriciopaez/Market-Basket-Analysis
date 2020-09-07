# Market-Basket-Analysis
This is an  introduction to Market Basket Analysis using Python, in the notebook you can find the basic theory, and some functions I made to enhance the analysis of 2 Business Case

There are many data analysis tools available to the python analyst and it can be challenging to know which ones to use in a particular situation. A useful (but somewhat overlooked) technique is called association analysis which attempts to find common patterns of items in large data sets. While these types of associations are normally used for looking at sales transactions; the basic analysis can be applied to other situations like click stream tracking, spare parts ordering and online recommendation engines - just to name a few.

If you have some basic understanding of the python data science world, your first inclination would be to look at scikit-learn for a ready-made algorithm. However, scikit-learn does not support this algorithm. Fortunately, the very useful MLxtend library by Sebastian Raschka has a a an implementation of the Apriori algorithm for extracting frequent item sets for further analysis.
