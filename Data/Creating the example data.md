## Creating the example data which simulates GP Microbiome output

Due to time constraints and the limitations of my computer, it did not make sense for me to generate example GP Microbiome output by simply running that program on several example input files. I did create a small example file called example_output.p this way,  to enable users of this repository to run readsample27. However CF data input files were significantly larger and the csv files created from example_output.p in readsample27 would not have been suitable for the plotting program. 

To demonstrate my plots of the output from GP Microbiome, I could have simply randomly generated some relative abundances and then applied random weights to them, as I did in Leave_One_Out_Example to create a second version of one of my example GP Microbiome output files. That code applied weights to one of the example files I had created in the more manual fashion described here. Although the process I describe here was very similar to the one in that program, it wasn’t exactly the same. 

I wanted the plots to look as similar in nature to the real ones, and to have the bacteria of interest show up as prominently as they did in the CF data, which had a high proportion of zeros. I wanted them to have a similar range of values in general, which differed for each of the 245 OTU’s.

Zero-inflation was one reason why GP Microbiome was an appropriate tool for our data. GP Microbiome calculates noise-free relative abundances from observed relative abundances, and can make predictions for noise-free relative abundances between time points or in the future. For more on the program, see the related research article [here.](https://academic.oup.com/bioinformatics/article/34/3/372/4157442)

This means that the real plots don’t simply look like predicted and actual relative abundances, as they would be if this were purely a prediction algorithm. Some show the observed and noise-free compositions as very similar, and others show major differences – as you might expect if it is accurate. 

I wanted to portray the output realistically, and not misrepresent the algorithm. It took too much computing time on my 6-year-old machine for me to run 5 times on example input – this was much faster.
### With this in mind, I took the following steps:
1. I scrambled the order of actual output from multiple participants, and created a relative abundance table, eventually know as Example_rel.csv and contained in this repository. 

2. I altered the table, moving some values into rows for bacteria of interest, adjusting some to be more realistic since the time points were scrambled, and making a few other small changes while still keeping all columns summing to 1.  

3. I divided the table into ‘participant’ relative abundance files and imported into Python. All details of participants, ages, time points, and other metadata were fictional. Applied random weights within a range from about .5 to 1.5 (which differed depending on the values), for both the noise-free compositions and predicted noise-free compositions. Adjusted so that the columns summed to 1 and made a few minor edits such as moving more non-zero values into the ‘bacteria of interest’ rows where desired. 

4. I previewed the plots, and made a couple of other minor adjustments to make them more realistic.
