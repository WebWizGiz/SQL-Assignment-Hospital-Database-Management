# SQL-Assignment-Hospital-Database-Management
SQL Assignment: Hospital Database Management
Background:
You are tasked with managing a simplified database for a hospital. This database keeps track of patients and doctors. Your role involves inserting records into the database, querying information based on specific criteria, updating records, and deleting records when necessary.

 Database Schema:
1. Patients Table 
   - PatientID INT
   - FirstName VARCHAR(255)
   - LastName VARCHAR(255)
   - DOB DATE
   - Gender VARCHAR(10)
   - Address VARCHAR(255)

2. Doctors Table
   - DoctorID INT
   - FirstName VARCHAR(255)
   - LastName VARCHAR(255)
   - Specialty VARCHAR(255)
   - YearsOfExperience INT

Sample Data:
**Patients:**
1. John Doe, 1980-01-01, Male, 123 Elm St
2. Jane Smith, 1990-05-15, Female, 456 Oak St
3. Alice Johnson, 1975-09-23, Female, 789 Pine St
4. Mark Brown, 1985-07-30, Male, 321 Maple St
5. Lucy Gray, 1995-03-12, Female, 654 Willow St
6. Ethan Hunt, 1978-05-21, Male, 987 Cedar St
7. Olivia Green, 1988-12-16, Female, 213 Spruce St
8. Noah Wilson, 1992-08-04, Male, 432 Birch St
9. Ava Taylor, 1983-11-23, Female, 876 Redwood St
10. William Davis, 1970-01-29, Male, 567 Chestnut St

**Doctors:**
1. Emily Stewart, Cardiology, 15
2. Michael Brown, Neurology, 20
3. Lucas Morris, Pediatrics, 5
4. Sarah Clark, Dermatology, 8
5. James Wilson, Orthopedics, 12
6. Anna Lee, General Medicine, 10
7. Richard Hall, Psychiatry, 18
8. Jessica King, Ophthalmology, 7
9. Daniel Young, Gastroenterology, 9
10. Sophia Martin, Oncology, 14

Tasks:
**Easy (1-10):**
1. Insert the sample data into the Patients table.
2. Insert the sample data into the Doctors table.
3. Select all patients who are Female.
4. Select all doctors with more than 10 years of experience.
5. Find all doctors specializing in 'Pediatrics'.
6. List all patients ordered by DOB in descending order.
7. Select all distinct addresses from the Patients table.
8. Update the address for 'John Doe' to '321 Elm St'.
9. Delete the patient record for 'William Davis'.
10. Select all doctors ordered by YearsOfExperience in ascending order.

**Medium (11-20):**
11. Select all patients with last names starting with 'J'.
12. Find all doctors who are not 'General Medicine' specialists.
13. List all patients where the FirstName is 'Alice' or 'Mark'.
14. Update the YearsOfExperience to 20 for 'Emily Stewart'.
15. Delete all doctors with less than 10 years of experience.
16. Select all patients where the address contains 'Elm'.
17. Find all doctors whose last name ends with 'son'.
18. List all patients and their genders, but only those living on 'Pine St'.
19. Update all Female patients' addresses to 'Unknown'.
20. Delete all patients born before '1980-01-01'.

**Hard (21-30):**
21. Select the doctor with the highest number of years of experience.
22. Find the youngest patient in the database.
23. List all doctors and their specialties, but only those with last names longer than 5 characters.
24. Update the Specialty to 'Emergency Medicine' for all doctors with less than 8 years of experience.
25. Delete all Female patients whose first name starts with 'A'.
26. Select all patients, showing only FirstName and DOB, where the DOB is after '1990-01-01'.
27. Find all doctors who specialize in either 'Cardiology' or 'Orthopedics'.
28. List all patients whose address does not contain 'St'.
29. Update the address for all patients living on 'Maple St' to 'Updated Maple St'.
30. Delete all doctors who do not have a specialty containing 'ology'.

 Bonus Tasks (31-50):

**Bonus Easy (31-35):**
31. Select the first name and last name of all doctors in alphabetical order by their first name.
32. Find the total number of male patients in the database.
33. List the first name of all patients whose first name contains the letter 'e'.
34. Update the gender of 'Ava Taylor' to 'Other'.
35. Delete the patient record for anyone whose last name is 'Johnson'.

**Bonus Medium (36-40):**
36. Select all doctors whose specialty starts with the letter 'O'.
37. Find all patients who live on streets that contain the word 'Cedar' or 'Spruce'.
38. List the full names of patients (concatenate first name and last name) and their DOB, ordered by their first name.
39. Update the YearsOfExperience by adding 2 years for all doctors who have less than 15 years of experience.
40. Delete all doctors who have a last name that starts with 'Y' or ends with 'g'.

**Bonus Hard (41-50):**
41. Select the oldest patient's full name and DOB.
42. Find the doctor with the least years of experience and list their specialty and years of experience.
43. List all patients whose address does not start with a number (Hint: Use NOT LIKE).
44. Update all patients born in '1980' to have their address changed to 'Special Address 1980'.
45. Delete all patients whose first name is shorter than 4 characters.
46. Select the count of doctors for each specialty, ordered by the count in descending order.
47. Find all patients whose first name starts with 'A' or last name ends with 'n', and order them by DOB.
48. Update the address for all doctors to include their specialty at the end (e.g., '123 Elm St, Cardiology').
49. Delete all records from the Patients table where the patient's first or last name contains the letter 'z'.
50. Select all doctors and order them by the length of their last name, from shortest to longest.
