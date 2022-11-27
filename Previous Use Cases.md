# Previous Use Cases of each team member:

## Shreyasi

1.  What is the tuition Fees of a particular course?

    The dataset does not have a details of tuition fees.

2.  What are the admission requirements of a course?

    We have admission requirements of a particular university but since there are no course detials we cannot fetch the requirements of a specific course.

        Select University.university_ID, University_name, Score, GRE, TOEFL, SOP, LOR, CGPA from university right join requirements on University.university_Id = Requirements.University_ID;

3.  What is the course structure? 

    The dataset does not have a details of course structure.

4.  Which universities have waived of GRE score?

    All the universities in the dataset have specific GRE score requirement.

5.  Top universities for GRE score less than 320? 

        Select University.university_ID, University_name, GRE from university right join requirements on University.university_Id = Requirements.University_ID where GRE < 320;

6.  What are the total number of international students registered in the university? 

    No such information present in the dataset.

7.  Number of courses available in the university? 

    The dataset does not have a details of courses.

8.  What is the course duration? 

    The dataset does not have a details of courses.

9.  What is the campus location?

        Select University_Name, Country from University;

10. How much is the application fees?

    Application fees details not available in the dataset



## Somesh R

1.  Search for universities which ranks between top 20-30.

        Select University_name, University_rating from University where University_rating BETWEEN 20 and 30;

2.	View the universities which has CGPA cutoff of 3.5 and above

        Select University.University_Id, university_name from University left join Requirements on  University.university_id = Requirements.university_id; where GPA >= 3.5;

3.	View the universities which offer course of “Computer science and engineering”.

    The dataset does not have details of courses.

4.	View the course which has requirements of IELTS<7.0 band.

    The dataset does not have details of courses.

5.	View the twitter username for the tweets related to Princeton University.

    The dataset does not have a details of twitter scap data.

6.  Which universities have a higher acceptance rate and a lower graduation rate?

    The dataset does not have details of graduation rate.

7.  Which universities have a high intake of international students in fall 2022?

    The dataset does not have details of intake of international students.

8.  Determine which university is in a developed location and has a vast job market (city or rural).

    No such information present in the dataset.

9.  How many universities have a high graduation rate in 2021?

    The dataset does not have details of graduation rate.

10. Which universities have IVY league status and view acceptance rate?

    The dataset does not have details of IVY league status.

11.	Which universities require a minimum score of 7 bands in IELTS and TOEFL > = 100?

    The dataset does not have details of IELTS.

        Select University.University_Id, University_Name, GRE, TOEFL from University left join Requirements On University.University_Id = Requirements.University_Id where IELTS >= 7 and TOEFL >= 100;

12.	Determine which universities have GRE requirements such as Verbal > = 155, Quants > = 160, and AWA > = 3.

    All the universities in the dataset have combined GRE score requirement.

13. What is the acceptance rate of students with a CGPA > = 7?

        Select University.University_Id, university_name, Chance_of_Admit from University left join requirements on University.University_ID = Requirements.University_ID where CGPA >= 7;

14. What is the most popular course of study in the top 10–20 universities?

    The dataset does not have a details of courses.

15. Which of the following private universities doesn’t have GRE or English proficiency exam requirements for application?

    All the universities in the dataset have combined GRE and IELTS/TOEFL requirement.

