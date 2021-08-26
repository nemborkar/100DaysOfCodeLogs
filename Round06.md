# #100DaysOfCode Round06 Log - Nem Borkar

The log of my #100DaysOfCode challenge. Started on [February 22, Sunday, 2021].

## Log

### 20210826 Day98
3/7 tests pass

Minor differences in JSON outputs. Tweaked fixture to match. Exact dictionaries but different order. But order shouldn't matter in JSON...  
Wait a second... That's just a string, not JSON! Changed to JSON  

7/7 tests pass

### 20210825 Day97
Refactored a giant file into modular parts so it's easy to troubleshoot and add future endpoints and methods. Nothing too fancy, just organized design.  

### 20210823 Day96
Delete and Put methods turned out to use the exact same model in our project, so combined into one. Cleaned up the fixtures' responses too.  

### 20210820 Day94~95
Improved upon the tests and added one more fixture for a use case I overlooked earlier. Changes were approved and merged into develop (^_^)v

Now for a relaxing weekend!

### 20210817 Day93
Used fixtures to write tests for some core methods in the project  
Side note, just learning the [types of errors](https://www.tutorialsteacher.com/python/error-types-in-python) can really up your troubleshooting game  

To be honest, I was kinda losing motivation to finish this challenge. But the little break from the routine really helped get me back in the game. Now to power through and finish this off. Personally, I would really like to finish this challenge so I don't need to tweet about it EVERYDAY. Since I'm juggling a full time job and irl commitments, building two or three new things per week is a better approach than just raw daily unfocused time poured into something for just green squares on github. Not the best use of resources. But glad I took up the 100 days of code challenge and am set to finish it. Not recommended to others though.

### 20210810 Day92
Continued working on the little web scraper app  
Tried doing it the oldschool way with regular epxressions  
Trying beautifulsoup4 soon  

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
