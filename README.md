# Analyzing Linux Kernel Development History <img src="Tux.svg.png" alt="Linux Kernel" width="100" height="100">


## Introduction

This project involves analyzing the evolution of the Linux kernel, one of the most well-known open-source projects. The Linux kernel serves as the core of various Linux distributions, including Debian, Ubuntu, and CentOS. The dataset used for this analysis contains the history of kernel development spanning almost 13 years, from early 2005 to late 2017. The primary goals of the project are:

1. Identifying the top contributors who have made significant code commits to the Linux kernel.
2. Visualizing the trends in commits over the years to understand the development activity's progression.

## Project Structure

The project follows the following structure:

- `datasets/`: Contains the dataset files used for analysis.
- `notebook.ipynb`: Jupyter Notebook containing the entire analysis process.
- `README.md`: This document, providing an overview of the project.

## Analysis Steps

1. **Reading the Dataset**: The dataset, obtained by running Git log commands, was loaded into a Pandas DataFrame to be processed.

2. **Getting an Overview**: Basic statistics, such as the number of authors and commits, were calculated to provide an initial overview of the dataset.

3. **Finding the Top Contributors**: The top 10 contributors with the most commits were identified to understand their impact on the project.

4. **Data Wrangling**: The dataset was cleaned and manipulated to ensure accurate analysis. Incorrect timestamps were dropped, and the dataset was prepared for further processing.

5. **Grouping Commits per Year**: The commits were grouped by year, and the number of commits for each year was counted.

6. **Visualizing the Development History**: The results were visualized using bar plots to illustrate the growth of development activity over the years.

## Usage

1. Clone the repository to your local machine.

2. Ensure you have the necessary libraries installed by running: `pip install pandas numpy matplotlib`.

3. Open and run the Jupyter Notebook (`notebook.ipynb`) to execute the analysis.

4. The notebook provides detailed comments and explanations for each step of the analysis.

## Conclusion

The project's analysis and visualization reveal insights into the development activity of the Linux kernel over the years. The growth in commits highlights the continuous effort and collaboration of developers, with no sign of decreasing development activity.

