# End-to-End-Data-Analytics-Project

## Data Transformation in SQL

This project focuses on cleaning the Nashville Housing dataset using SQL by performing several key tasks to ensure data uniformity and accuracy. First, the SaleDate column is standardized to a consistent date format. Missing PropertyAddress values are populated using SQL joins based on matching ParcelID. The PropertyAddress and OwnerAddress fields are split into separate columns for address, city, and state to facilitate easier analysis. The SoldAsVacant field is updated to replace 'Y' and 'N' with 'Yes' and 'No'. Finally, duplicate rows are identified and removed, and unused columns are dropped, resulting in a clean and standardized dataset ready for further analysis.
