# Stock-analysis VBA Challenge

## Overview of Stock-Analysis
  The purpose of this project was to write a code that would make it easy to analyze a group of stock over two years. 
  The code was to summarize the stock information by stock and other pertinent financial information. The code needed 
  to easily identify important information visually as well with color.  This would allow the individual 
  to visually identify successful stock vs poorly performing stock.  
   
## Results of refactoring and upgrading my code
   Before refactoring my code to include an index of the tickers `Dim tickerIndex As Integer, tickerIndex = 0` the run
   time for 2017 and 2018 were: 
          
 #### 2017 Runtime pre-refactoring
   ![Screenshot_runtime_2017_old_code](https://user-images.githubusercontent.com/94803292/149633132-a12d2bdd-adc5-4b34-826a-9709b45508e1.png)
        
          
     
 #### 2018 Runtime pre-refactoring
   ![Screenshot_runtime_2018_old_code](https://user-images.githubusercontent.com/94803292/149633137-c2ad8ceb-2684-4169-9b87-49175c8eec0a.png)
         
          
     
   Once I refactored the code to include the indexing of the tickers the run time of the code was much faster as you 
   can see below.:
     
 #### 2017 Runtime post refactoring
   ![Screenshot runtime 2017](https://user-images.githubusercontent.com/94803292/149633158-b7a406f5-2051-431b-91e4-abdb732b3755.png)

      

 #### 2018 Runtime post refactoring
   ![Screenshot runtime 2018](https://user-images.githubusercontent.com/94803292/149633166-f0726330-f8c0-4032-9535-213037276ed1.png)

     
 ## Summary 
 Refactoring code definitely has its in advantages. The fact that you do not have to rewrite each line a code over again
 provides big time savings.  Be able to refactor code allows you to have a sort of visual guide when trying to figure out
 what is the appropriate logic to use when approaching a particular obstacle.  As you talk through the code you have already 
 written you can see if that same piece of code will work for your current project.  I have used the code that I have learned
 in this module already in my job. Refactoring does come with some issues as well.  When refactoring code I find that it 
 is easier for you to miss reference or variables throughout your code.  As you refactor you can easily flyby something that 
 should have been updated with a new reference possibly causing so extra time debugging.  This is what I found when I 
 refactored my original code to the new code.  I failed to update a few references throughout my code.  Although I think I spent
 a little more time debugging the code it was nothing compared to the time I would have had to spend rewriting the code from 
 scratch
          
     
 
     
    
    
    
    
    
    
Module 2 coursework
