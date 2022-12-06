# Climate_Statistics

This repository contains an analysis of average monthly rainfall in Melbourne, Australia, and Oxford, UK, from the year 1855 to the year 2015.

To run this analysis start by using the following command to combine average rainfall data from the two cities:

  `Rscript src/Combine-Data.R`
  
The input data is in `data`. The dataset generated by this command can be found in `out`.

To proceed with analysis, run the following command:

  `Rscript src/Make-Plot.R`
 
 Again, the input data can be found in `data` and the output can be found in `out`.
