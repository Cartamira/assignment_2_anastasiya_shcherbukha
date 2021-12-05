# assignment_2_anastasiya_shcherbukha
Dice Search solution
The solution is using Robotic Enterprise Framework for daily email reporting on the number of jobs from Dice job portal in the top 10 biggest city in USA. The report is delivering by Gmail. The file name is today’s date. 
On Initializations step we search for top 10 biggest cities in USA and store them in excel file. Next step would be push these name to the Queue. 
In Get Transactions Data we receiving the data one by one to the process transactions
In the process transaction stage we are delivering the job search, based on some parameters, locations names we are receiving from the Queue. Using the same file to store the numbers of jobs at each locations. Getting the next Transaction until there is a data.
If there is no data in the Queue, we are forming the report by sorting the data by the number of jobs. Sending the report to predefined email. The name of the file change to today’s date. Delete the file from the folder at the end of the process. 
