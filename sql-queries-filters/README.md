## Apply filters to SQL queries

### Overview
This activity shows how SQL filtering techniques were used to investigate potential security issues, within the employee and login activity data at an organization. The analysis focused on two main datasets: log_in_attempts and employees. Using SQL queries, I identified suspicious login behavior, reviewed activity on specific dates, and filtered employee records based on security requirements.

---

### Scenario
You are a security professional at a large organization. Part of your job is to investigate security issues to help keep the system secure. You recently discovered some potential security issues that involve login attempts and employee machines. Your task is to examine the organization’s data in their employees and log_in_attempts tables. You’ll need to use SQL filters to retrieve records from different datasets and investigate the potential security issues.

---


### Objectives
- Identify failed login attempts after business hours.
- Analyze login activity on specific dates related to a suspicious incident.
- Detect login attempts originating outside of Mexico.
- Filter employee records for targeted security updates across departments.

---


### Steps and Purposes

#### Retrieve After Hours Failed Login Attempts
- Investigated failed login attempts that occurred after business hours (18:00). 
- Identify unsuccessful login attempts that occurred outside of normal working hours.

#### Retrieve Login Attempts on Specific Dates
- Filtered login activity for a suspected security incident on 5/9/2022 and the previous day.
- Review all login activity related to the incident time period.

#### Retrieve Login Attempts Outside of Mexico
- Identified login attempts originating from outside Mexico by excluding known values.
- Investigate suspicious login activity from outside the expected region.

#### Retrieve Employees in the Marketing Department
- Filtered employees in the Marketing department located in the East building.
- Identify employee machines requiring updates.

#### Retrieve Employees in Finance or Sales
- Selected employees from departments requiring security updates.
- Ensure all relevant departments are included in the update process.

#### Retrieve Employees Not in IT
- Excluded IT department employees from the update list.
- Include all non-IT employees for final security updates.

---

### SQL Techniques Used
- WHERE clause: filtering records.
- AND operator: including multiple conditions.
- OR operator: alternative conditions.
- NOT operator: exclusions.
- LIKE operator with % wildcard: pattern matching.

---

### What I Learned?
- Use SQL filtering techniques to investigate security-related data.
- Apply logical operators such as AND, OR, and NOT to improve query filtering.
- Use the LIKE operator and % wildcard for pattern matching.
- Analyze login activity based on time, date, and location.

---

### Notes
This activity followed directions from the lab "Filter with AND, OR, and NOT," available in Google Cybersecurity Professional Certificate. More details about lab directions and performed steps could be found in the uploaded documents.

