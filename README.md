# correlation-visuals

I’ve been dealing with some fairly wide data sets (70-100 columns), and trying to get a sense of the correlations between so many variables and my target has been challenging. In looking for some alternatives to a really big table or heatmap, I’ve put together three options and show it here using a small portion of the FIFA data set.

* **Grouped scatterplots** - This is basic but seemed like a cleaner way to combine sets of variables and into more easily digestible chunks.
* **Barplot** - This shows the correlation value for all variables and colored based on statistical significance.
* **Dendrogram** - Made using agglomerative clustering of features by their correlations. This was a challenge to color the clustered groups using ggplot (rather than the generic plot finctions)

I’m sure there are better and cleaner ways to do these things, feel free to suggest alternatives!

<img src= https://github.com/Jeffrothschild/correlation-visuals/blob/master/Example%20corr%20bar%20plot.png width="400" height="600" />

<img src="https://github.com/Jeffrothschild/correlation-visuals/blob/master/Example%20colored%20dendrogram.png" width="600" height="600" />

