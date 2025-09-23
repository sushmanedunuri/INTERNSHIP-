 Task 1 – Data Cleaning and Preprocessing  

Objective  
The purpose of this task was to clean the given dataset (Medical Appointment No-Shows) and prepare it for further analysis.  

What I Did  
1. Checked for missing values → none found.  
2. Looked for duplicate rows and columns → none found.  
3. Renamed all column names to lowercase and replaced spaces with underscores.  
4. Cleaned categorical values:  
   - Gender column changed to Male/Female  
   - No-show column changed to Yes/No  
5. Converted date columns (scheduled day and appointment day) into proper date format and removed timezone.  
6. Fixed age column by removing 1 invalid record (negative or >120).  

 Final Dataset  
- Rows: 110,526  
- Columns: 14  
- Saved as: `medical_appointments_cleaned_final.xlsx`  

This Excel file has:  
- Cleaned_Data** → cleaned dataset  
- Data_Cleaning_Report** → summary of what I did  

 Learnings  
- Understood how to check for missing values and duplicates.  
- Learned how to standardize categorical values.  
- Realized the importance of validating data like age and dates.  

