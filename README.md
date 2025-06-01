## 🧹 Data Cleaning and Preprocessing Task

This task focused on cleaning and preparing the raw dataset for dashboard creation and analysis. The following steps were performed:

### ✅ Tasks Performed:

1. **Date Formatting**
   - Converted the `Date` column into a standard `Date` format (MM/DD/YYYY) for consistency and proper time-series analysis.

2. **Phone Number Standardization**
   - Reformatted phone numbers into the standard **U.S. style**: `(XXX) XXX-XXXX`.

3. **Column Insertion**
   - Inserted a new column to support calculated fields or derived values as part of the analysis process.

4. **Duplicate Removal**
   - Removed duplicate rows to ensure clean and reliable data insights.

5. **Blank Value Handling**
   - Replaced all **blank (empty)** values with:
     - `"NULL"` (where applicable, for text fields)
     - `0` (where applicable, for numerical fields)

6. **Table Creation**
   - Structured the cleaned data into a table format to enable filtering, sorting, and formula application in downstream tools like Power BI.

---

This preprocessing ensured that the dataset was clean, structured, and analysis-ready for creating visual dashboards and deriving actionable insights.
