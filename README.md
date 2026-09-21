# Pandas Practice Workbook: Netflix Dataset

A hands-on pandas workbook prepared by Nageshwor Sharma. The notebook contains 125 practice questions using a cleaned Netflix catalog dataset.

## Contents

- `Nageshwor_Sharma_workbook.ipynb` - The complete workbook with questions, Python code, and explanations.
- `netflix_clean.csv` - The dataset used by the notebook.

## Dataset

The CSV contains 550 rows and 12 columns:

`show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, and `description`.

The data includes both movies and TV shows, along with metadata such as release year, rating, duration, country, genres, and descriptions. Some text fields contain missing values, making the dataset useful for practicing data cleaning.

## Workbook Sections

| Section | Topic | Questions |
| --- | --- | ---: |
| A | First analysis of the data | 15 |
| B | Selection with `[]`, `.loc`, and `.iloc` | 25 |
| C | Conditional filtering with `.loc` | 20 |
| D | Sorting | 10 |
| E | Updating data | 15 |
| F | GroupBy analysis | 20 |
| G | Data cleaning | 20 |
| **Total** |  | **125** |

## Requirements

- Python 3.9 or newer
- Jupyter Notebook or JupyterLab
- pandas

Install pandas and Jupyter with:

```bash
python -m pip install pandas jupyter
```

## Running the Workbook

1. Open the project folder in VS Code or start Jupyter from this folder.
2. Open `Nageshwor_Sharma_workbook.ipynb`.
3. Ensure the notebook is using a Python kernel with pandas installed.
4. Update the CSV path in the first code cell if needed. For a local copy in this project folder, use:

```python
df = pd.read_csv("netflix_clean.csv")
```

5. Run the cells from top to bottom.

The original first cell uses `/content/netflix_clean.csv`, which is appropriate for Google Colab. The relative path above is recommended when running locally.

## Learning Goals

By completing the workbook, you will practice:

- Loading and inspecting tabular data with pandas
- Selecting rows and columns with multiple indexing methods
- Writing reusable filtering conditions
- Sorting and ranking records
- Modifying values and creating updated columns
- Summarizing data with `groupby`
- Handling missing values and cleaning text and numeric fields

## Notes

The dataset is intended for learning and practice. Results depend on the values in the supplied CSV file, and some questions may modify the DataFrame during execution. Restart the kernel and rerun the notebook from the beginning to reproduce a clean analysis.
