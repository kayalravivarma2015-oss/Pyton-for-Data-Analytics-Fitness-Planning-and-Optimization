A file named cleaned_fitness_data.xlsx will be created in the current working directory containing the cleaned fitness dataset in Excel format.
output_filename = 'cleaned_fitness_data.xlsx'
Creates a variable containing the name of the Excel file where the cleaned data will be stored.

df.to_excel(output_filename, index=False)
Exports the DataFrame df to an Excel file.

index=False prevents Pandas from writing the DataFrame's row numbers as an extra column in the Excel sheet.

Exported the cleaned fitness dataset to an Excel file (cleaned_fitness_data.xlsx) using Pandas, ensuring a structured and index-free format for further analysis and reporting.
