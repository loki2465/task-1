# task-1
This Excel file contains a cleaned version of a raw dataset. The following data preprocessing and cleaning steps were applied to ensure consistency, accuracy, and usability of the data:

✅ 1. Identified and Handled Missing Values
Applied Filters to each column to detect missing (blank) cells.

Used conditional formulas and manual checks to fill missing values with placeholders such as "Unknown" or appropriate default values.

In some cases, rows with critical missing data were removed entirely.

✅ 2. Removed Duplicate Rows
Used Excel’s "Remove Duplicates" tool under the Data tab.

Selected all columns to check for full-row duplicates and removed them to avoid redundancy.

✅ 3. Standardized Text Values
Cleaned up inconsistent text entries such as:

Gender ("M", "m", "Male") → standardized to "Male".

Country names and other categorical values were normalized for spelling and casing.

Used Find & Replace, IF formulas, and Flash Fill to assist in transformation.

✅ 4. Converted Date Formats to Consistent Type
All date columns were converted to the dd-mm-yyyy format using:

Format Cells → Custom → dd-mm-yyyy.

Ensured all entries are recognized as valid Excel dates for consistency and future analysis.

✅ 5. Renamed Column Headers
Cleaned and standardized column headers:

Converted all headers to lowercase.

Replaced spaces with underscores for readability (e.g., "First Name" → first_name).

Ensured all headers were meaningful and relevant.

✅ 6. Checked and Fixed Data Types
Ensured each column had the correct data type:

Age columns were converted to integers.

Date fields were validated as Date type.

Text fields were formatted properly for consistency.

Used Excel’s Format Cells feature and formulas like =INT(), =VALUE() to correct data types where needed.

