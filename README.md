# Circos-Plot
Circos is a software package for visualizing data and information. It visualizes data in a circular layout — this makes Circos ideal for exploring relationships between objects or positions. There are other reasons why a circular layout is advantageous, not the least being the fact that it is attractive.

Circos is ideal for creating publication-quality infographics and illustrations with a high data-to-ink ratio, richly layered data and pleasant symmetries. You have fine control each element in the figure to tailor its focus points and detail to your audience
Circos is flexible. Although originally designed for visualizing genomic data, it can create figures from data in any field—from genomics to visualizing migration to mathematical art. If you have data that describes relationships or multi-layered annotations of one or more scales, Circos is for you.



in the above code we have used these three libraries to plot the circos plot of our data
library("RCircos")
library(circlize)
library(dplyr)
we have used this data for human geneome
data("UCSC.HG38.Human.CytoBandIdeogram")
First of all we build the basic chromosome ideogram and take my deg file that contains log2 fold change values and p values

Intersect deg gene name with biomaRT 'hgnc_symbol' gene name
and then plot the circos plot


output:

![circos](https://user-images.githubusercontent.com/110675838/198817920-2894168a-362c-4d61-9e80-626b88b3cbe5.png)
