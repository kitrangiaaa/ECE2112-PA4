#### <center> WELCOME TO MY EXPERIMENT 4!
## <center> DATA WRANGLING AND DATA VISUALIZATION

### __BEFORE I START THE PROBLEM__

<p align="justify"> First, I imported pandas as pd to access the pandas library.

<img width="175" height="42" alt="Screenshot 2025-09-22 at 4 02 21 AM" src="https://github.com/user-attachments/assets/405e1756-4c5d-415d-a04f-ba6ecb4edb40" />

## __ECE BOARD EXAM PROBLEM 1__
### __1. Create the following data frames based on the format provided:__
### Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas

I used "boards" to store the code to read the Excel file that is uploaded in my folder:

<img width="294" height="79" alt="Screenshot 2025-09-22 at 4 03 27 AM" src="https://github.com/user-attachments/assets/60d0e7e8-ed22-4686-8b1d-1e22a0a15181" />

<img width="430" height="594" alt="Screenshot 2025-09-22 at 4 03 59 AM" src="https://github.com/user-attachments/assets/aad40f64-d715-4b44-a203-9cc8240ffe71" />

### __a. Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as Instrumentation and hometown Luzon__

To do this instruction, I used this code: 

<img width="509" height="96" alt="Screenshot 2025-09-22 at 4 05 17 AM" src="https://github.com/user-attachments/assets/6eb1d2aa-2d3a-426b-a4b3-781e01a92077" />

<p align="justify"> I used "Instru" to store the code as instructed. I applied ".loc" to locate the students with Track equal to Instrumentation, Hometown equal to Luzon, and Electronics scores greater than 70. I only displayed the Name, GEAS, and Electronics scores above 70.

This is the output of my code:

<img width="224" height="116" alt="Screenshot 2025-09-22 at 4 05 32 AM" src="https://github.com/user-attachments/assets/05481064-deef-425e-9f8c-60ab4f970dc4" />

### __b. Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female__

I used this code first for this instruction:

<img width="691" height="56" alt="Screenshot 2025-09-22 at 4 06 09 AM" src="https://github.com/user-attachments/assets/bc1f9134-91f2-4615-a0d0-15b73ccfb06e" />

<img width="467" height="597" alt="Screenshot 2025-09-22 at 4 06 42 AM" src="https://github.com/user-attachments/assets/7cef0d0c-7653-4773-99c2-4e0dda96b15c" />

<p align="justify"> This code produces another column for my uploaded Excel file, the Average column. I get the mean of Math, Electronics, GEAS, and Communication using ".mean" and "axis=1" to compute the mean scores by row. I coded this since it is needed for this second instruction.

I, then, used this code:

<img width="381" height="61" alt="Screenshot 2025-09-22 at 4 07 11 AM" src="https://github.com/user-attachments/assets/d2c282ed-1822-48f0-be25-a246d0261aa1" />

<p align="justify"> I stored the code in Mindy as instructed. I used ".loc" again to locate the students whose Hometowns are equal to Mindanao, whose Gender is equal to female, and whose Average scores are greater or equal to 55. I only displayed the Name, Track, Electronics, and Average.

This is the output of my code for this instruction:

<img width="237" height="118" alt="Screenshot 2025-09-22 at 4 07 38 AM" src="https://github.com/user-attachments/assets/5f6aa632-1539-492f-90d4-492541800aa5" />

## __ECE BOARD EXAM PROBLEM 2__

### __2. Create a visualization that shows how the different features contributes to average grade. Does chosen track in college, gender, or hometown contributes to a higher average score?__

I, first, input this code to access the matplot library:

<img width="266" height="42" alt="Screenshot 2025-09-22 at 4 08 07 AM" src="https://github.com/user-attachments/assets/872688ee-b301-4b8d-9c45-76b0497f5389" />

<p align="justify"> I used the following codes to produce the correlation between Track, Gender, and Hometown in the students' average scores:

<p align="justify"> I used "plt.figure" to change the size of the graph. I used the "plt.bar" to store the graph values in x and y and input a color. I put "plt.xlabel" and "plt.ylabel" to insert a name. Lastly, I used "plt.title" to give a name for the graph.

## __First Graph:__

<img width="657" height="150" alt="Screenshot 2025-09-22 at 4 08 34 AM" src="https://github.com/user-attachments/assets/d749abf2-9768-4109-9541-1b7fe115462d" />

<p align="justify"> This code is used to know the graph of average scores of students in each Track they chose. Students who study Microelectronics have the highest average score, and students who study Instrumentation have the lowest average score. I think Microelectronics students have the highest since they focus mainly on electronics.

This is the output graph:

<img width="861" height="466" alt="Screenshot 2025-09-22 at 4 09 01 AM" src="https://github.com/user-attachments/assets/549a83ea-e139-4642-8275-d40b38ec96d3" />

## __Second Graph:__

<img width="611" height="147" alt="Screenshot 2025-09-22 at 4 09 23 AM" src="https://github.com/user-attachments/assets/c114d92b-41d2-44c4-81ea-0f61f60ff955" />

<p align="justify"> This code is used to know the graph of students' average scores based on their Gender. Female students got the highest average scores than Male students. Maybe female students got the highest since there are 15 females and 14 males.

This is the output graph:

<img width="855" height="474" alt="Screenshot 2025-09-22 at 4 09 45 AM" src="https://github.com/user-attachments/assets/3751ef0e-138c-46b9-8818-0c851713d8cc" />

## __Third Graph:__

<img width="627" height="147" alt="Screenshot 2025-09-22 at 4 10 07 AM" src="https://github.com/user-attachments/assets/82370654-5a16-4c8a-bcd3-be1621d1ce4a" />

<p align="justify"> This code is used to know the graph of average scores of students based on their Hometown. Students who study in Luzon have the highest average score, and students who study in Mindanao have the lowest average score. I think students who study in Luzon have the highest since, most of the time, the board exams are held there, so people in Mindanao need to travel.

This is the output graph:

<img width="853" height="472" alt="Screenshot 2025-09-22 at 4 10 32 AM" src="https://github.com/user-attachments/assets/be77c927-d18c-4b93-ae28-cb1c4bca3bc9" />

## __MESSAGE__

Thank you for being with me in this journey!
