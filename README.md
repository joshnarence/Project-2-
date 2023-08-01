# Project-2-


Extract, Transform, and Load

Extract data from crowdfunding.xlsx Excel file.
Clean the dataset by assigning category and subcategory values to appropriate columns.
Obtain lists of unique categories and subcategories.
Create two DataFrames: categories_df with category IDs and names, and subcategories_df with subcategory IDs and names.
Export categories_df and subcategories_df as CSV files.
Created a copy of crowdfunding_info_df DataFrame named campaign_df.
Convert "goal" and "pledged" columns to float data type.
Convert Unix timestamps to datetime objects.
Merge campaign_df with category_df based on "category" column and subcategory_df based on "subcategory" column.
Drop unwanted columns from the DataFrame.
Export the transformed DataFrame as a CSV file.
Extract data from contacts.xlsx Excel file.
Create Contacts DataFrame with columns: "contact_id", "first_name", "last_name", and "email"
Used Pandas to extract email addresses for the "email" column.
Export the DataFrame as a CSV file.
