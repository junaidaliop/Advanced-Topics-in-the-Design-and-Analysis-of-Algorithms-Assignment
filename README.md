# Submission by Group 23

**Members:**
- Muhammad Junaid Ali Asif Raja (M11217073)
- Muhammad Aown Ali (M11217077)

## Project Structure

```
├── Code
│   └── apriori.ipynb
├── data set
│   ├── data.txt
│   ├── Groceries_dataset.csv
│   ├── Music.txt
│   └── README.md
├── Group23_M11217073_M11217077_Presentation.pptx
├── output
│   ├── Group23_data_bonustask4_min_support=0.05.txt
│   ├── Group23_data_task1_min_support=0.05.txt
│   ├── Group23_data_task2_min_support=0.05.txt
│   ├── Group23_groceries_bonustask6_min_support=0.05.txt
│   ├── Group23_music_bonustask5_min_support=0.0003.txt
│   ├── Group23_music_bonustask5_min_support=0.0006.txt
│   ├── Group23_music_bonustask5_min_support=0.0009.txt
│   ├── Group23_music_min_support=0.0003.txt
│   ├── Group23_music_min_support=0.0006.txt
│   └── Group23_music_min_support=0.0009.txt
├── Apriori.yml
└── README.md
```

## Description

This submission covers the implementation of the Apriori algorithm for frequent itemset mining using both packages and manual implementations. The tasks include handling various datasets and efficiently processing large datasets.

## Tasks

### Task 1: Apriori Algorithm Using Packages
Implemented the Apriori algorithm with `mlxtend` for `data.txt` with `min_support=0.05`.

### Task 2: Apriori Algorithm Without Packages (min_support=0.05)
Implemented the Apriori algorithm without packages for `data.txt` with `min_support=0.05`.

### Task 3: Apriori Algorithm Without Packages (min_support=0.0003, 0.0006, 0.0009)
Implemented the Apriori algorithm without packages for `Music.txt` with various `min_support` values, efficiently handling large datasets.

### Bonus Task 4: Apriori Algorithm Using R (min_support=0.05)
Implemented the Apriori algorithm using R for `data.txt` with `min_support=0.05`.

### Bonus Task 5: Improved Apriori Algorithm (FP-Growth) for Music Dataset
Implemented the FP-Growth algorithm for `Music.txt` with `min_support` values of 0.0003, 0.0006, and 0.0009 for improved performance.

### Bonus Task 6: Analyze Shopping Behavior with Groceries Dataset
Applied the Apriori algorithm on `Groceries_dataset.csv` to analyze meaningful patterns of shopping behavior with `min_support=0.05`.

## Usage

### Jupyter Notebook
Open `Code/apriori.ipynb` in Jupyter Notebook to run and view the implementations.

### Output Files
The output files for each task are stored in the `output` directory, named appropriately for each task and minimum support value.

### Setting Up the Environment

To set up the environment using the provided `Apriori.yml` file, run the following command:

```bash
conda env create -f Apriori.yml
```

This will create a new conda environment with all the necessary dependencies.

## Presentation

The project presentation is available in `Group23_M11217073_M11217077_Presentation.pptx`.

## Author

**Group 23**
- Muhammad Junaid Ali Asif Raja (M11217073)
- Muhammad Aown Ali (M11217077)
