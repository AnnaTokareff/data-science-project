# Data Science Project

This folder contains code and dataset for the project of Data Science course.

To install the environment needed:

```bash
conda create -n data python=3.9
conda activate data
python -m pip install jupyter
python -m pip install -r requirements.txt
```

For M1/2 Macbook users, use this command to install spacy:

```bash
python -m pip install 'spacy[apple]'
```

To run the code, make sure the code notebooks and the dataset directory are in the same folder, as the file paths for importing data in the notebooks are relative paths.

- Part 1:
  - Code: [part_1.ipynb](part_1.ipynb)
  - Dataset (directory): [part 1 dataset](./part1_dataset/)
- Part 2:
  - Code: [part_2.ipynb](part_2.ipynb)
  - Dataset (csv file): [part 2 dataset](part2_dataset.csv)
