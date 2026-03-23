# Consolidating-Employee-Data-with-Python
This project uses DataFrames to read and merge employee data from different sources.

## Source Data
This project is created to structure the human resources data for a company. The data is currently scattered across teams and files and comes in various formats: Excel files, CSVs, JSON files in the following structure:

**Office addresses:**
Saved in office_addresses.csv.
If the value for office is NaN, then the employee is remote.

**Employee addresses:**
Saved on the first tab of employee_information.xlsx.

**Employee emergency contacts:** Saved on the second tab of employee_information.xlsx; this tab is called emergency_contacts.
This sheet has no headers. Headers should be: employee_id, last_name, first_name, emergency_contact, emergency_contact_number, and relationship.

**Employee roles, teams, and salaries:** This information has been exported from the company's human resources management system into a JSON file titled employee_roles.json

## Tools Used
**Python:** Data cleaning and aggregation
