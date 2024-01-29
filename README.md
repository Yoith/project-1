## Shark Attack Study

### Overview

This repository contains data and analysis regarding shark attacks, focusing on geographical patterns, gender distribution, and human-induced factors. The study aims to provide insights for understanding and preventing shark attacks.

### Contents

- **Data Analysis:** Explore data on coastal hotspots, gender-specific patterns, and human-induced shark attacks.

- **Jupyter Notebooks:**
  - **exploring.ipynb:** Accesses information in the 'attacks.csv' file, providing an overview of the DataFrame, including basic information using functions like `.info()`, the number of columns or entries, null and unique values.
  
  - **cleaning.ipynb:** Imports libraries such as seaborn, matplotlib, pandas, numpy, and pycountry. Renames columns, drops rows with null information, removes irrelevant columns, and eliminates duplicates. Introduces functions like `strip_columns(df)` for unified column modification and `filter_oceans()` to filter countries and remove seas and oceans from the list.
  
  - **visualization.ipynb:** Imports the modified CSV file from the cleaning stage and creates bar plots, pie plots, and line plots with relevant information for the study, utilized for the final presentation.

- **Images:** The 'images' folder contains all the plots and visualizations generated during the study.

### Conclusions

The study concludes that male American surfers currently face a higher risk of shark attacks compared to other demographics worldwide. This insight serves as a valuable cautionary note for individuals engaged in surfing activities, particularly in the American coastal regions.

### Recommendations

- **Safety Measures:** Consider implementing targeted safety measures for surfers, especially in regions identified as hotspots.
  
- **Public Awareness:** Raise awareness about the increased risk for male American surfers and promote cautious behavior in shark-prone areas.

### Usage

Feel free to use the data and findings for educational or research purposes. Please attribute the source appropriately.

### Cautionary Note

If you are an American surfer, exercise caution in waters identified as shark hotspots. Understanding the risks and adopting safe practices can contribute to a safer surfing experience.

### Author

[Guillermo Diaz]