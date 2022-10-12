#####Application Readme file
- I have developed the solution in C# console application and attached the program .exe solution with the source code in google drive. Google drive link available in the email.
- You can simply run the .exe solution file to execute the program.
- THE PROGRAM WILL CREATE FOLDER IN C DRIVE IF NOT EXIST BY DEFAULT NAMED AS "SearchKeyword"
- Place your sample txt file in "C:\SearchKeyword"
- The program will ask to input filename or write letsquit to exit the program
- If the file nme does not exist in the directory then it will show "File <filename> does not exist"
- If the input contains a dot (sample.txt) then it will split the input string with dot and get the file extension
- If there is any file extension other than txt then it will be ignored and the program will ask to input filename again.
- Only txt files are supported in this program
- Once the filename is entered, the program will read it line by line and ask to enter the search term
- It will fetch the matching search term from the text file and get first and last 3 words including the search term
- If no matching word found then it will display "Keyword <keyword> not found" and the program will again ask to enter search param.
- the program can search the input in all the desired cases as required “species”, “SPECIES”, and “SpEcIeS”
- The program can search input with a-z, A-Z, 0-9, and apostrophe.


BONUS FEATURES:
- Security measures should be like protecting the directories from write features or to avoid unrestricted access
- This can be converted to RestAPI using Laravel jobs features or Azure Web Service.
- For monitoring, I can convert this application to windows service and we can log different activities to Window Event Log that can be view using Event Viewer app
- For infrastructre, we can host this application to azure web services. We can deploy it as a window service as well on any dedicated windows platform server.
