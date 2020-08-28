# Attendance-calculator
## Our small Project to help our teachers to easily Calculate Attendance from Microsoft Teams 

## What is this project trying to achieve?
 If you have you organised Microsoft Teams you might have noticed that the Attendance list you download is a Mess, And if you want to Assess it make a list of Absentees and Presentees it would take a Hour.So Here,We are trying to achieve to automate this process by writing a Python code which will help The meeting orgainzers to easily sort the absentees and presentees from the there meetings.These project is specially dedicated to our teachers.


## Who can use it and What are the prerequisites?
 Basically anyone can use it. You will need the Attendance list which you download from Microsoft Teams obviously and a list of all the people you wanted them to attend


## Prerequisites
* List of all the people you wanted them to attend
  We suggest you to use google forms for this as the present code works best with .csv file downloaded from google forms and its very easy to use also
  
  ![Google Forms Help image](https://icwy841l6zopsr5u4960yoyz-wpengine.netdna-ssl.com/wp-content/uploads/2019/11/options-google-form-responses-tab.jpg)
  
* Attendance list which you download from Microsoft Teams
  When you have organised Microsoft Teams let's you download Attendance list which contains the log of that present movement happening in the meeting.
  Here the .csv you download has encoding = 'utf-16' and separation = '\t' ,"So do not try to covert this as present code is written only for this encoding type."
   
   ![MS Teams Help image](https://docs.microsoft.com/en-us/microsoftteams/media/meetings-attendance-download.jpg)
   
 ## Features
 * The application is **"Easy To Use"**
 * The application can compare **"Two parameters"**(eg:Name,RollNo) as some studentes have there teams username as either there Nme or there RollNo.
 * The application is **"Case-Sensitive"**(eg:AbC,aBC its take both as same)
 * The application is **"Space Sensitive"**(eg:Ab C,a B C its take both as same)
 * The application can check for a certain **"Time Period"** if the attendee is present or not.
 (eg:[A,joined 11:30],[A,left 11:45], 
 TimePeriod is 10 then A is Present, 
 If TimePeriod is 20 then A is Absent)
 * The application can **"Save the outputs to csv formats"**
 * The application has an **"Intercative Graphical User Interface"** according to ME :wink:
 
## How can I install it?
   The application is a portable one so you dont need to install it.Just download and try it out!
   
   ### Note:Since the application is built on python the file size is pretty big because it includes all the functions in the libraries have imported even the fuctions which i have not used and the file size limit of the Git-hub is 100 MB i have uploaded it to Google Drive.
    
    
   ### **"This is GUI based application is made for Teachers ease of use"** 
   
## How to use it?
   Now let's get down to the fun part,
   1. First **"Extract the Attendancecalculator.zip"**
   2. Next **"Run Attendancecalculator.exe"**,It may take a minute or two to pop-up
      Once it runs it should look something like this;
      
      ![Basic Help image](
      
   3. 
   


