# Pokemon Analysis
Doing an analysis on Pokemon using the [data provided here](https://github.com/lgreski/pokemonData)

If you are unable to preview the code in the 'pokemon_analysis_project.ipynb' file then please use
the following link to preview the code and visuals. There is a current issue with GitHub not
showing specific types of visualizations - such as the ones I use from the 'plotly' package.

[pokemon_analysis_project.ipynb](https://nbviewer.jupyter.org/github/calvintirrell/Pokemon_Analysis/blob/main/pokemon_analysis_project.ipynb)

# Summary of findings (from the code file)

Strongest correlation of Pokemon attributes was between the Defense and Sp Defense attributes.
I'm not including the Total column as it is the sum of the other individuals attributes for an individual Pokemon.
This would naturally give it a very strong correlation to the other individual Pokemon attributes.

The blue joint plot confirms this correlation between Defense and Sp Defense given the dark blue line of data points.
The line is pointing NE at about a 45 degree angle, which shows the positive correlation between these attributes.

The box plot of Type1 and Defense shows the distribution of Pokemon Defense values grouped together by the Pokemon Type(1).
Steel type Pokemon have the highest median defense attribute value among all Pokemon.
Box plots shows the minimum, maximum, median, Q1/Quartile 1/25th percentile and Q3/Quartile 3/75th percentile of data values.
The dots above some of the box plots represent data values that are considered outliers for that particular group of data.

The same ideas apply for the second box plot of Type1 and Sp Defense values. However, the highest median Sp Defense values is
basically tied between the Fairy and Psychic type Pokemon, with the Steel type Pokemon having quite a lower median value.

Mewtwo has the highest overall Attack and Sp Attack attribute values. Eternatus has the highest overall Defense and
Sp. Defense attribute values. Regieleki took first place in the Speed attribute race with Aerodactyl completing the top 5.
