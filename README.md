# Attendance Calculator
## Our small Project to help Teachers and Meeting Organisers to easily Calculate Attendance from Microsoft Teams 

## About Our Project:
 If you are familiar with Microsoft Teams you might have noticed that the Attendance list you download is a mess and if you want to assess it, you have to make a list of Absentees and Presentees it would take a lot of time. So Here we are trying to achieve to automate this process by writing a Python code which will help the meeting orgainzers to easily sort the absentees and presentees from the meetings.


## Who can Use:
 Basically anyone can use it. You will need the Attendance list which you download from Microsoft Teams obviously and a list of all the people you wanted them to attend


## Prerequisites:
* List of all the people you wanted them to attend
  We suggest you to use Google Forms for this as the present code works best with .csv file downloaded from Google Forms and it's very easy to use.
  
  ![Google Forms Help image](https://icwy841l6zopsr5u4960yoyz-wpengine.netdna-ssl.com/wp-content/uploads/2019/11/options-google-form-responses-tab.jpg)
  
* Attendance list which you download from Microsoft Teams;
  Microsoft Teams let's you download Attendance list which contains the log of whats happening in the meeting.
  Here the .csv you download has encoding = 'utf-16' and separation = '\t' ,"So do not try to covert this as present code is written only for this encoding type."
   
   ![MS Teams Help image](https://docs.microsoft.com/en-us/microsoftteams/media/meetings-attendance-download.jpg)
   
 ## Features:
 * The application is **"Easy To Use"**
 * The application can compare **"Two parameters"**(eg:Name,RollNo) as some studentes have there teams username as either there Nme or there RollNo.
 * The application is **"non Case-Sensitive"**(eg:AbC,aBC its take both as same)
 * The application is **"non Space Sensitive"**(eg:Ab C,a B C its take both as same)
 * The application can check for a certain **"Time Period"** if the attendee is present or not.
 (eg:[A,joined 11:30],[A,left 11:45], 
 TimePeriod is 10 then A is Present, 
 If TimePeriod is 20 then A is Absent)
 * The application can **"Save the output to .csv formats"**
 * The application has an **"Intercative Graphical User Interface"** according to ME :wink:
 
 ## How can I install?
   The application is portable, so you dont need to install it. Just download and try it out!
   
### Note: Since the application is built on python interface, the file size is pretty big because it includes all the functions and the libraries are imported and even the fuctions which we have not used. Since the file size limit of Git-hub is 100 MB, we have uploaded it to Google Drive.

[Download](https://github.com/Prajwalmegalamani/Attendance-calculator/releases/tag/v1.0)
![Downloads](https://img.shields.io/github/downloads/ThePBone/GalaxyBudsClient/total)

### **"This is GUI based application is made for Teachers ease of use"** 

## Limitations:
  * You cannot run this application continuesly, You calculate the attendance for one meeting then you need to Exit the application to calculate the attendance for another meeting(Will be avaliable by next update).
  * Sometimes some of the .csv dont give the requied output(eg: Save absentees list will not work)
  * You need to input every thing in the order of the application shows you.
   
## How to use it?
   Now let's get down to the fun part,
   1. First **"Extract the Attendancecalculator.zip"**
   2. Next **"Run Attendancecalculator.exe"**,It may take a minute or two to pop-up
      Once it runs it should look something like this;
      
      ![Basic Help image](https://user-images.githubusercontent.com/46928323/91612104-4f20b380-e99a-11ea-9f83-61e8499ecfc1.png))
      
   ## **"Note: Check for the Spaces in Entry boxes"**
   
   3. Now Enter the **"Parameter1(Student's Names) Column Name"** in entry box, In this case it is "Full Name "
      
      ![C1 Help image](https://user-images.githubusercontent.com/46928323/91612509-3369dd00-e99b-11ea-96fb-43807f79c712.png)
      
   4. Next Enter the **"Parameter2(Roll Numbers) Column Name"** in entry box, In this case it is "USN "
   
      ![C2 Help image](https://user-images.githubusercontent.com/46928323/91612751-b4c16f80-e99b-11ea-8a9c-cf3d858a5fae.png)
      
   5. Next **"Select the Attendees list collected(Student's list) with Extension .csv"**,From the Pop-up select the file,In this case it is "finalstudentslist.csv"
   
      ![SL Help image](https://user-images.githubusercontent.com/46928323/91613094-79737080-e99c-11ea-9d3c-c5f41e322b86.png)
      
   6. Next **"Select the Attendance list downloaded from teams(Attendance list) with Extension .csv"**,From the Pop-up select the file,In this case it is "08-08-2020.csv"
   
      ![AL Help image](https://user-images.githubusercontent.com/46928323/91613291-da02ad80-e99c-11ea-8c71-c912ba2f0b14.png)
      
   7. Now Enter the **"Time Peroid(Minumum Time student should be present) in Minutes"** in entry box, In this case it is "10"
     
      ![MT Help image](https://user-images.githubusercontent.com/46928323/91613340-f43c8b80-e99c-11ea-87ca-a2cefc8d787c.png)
      
   ## **"Note: Extensions are taken automatically(.csv)"**
   
   8. Next **"Select the Save Absentees as Excel File(This will save Absentees list as Your_file_Name.csv)"**,Type the filename in the Pop-up,In this case it is "Absentees(10-08-2020).csv"
   
      ![SAB Help image](https://user-images.githubusercontent.com/46928323/91614182-afb1ef80-e99e-11ea-91ff-321c1362b42d.png)
   
   9. Next **"Select the Save Presentees as Excel File(This will save Presentees list as Your_file_Name.csv)"**,Type the filename in the Pop-up,In this case it is "Presentees(10-08-2020).csv"
   
      ![SPR Help image](https://user-images.githubusercontent.com/46928323/91614268-d7a15300-e99e-11ea-93c5-39d7f8f006b5.png)
      
   10. Exit the application and **"Check saved files"**
    
       ![CMP Help image](https://user-images.githubusercontent.com/46928323/91615215-b6416680-e9a0-11ea-9ff1-027821cb2654.png)
       
   
   # Do you think anything is missing, or have an idea to make this project better let us know.
   
   
   
   
  
   


