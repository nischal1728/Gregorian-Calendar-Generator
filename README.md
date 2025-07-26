
📅 Gregorian Calendar Generator
A C-based console application to generate a monthly or yearly Gregorian calendar, with support for leap years, day-of-week calculation, and validation. Developed during the Critical Thinking & Problem Solving Bootcamp.

🧠 Team Name: Segmentation Fault
Team Members:

Nandini Hegde (4MT22CI017)

Marushka Rachelle D'silva (4MT22CI029)

Nischal K (4MT22CI036)

Riyaz K (4MT22CI041)

Sujal Revankar (4MT22CI055)

Vikas M (4MT22CI060)

Yashita Vasu (4MT22CI062)

🔍 Features
Displays calendar for a specific month or all months in a given year.

Accurately handles leap years using Gregorian rules.

Calculates day of the week for any date.

Validates user input for month and year boundaries.

Provides console-based calendar layout.

Structured code for easy understanding and testing.

⚙️ How It Works
User inputs a year and optionally a month (or ALL).

The program calculates:

Leap year status

Day of the week for the 1st of the month

Total days in each month

It then prints a formatted monthly calendar grid to the console.

🧪 Test Cases Included
Leap year validation (e.g. 2020, 2100)

Month length (e.g. Feb 2023 = 28, April = 30)

Edge case years (e.g. 1 or 9999)

Invalid input handling

Day-of-week checks (e.g. 25-Dec-2023)

Day counter in the year

📁 Files
calendar.c: Source code file

README.md: Project documentation

sample-output.txt (optional): Example output results

test-cases.txt (optional): Test cases run and results

🖥️ Compilation & Run
bash
Copy
Edit
gcc calendar.c -o calendar
./calendar
🗒️ Sample Output
sql
Copy
Edit
Enter Year = 2024
Enter Month (1-12 or 'ALL') = ALL

       Month 1, 2024
  Sun  Mon  Tue  Wed  Thu  Fri  Sat
       1    2    3    4    5    6
   7    8    9   10   11   12   13
  ...
✅ Use Cases
Personal scheduling

School/academic calendar

Work and project planning

Financial planning and reminders

Travel or holiday planning

📌 Requirements
C compiler (GCC or any standard)

Works on Windows, Linux, Mac (terminal required)

Let me know if you want a README.md file generated or help setting up the GitHub repo itself!











