#### <center> WELCOME TO MY EXPERIMENT 4!

## <center> DATA WRANGLING AND DATA VISUALIZATION

##### Name: Trangia, Klein Isshi G.

##### Section: 2ECE-D

##### Date Submitted: September 19, 2024

## __ECE BOARD EXAM PROBLEM 1__

### __1. Create the following data frames based on the format provided:__

First, I imported pandas as pd to access the pandas library.

<img width="168" alt="Screenshot 2024-09-19 at 7 07 32 PM" src="https://github.com/user-attachments/assets/32da7421-ee75-4cfa-b506-ed83f5af28ff">

I used "boards" to store this code to read the Excel file that is uploaded in my folder:

<img width="311" alt="Screenshot 2024-09-19 at 7 11 43 PM" src="https://github.com/user-attachments/assets/d64369e9-3331-4f3b-97ef-73ffca2b203b">

<img width="475" alt="Screenshot 2024-09-19 at 7 14 27 PM" src="https://github.com/user-attachments/assets/2bb7ba3b-ee66-43be-a544-a7ef56d8a8d0">

### __a. Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as Instrumentation and hometown Luzon__

To do this instruction, I used this code: 

<img width="504" alt="Screenshot 2024-09-19 at 7 17 10 PM" src="https://github.com/user-attachments/assets/7d16b160-5116-4437-ba08-0581b54d94a0">

I used "Instru" to store the code as instructed. I applied ".loc" to locate the students with Track equal to Instrumentation, Hometown equal to Luzon, and Electronics scores greater than 70. I only displayed the Name, GEAS, and Electronics scores above 70.

This is the output of my code:

<img width="232" alt="Screenshot 2024-09-19 at 7 25 37 PM" src="https://github.com/user-attachments/assets/17f6fac8-750f-4437-8b36-a9d59bae6e9d">

### __b. Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female__

I used this code first for this instruction:

<img width="695" alt="Screenshot 2024-09-19 at 7 29 35 PM" src="https://github.com/user-attachments/assets/18277ce1-7030-403f-acfd-aba67282ae03">

<img width="523" alt="Screenshot 2024-09-19 at 7 35 07 PM" src="https://github.com/user-attachments/assets/127e0bb2-158d-41d4-91de-8a9922650e61">

This code produces another column for my uploaded Excel file, the Average column. I get the mean of Math, Electronics, GEAS, and Communication using ".mean" and "axis=1" to compute the mean scores by row. I coded this since it is needed for this second instruction.

I, then, used this code:

<img width="568" alt="Screenshot 2024-09-19 at 7 37 32 PM" src="https://github.com/user-attachments/assets/5ef9f4ca-966b-4ed1-9813-12cb36de1ac0">

I stored the code in Mindy as instructed. I used ".loc" again to locate the students whose Hometowns are equal to Mindanao, whose Gender is equal to female, and whose Average scores are greater or equal to 55. I only displayed the Name, Track, Electronics, and Average.

This is the output of my code for this instruction:

<img width="353" alt="Screenshot 2024-09-19 at 7 43 59 PM" src="https://github.com/user-attachments/assets/c943600a-5f85-4f60-ae98-dbb786c67a8f">

## __ECE BOARD EXAM PROBLEM 2__

### __2. Create a visualization that shows how the different features contributes to average grade. Does chosen track in college, gender, or hometown contributes to a higher average score?__

I, first, input this code to access the matplot library:

<img width="259" alt="Screenshot 2024-09-19 at 7 53 31 PM" src="https://github.com/user-attachments/assets/5859a152-f063-4c0e-a918-7475568b1307">

I used the following codes to produce the correlation between Track, Gender, and Hometown in the students' average scores:

I used "plt.figure" to change the size of the graph. I used the "plt.bar" to store the graph values in x and y and input a color. I put "plt.xlabel" and "plt.ylabel" to insert a name. Lastly, I used "plt.title" to give a name for the graph.

## __First Graph:__

<img width="655" alt="Screenshot 2024-09-19 at 7 55 38 PM" src="https://github.com/user-attachments/assets/c7d04719-58be-46ed-9a64-3128e7d444b2">

This code is used to know the graph of average scores of students in each Track they chose. Students who study Microelectronics have the highest average score, and students who study Instrumentation have the lowest average score. I think Microelectronics students have the highest since they focus mainly on electronics.

This is the output graph:

<img width="880" alt="Screenshot 2024-09-19 at 8 08 29 PM" src="https://github.com/user-attachments/assets/f8990d2f-dc23-437e-ab43-41ee86252bdb">

## __Second Graph:__

<img width="610" alt="Screenshot 2024-09-19 at 7 56 02 PM" src="https://github.com/user-attachments/assets/02203e85-0c84-419c-9761-ab5f09a40c6e">

This code is used to know the graph of students' average scores based on their Gender. Female students got the highest average scores than Male students. Maybe female students got the highest since there are 15 females and 14 males.

This is the output graph:

<img width="859" alt="Screenshot 2024-09-19 at 8 21 21 PM" src="https://github.com/user-attachments/assets/c4d4edfa-8416-4991-96fe-0f000981c775">

## __Third Graph:__

<img width="625" alt="Screenshot 2024-09-19 at 7 56 31 PM" src="https://github.com/user-attachments/assets/575dd73c-2f18-4d23-9d65-a6b06cf07acb">

This code is used to know the graph of average scores of students based on their Hometown. Students who study in Luzon have the highest average score, and students who study in Mindanao have the lowest average score. I think students who study in Luzon have the highest since, most of the time, the board exams are held there, so people in Mindanao need to travel.

This is the output graph:

<img width="858" alt="Screenshot 2024-09-19 at 8 22 18 PM" src="https://github.com/user-attachments/assets/03c40dec-d464-468f-bfff-759fb7a3dce8">

## __MESSAGE__

Thank you for being with me in this journey!
