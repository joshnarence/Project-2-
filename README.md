# Project-2-


Extract, Transform, and Load

1.Extract data from crowdfunding.xlsx Excel file.
2.Clean the dataset by assigning category and subcategory values to appropriate columns.
3.Obtain lists of unique categories and subcategories.
4.Create two DataFrames: categories_df with category IDs and names, and subcategories_df with subcategory IDs and names.
5.Export categories_df and subcategories_df as CSV files.
6.Created a copy of crowdfunding_info_df DataFrame named campaign_df.
7.Convert "goal" and "pledged" columns to float data type.
8.Convert Unix timestamps to datetime objects.
9.Merge campaign_df with category_df based on "category" column and subcategory_df based on "subcategory" column.
10Drop unwanted columns from the DataFrame.
11.Export the transformed DataFrame as a CSV file.
12.Extract data from contacts.xlsx Excel file.
13.Create Contacts DataFrame with columns: "contact_id", "first_name", "last_name", and "email"
14.Used Pandas to extract email addresses for the "email" column.
15.Export the DataFrame as a CSV file.
