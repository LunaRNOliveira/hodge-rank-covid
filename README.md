# HodgeRank Method

The present notebook provides a complete code in *Wolfram Mathematica Language* to determine the ranking, the inconsistencies, the matrix plots, and the graphs obtained via HodgeRank Method applied in Social Representation Theory.

Observe that here we chose to follow the standard convention, where the average used in the calculation of the flows is the score difference and inner products in $0$-cochain and $1$-cochain have, respectively, unit weight and weights equal to the number of individuals (voters) who cited the words $i$ and $j$.

- The **input** of such a code must be a .csv file (a table with the lines presenting all the individuals (voters) and the columns represented by all the words. The elements are $0, 1, ..., 5$ depending on the ranking of each individual (voter)).

- The **outputs** are:
  1. The ranking table (.tex);
  2. The ranking table (.csv);
  3. A table with the reability of the ranking and some aditional information (.pdf);
  4. The flow edge matrix (.pdf);
  5. The potential gradient matrix (.pdf);
  6. The $R^*$ matrix (.pdf);
  7. The legend bar for the above matrices (.pdf);
  8. A graph whose edges indicate the weights (.pdf);
  9. The legend bar for the above graph (.pdf);
  10. A graph whose edges indicate $R^*$ (.pdf);
  11. The legend bar for the above graph (.pdf);

 
Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
 




