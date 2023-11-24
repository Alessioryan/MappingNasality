# MappingNasality

The goal of this notebook is to take the Phoible database and visualize the percentage of oral and nasal vowels/consonants in a variety of the world's languages. 

To do this, we will take the data available in Phoible, and:
- Calculate the number of oral/nasal vowels/consonants in each language, using the features NASAL and SYLLABIC to determine whether a phoneme is nasal and a consonant.
- Add each inventory (TODO: HOW TO HANDLE DUPLICATES) to a new dataframe with Glottocode, num_oral_cons, num_nasal_cons, num_oral_vowel, num_nasal_cons

After, we will add the x_coord and y_coord to this dataframe, and the result will be plotted in QGIS.