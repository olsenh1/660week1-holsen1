# README.md (Week1.py )

### SWDV-660 – Applied DevOps
### Maryville University, 2019  
### Week 1 Assignment: Package Managed Projects  
### **Henrik Olsen** (0913075)    

---------

## My Python code this week https://github.com/olsenh1/660week1-holsen1/blob/master/week1.py is a small program that roll a die however many times the user tells it to. 

  * ### Random dependency is used to generate random numbers between 1 and 6 (technically, the code is using randrange from the random module to generate    integers).
  * ### PrettyTable dependency is used to print the results of the die rolling in table format.
  * ### Colorama dependency is used to color the output from PrettyTable as well as some of the standard Python output. 


### The GitHub repository also includes a Windows 10 compiled version of the file: https://github.com/olsenh1/660week1-holsen1/blob/master/week1.exe 


### The program will ask the user how many times he/she wish to roll the die. After ensuring the input is a whole number (you can't do a partial roll or 'h' rolls for example) a virtual die is rolled that many times and the result of each roll is recorded. Then the result is printed out in a colorful table format along with statistics on how often each possibility was rolled. 

### To run the code, clone it from the GitHub repository:
   ### 1. Open a command prompt or PowerShell
   ### 2. Navigate to a directory of your choice
   ### 3. Run the following command:
    git clone https://github.com/olsenh1/660week1-holsen1 
   ### 4. Then navigate inside the directory
   ### 5. From here you can run the exe file or run a "pipenv install" to create a virtual environment. Then you can run the source file by running the command:
    pipenv run python week1.py

   ### or open a new shell:

    pipenv shell

   ### and then run the python code normally, using:

    python week1.py

### Note that Colorama doesn't seem to be working in Thonny, so running the code from here will produce a less than desired output.