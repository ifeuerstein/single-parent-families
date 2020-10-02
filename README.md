I chose this week to work on statistics of single-parent families. The Insee releases the share of single-parent families for every municipality. It could be interesting to see if there are regional patterns or if there are, for example, a higher proportion of single-parents in big cities than in smaller town.
Problem: the .csv files with each municipality only include the Insee code and not the postcode. Therefore, it is impossible to draw a map with it.
I found another .csv files giving the correspondence between Insee codes and Postcodes, with even the GPS coordinates.
I copied it as a new Excel sheet. With the function VLOOKUP, I was able to find the correspondence between Insee codes/Postcodes and Insee codes/GPS coordinates.
Now I can exploit this sheet to draw a map.
