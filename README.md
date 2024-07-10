# Investigating-The-Influence-of-Sentiment-on-Financial-Time-Series

## Author:
Sean Dowling

## File Description:
This code accompanies the dissertation titled "Investigating the Influence of Sentiment on Financial Time Series." 
It contains implementations related to the experiments conducted in the thesis.

All scripts are run in Python bar the scripts in the GRETL_Scripts directory, which are run in the GRETL script editor.

[Convert_pdf_txt.py](Convert_pdf_txt.py) converts the downloaded article .pdf files into .txt files.

[Combine_txt.py](Combine_txt.py) combines article .txt files into one .txt file.

[Compile_Data.py](Compile_Data.py) calculates and aggregates the time series data required for the project.

[Get_Returns_Distribution.py](Get_Returns_Distribution.py) & [Get_Returns_Summary_Stats.py](Get_Returns_Summary_Stats.py) are used to analyse the financial returns time series.

[Run_Returns_VAR.inp](GRETL_Scripts/Run_Returns_VAR.inp) & [Run_Absolute_Returns_VAR.inp](GRETL_Scripts/Run_Absolute_Returns_VAR.inp) run the VAR models in GRETL.

[Run_Returns_Rolling_VAR.inp](GRETL_Scripts/Run_Returns_Rolling_VAR.inp) & [Run_Absolute_Returns_Rolling_VAR.inp](GRETL_Scripts/Run_Absolute_Returns_Rolling_VAR.inp) run the rolling VAR models in GRETL.

[Plot_Rolling_VAR_Results.py](Plot_Rolling_VAR_Results.py) is used to analyse the results of the rolling VAR models.

