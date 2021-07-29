# #100DaysOfCode Round06 Log - Nem Borkar

The log of my #100DaysOfCode challenge. Started on [February 22, Sunday, 2021].

## Log

### 20210729 Day91
Today I solved a fairly complex issue with some basic dictionary manipulation  
The API we are building and the API it's talking to accept JSON in very different formats  
Just had to reshuffle the dictionary a bit and bam! Done!  
All that leetcode grinding actually helped somewhere!  

### 20210728 Day90

Toolkit team said no, so we are gonna use a bandaid fix to keep our stuff moving  

Completed a tiny feature branch and PR is in progress  

### 20210727 Day89
Troubleshot a header dependency with our senior dev today. Explored options all the way back to the third party package that we are using in our dependency toolkit. Will probably discuss and resolve with our toolkit's team tomorrow  

Also separated the giant ticket into smaller subtasks (and git branches)  
Time to divide and conquer!

Also, self project: created repo and venv for the python webscraper I'm slowly building lol  

### 20210726 Day88
After finishing rebase, git status will say your local branch has diverged from the remote and will suggest PULLING to MERGE from the remote. This defeats the whole purpose of the rebase! Why git, why?  

To succesfully complete a rebase, force push local changes to remote!  
This was the step I was missing, the last time I messed up my rebase!

### 20210720 Day87
Adjusted some of the model classes to accept data from the PATCH method. PUT and POST are working though  
Gotta troubleshoot this further...  

### 20210719 Day86
Predominantly writing scripts in the last couple years, I had forgotten most of the OOP concepts I learnt back in the day studying C++/Java  
So decided to brush up on Python specific OOP today  

### 20210716 Day85
Messed up big time rebasing a branch from upstream today. Lesson learned: you don't ALWAYS have to choose between incoming or existing code. We can just keep both and then trim manually  

Useful command for #git postmortems,  
$ git reflog show --date=iso

### 20210714 Day84
Trying to get POST, PATCH and PUT methods to work on an upstream API  
More good advice from my teammate: Breakdown the steps and troubleshoot as you go. It's better to overdo then delete, than to overthink and not do much. More code; less todos  
