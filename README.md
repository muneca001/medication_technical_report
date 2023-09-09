# Cancer Treatment Study Analysis Readme

## Project Overview

In this project, I analyze data from a cancer treatment study involving 249 mice. The study evaluates the effectiveness of Capomulin compared to other treatments for squamous cell carcinoma (SCC), a type of skin cancer. A full analysis of my findings can be found at the top of the jupyter notebook file.

## Tasks

1. **Prepare the Data**

   - Merge data files.
   - Remove duplicate time points.
   - Verify unique mouse IDs.

2. **Generate Summary Statistics**

   - Calculate mean, median, variance, SD, and SEM for tumor volume by drug regimen.

3. **Create Charts**

   - Generate bar charts for total timepoints per drug regimen.
   - Create pie charts to visualize gender distribution.

4. **Identify Outliers**

   - Calculate quartiles and IQR.
   - Detect potential outliers.
   - Create box plots.

5. **Visualize Data**

   - Plot tumor volume over time for one mouse.
   - Generate a scatter plot of mouse weight vs. tumor volume.

6. **Correlation and Regression**

   - Calculate correlation between mouse weight and tumor volume.
   - Perform linear regression analysis.

7. **Conclusion**

   - Summarize key findings at the top of the `ETL_Project.ipynb` file.

## Files

- `ETL_Project.ipynb`: Jupyter Notebook with code.
