# Homework 1 - Excel tips

## The Process
1.  This suggestion is not really that important but if you want to set up your files like this then it might be helpful.  My suggestion is that you keep the files from GitLab separate
from your homework.  So maybe a file structure like this will keep
things organized.  
  
  * What you can start with will be in google drive and you can have just a folder for the homework and copy the files for Excel over into this folder.

  ```
Google Drive
|
├── Homeworks
    ├── 01-Excel                     # Shared Google Folder or GitHub Repo
        ├── excel-challenge
            ├── Images
            ├── StarterBook.xls
            ├── Readme.doc            # Put your summary here
            ├── Readme.md***          # Try making a summary here also if you want to learn Markdown
            ├── .gitignore            # Not needed until added to GitHub
```
 *** [Learn about Markdown](https://guides.github.com/features/mastering-markdown/) 
  * Later you will want to move these files into a structure that looks like this.  



```
DS_Bootcamp
|
├── nu-chi-data-pt-02-2021-u-c*      # GitLab Repo
|   ├── 00-PreWork
|   ├── 01-Lesson-Plans
|   ├── 02-Homework
|   ├── Readme.md
|   ├── .gitignore
|
├── Homeworks
|   ├── 01-Excel                     # Shared Google Folder or GitHub Repo
|       ├── excel-challenge
|          ├── Images
|          ├── StarterBook.xls
|          ├── Readme.doc            # Put your summary here
|          ├── Readme.md             # Put your summary here 
|          ├── .gitignore            # Not needed until added to GitHub
|
├── Projects
|   ├── 1_Pandas*                    # Github Repos
|   ├── 2_ETL*
|   ├── 3_Visualization*
|   ├── 4_ML*
|
├── Github webpage
|   ├── github.io*                   # Covered Week 11  (GitHub Repo)
|       ├── static
|       |   ├── data
|       |   ├── css
|       |   ├── js
|       |
|       ├── pages
|       |
|       ├── index.html
|
├── Resources
    ├── Notes
    ├── Cheatsheets
```
2.  As long as you get the charts to look approximately like the images then you are fine.  I have a few comments below.  
2.  A trick to see categorical data in a spreadsheet is by turning on the filters.  That is done by selecting any cell in your data table and going to the Data Menu and then Selecting Filter. The top row will now have down arrows and you can click on this to see the unique values in that column.  For the state column you should 
have 4 unique categories - cancelled, failed, live, successful.
3.   The `percent funded` column is a calculation that provides the percent of pledges compared to the goal.  So if the pledges equal half the goal then it is 50%.
4.  The pledged column is how much money all the backers have contributed thus far (paid)
5.  The new `Date Created Conversion` and `Date Ended Conversion` columns can be placed in column S and T, respectively.
6.  The converted time stamps are GMT.  To check your formula then you can use this tool:  [https://www.unixtimestamp.com/index.php](https://www.unixtimestamp.com/index.php).  Dates and Times can be difficult to handle.  What is the difference between GMT and CST?  Also remember to read the instructions - they give you a link that takes you to the instructions about how to convert the dates.
7.  Notice that columns I & J are not in the order that you would expect but the instructions are correct.
7.  If you receive errors then searching google for "excel error handling" might be helpful.  Many times you will come across an unexpected issue in your code and searching and resolving it is part of the process and part of what makes you an independent and valuable employee.
7.  You may also need to search for methods to "parse excel text" or "split excel text".  One of the ways that you can do this involves the '=LEFT()' function.  There are a couple other functions that can help but first try to google search to figure it out first on your own.  This is some practice about learning on your own but we will help if you get stuck.
 ![Outcomes Based on Launch Date](Images/LaunchDateOutcomes.png)
8.  The image above shows only successful, failed, cancelled from the data.  If you include `live` (missing column) in the pivot table or pivot chart then that is fine.  I will double check if this table and chart are correct - there is a chance that the image is from a different data set and you will have slightly different trends.  I will send you an update about this. `UPDATE:  As long as your time stamp is converted to GMT (like the instructions provide) then your trends will be very similar.  Interestingly, if you use CST then the trends will look quite different even though only a subset of the data will be off by a day.  You can use the "Date Created" date to make this chart.`
8.  You can make your summary in Word but if you want to learn how to make a .md (MarkDown) then review this document - [Learn about Markdown](https://guides.github.com/features/mastering-markdown/).  You can also look at how the readme.md instructions are written for this homework to understand how it works.  You can see the markup code and the rendered code in MS VSCode.
