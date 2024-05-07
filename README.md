# Netflix Dataset Analysis

Welcome to the Netflix Dataset Analysis repository! This project is dedicated to cleaning, analyzing, and visualizing data from Netflix. Our analysis focuses on uncovering insights into the types of shows available, the distribution of movies and TV shows, director contributions, and much more.

## Dataset

The dataset used for this analysis is sourced from Kaggle, a platform for predictive modelling and analytics competitions. It contains detailed information about the movies and TV shows available on Netflix up to 2021. You can access the dataset using the following link:

[Netflix Data: Cleaning, Analysis and Visualization](https://www.kaggle.com/datasets/ariyoomotade/netflix-data-cleaning-analysis-and-visualization)

## Repository Contents

This repository contains the following files:

- `analyse.ipynb`: A Jupyter notebook containing all the Python code used for the data cleaning, analysis, and visualization. This notebook is well-documented with markdown cells explaining each step of the process.

- `netflix1.csv`: The dataset file that contains data about Netflix movies and TV shows.

## Analysis Overview

The analysis covers various aspects of the Netflix data, including:

- **Data Cleaning**: Renaming columns, handling missing values, and converting data types.
- **Exploratory Data Analysis (EDA)**: Analyzing the distribution of content types, the popularity of different genres, release patterns, and ratings.
- **Visualization**: Creating visual representations for a better understanding of the data using libraries like Matplotlib and Seaborn.

## Visualizations

This project includes a variety of visualizations to aid in understanding the data better:

- Pie charts showing the proportion of Movies vs. TV Shows.
- Bar charts depicting the top countries producing Netflix content.
- Histograms visualizing the distribution of release years.
- More complex graphs showing the frequency of different ratings among directors and genres.

## How to Use

To view the analysis:

1. Ensure that you have Jupyter Notebook installed, or use an IDE that supports IPython Notebooks.
2. Download `netflix1.csv` and `analyse.ipynb`.
3. Open the `analyse.ipynb` file in Jupyter Notebook to view and run the code.

## Connect With Me

If you have any feedback or would like to discuss this project further, feel free to connect with me on my professional and social platforms:

[![LinkedIn](data:image/png;base64,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)](https://www.linkedin.com/in/abd-el-rahman-eldeeb-a9bab6251/) &nbsp;
[![GitHub](data:image/png;base64,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)](https://github.com/ElDEEB21) &nbsp;
[![Kaggle](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAkFBMVEX////u7+8gvv/t7u739/fv8PD+/v709fX5+fkAuP8Atf/58+7N5PISu/8At/////tSyv+Z3v5pzf//+/au5P645/7D6/779fD4/f9BwPyP2f6Y2v+L1v/w+f+d3f5pzv7Q7/7d9P7k7fC23vV60fu/4PTf7var2faf1vZQwfv98+zV6fek3/rC4fPm9/+Kz/j6OGTCAAAIsElEQVR4nO2dbXeiPBCGAQkICPJgq5W21vra3b7s//93j1qCVEgmCSgZynzYc5qzvXeuDUlmkjAYBjXXzIzkTSRrGdi0xRnQJoc2DfMmLaVMozmtnrAn7Al7wp5QK7euRDjIrKBFmwpa1Apa1DSVcqnZQ2p5U95il5t4v6eVlEE7czDk9LmdNRX+J4dBZpO86fgTUZAitMnNmwaKXlVIyREWRsPdJqmwl9Qk0lJ0YJmKhHwpVcLUD60KC6N41RHCqIrvaNGIdIJw4rMIvZ6wJ9SEcMwkVBmHNVcLvpRBqA2dzIblJpu2uFnDjNOHrpyU47jlJjWvKqXOqBXxkVmKj4ysIWDOpd5IUko6alOVkotxAUIZKU1zi56wJ+wJe8KeUHQXoxvrYUX0YGYtplOKHojx3cCNS+WkHKMciBj09+pLOY1H3r565N1EXFqW6nOLX0vIzp66QniVcYiEsCt9iOkpzVfGglZp/bQv110eoSknVTiIKBAqeVUpZdhKxt7FiEZDNclr2RlV6pRHOmrT4BjrN0TePWFP2BP2hDfI8ZsjlJECCOtKmUaeC5/T4zxjznNoO/9bWabNJZSTImb5bOLsVm0pwo2P8v+2PD6ifS4dtbGlpKM2Sak+e2JoYcot1Ah554fdIOx+HzZ7yq0jYfd3MTARNr0eRtqthxUxTbnJvggVXHZME43kpEjlfQslr6qlzqg0Ahw0F5cKSYnFpcpSvyu36Al7wp6wJ7zZLkbVzfcGVgumlPxqISVlGmovQvCyJ+l3Kngu1Jf6BWdPtDObyoC7kj11PwP+zbsY3X9Ku0/Ylaf0N+9i+NrtYuTW2fulZy2T2eddibx7wp6wPuGYvj0d5L83+f6Z4Cdc7mOObbYBdsJp5IUc87yRKyqlJ+Ejc3mlqm+2oBSPsLzy3Ojm3viRqUYtegyEpKrWQ7XtBV72ZEvuVIwXUA9aobe7ddWI+rnFuX+fwB4MrQcxqQarRrAjb+ns6QPuwfAZc/a0qKw+8bMHnwW90jJ7gieZcP4s6pWO71tMwUc0ih+EvdLwKYVnUe/lQdwr/QgFxmDWg0gJ70FAL3mQ8ap6teAd8qtUjfBFq0bYMGCUrDBXjZjCPXh4RBHvYtx5YA8eJxm8GfAUBPROkwxaQpEx+CDtlUaEAoB7R94rfQjhScZ/Gyt4pQ0hPMn467GKV7oQCkwytAdRVo2YwGPQ3wdqXmlRNUIkVLs3MFeNEJhk7gzMVSMEJpmp0QBhazk+PMlEd4YehGrZEzwGrXtDE0KlcQgChtbS0J+Q3YfgIxqGU/qL7RMqPKV30K5aGL7mXjVJmK+M1725d+hBcBBuZzW9qr6poFaKQbZqxCGSgQC95aRWdQiWnVGvevYkNskgrhohEGxPDczn+PAk473+cAsbITjJePPpT7eQEe6gScb7M7xwCxfh1BIFREo4nYOAdsktTFUjVny8I+BfkfctahBWbPk3WDXCBsdgUnVigqdqxA6cRWPj6vdLaWdeI3tywUkmKT52Wt2CFsothuAkE7Pcap9Q5H2LFTgGY6Zb7RMK9OEQAgwTtls6E9IbQy70iEYpx632CcFdDAlAnITgJOOnaN+3OFWNINAyEabFS7/XXQ951xhUq0bY4DqY4q4aAY5BP61+7JBUjXi3wYU+hdzSO3t6/yPSg4gJQzDYXsBuaU0IWfQu4BZmwnAt4hZqwkWLhBXz8oClpf6U5udL6qsF06vbVI0ACS2CvGoEjDgPzKKUdNQme/ZEO7OpDBg2b8MYWFrlFjX68IgY6E9Ypw8PD+pnoD1hrT482KjqpdAuEYbzXccJrTCpeO1VK0L2LoagRR9odzFEO9H7OLt13V2M3Bq6XyqMGO6oPLKqEeKI1opcPHadyC2KiMmq44RW+BZ0nNDy1gF2QvCq15agJgzj7Rz4G4dMCjGhN1/NlsC6GcbklrsY7HxS4ubeGTA+xp5rcHfYlF0P264akfeO9XyUIi/QGc2nw3NBslTmLapGZBZtaJkA8BDjK99tUoxLb1w14tu8f+NMinxCnXjIpDLTKbcA+jD6BjwRzj6AMevFfzUk5PdhtHDOUoPhG4SYEmSE0dNPqb/QgWl0im30IuQ9pd7b5ELqGTwTHhFEhGE6vJQiI+A5DeeEoCH09kFJamCnEGJM1FcLk79a8A75VapGeJVVI+wn4La+t5m5hdsIal61WzUiBocill0M1pvOIyiR8l+R5BYswmAPPKfh/As34WC2hyK9ZJL/gxgJDz8k0FDcYCck4JXajwA1oWmv+IB0awovoRnAL6t/7xLfbBej8aoRAbjwJ6vG18OK6OGKVSMmCYQYj49xCOKqEa98wGMmdeoUJa90qBphGEvwnfVpA4RtVoacrKEtVOtVB8IaNffIBgrf/uhAWKP2pTmD9hfDRGtCuG6iCw/FNGidsFZlyAAswxO9k+YI85XxulUjilKEvIG9+E4UvGqzasSFTWIwWdwJyAjZGfWmFcu/wNnmn4JXWtW+/AKPdhbyXrWfWxSlPsFKEnfICY0UGorREDmhAe0vhnPUFVoPtuQDfle6xkzoBFsQcY+gagRPKlhDs42/nch41UbVCL7UDBqKlvUu41ULVSMgqQdw4bfGEl41+b5FU18OgM9ON464V9rkFkWpe2goRh/tEDb3lU7opobl3+PuQ8MANzWslV6E0t+ZGYP1M46xDapdjEu3wC3UU/15zITGFhqK3uNYo/ctIvmvdLob8AT8vsZ6yLvGoFo1QrrUA7zwL7WqGiFf6kEgtkH+7TyBCrznL87gJIS/ixStRaUaIuTMpWqJ+QK8F3ZjQuZTdawKoULozCHEGxM++V6lnT4ippSYP/9jSGbm35bQtHf/VVoqL5W75T4lbEuX9QkrpviBgNakvPKoSo2DYDYLDn/8/FruqW0iJ1W7asS1Sz00KNVkfQY9pRQj72u/ntz+GXBPqJFUT9gT9oTtS3Wf8H+O/KnynnkcNgAAAABJRU5ErkJggg==)](https://www.kaggle.com/abdoreldeeb)


Feel free to contribute or suggest improvements!

Thank you for visiting this repository, and I hope you find the insights from this analysis useful!
