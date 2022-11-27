# Previous Use Cases

## Shreyasi

1. What is the tuition Fees of a particular course?

The dataset does not have a details of tuition fees.

2. What are the admission requirements of a course?

We have admission requirements of a particular university but since there are no course detials we cannot fetch the requirements of a specific course

    Select University.university_ID, University_name, Score, GRE, TOEFL, SOP, LOR, CGPA from university right join requirements on University.university_Id = Requirements.University_ID;

3. What is the course structure? 

The dataset does not have a details of course structure.

4.Which universities have waived of GRE score?

All the universities in the dataset have specific GRE score requirement

5.Top universities for GRE score less than 320? 

    Select University.university_ID, University_name, GRE from university right join requirements on University.university_Id = Requirements.University_ID where GRE < 320;

6. What are the total number of international students registered in the university? 

No such information present in the dataset

7. Number of courses available in the university? 

The dataset does not have a details of courses.

8. What is the course duration? 

The dataset does not have a details of courses.

9. What is the campus location? 

    Select University_Name, Country from University;

10. How much is the application fees?

Application fees details not available in the dataset



