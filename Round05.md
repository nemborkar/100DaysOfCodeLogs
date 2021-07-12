# #100DaysOfCode Round05 Log - Nem Borkar

The log of my #100DaysOfCode challenge. Started on [February 22, Sunday, 2021].

## Log

### 20210712 Day83
After a lot of feedback, suggestions and changes from our senior devs, the refactor I was working on (last week) was approved and merged into the Develop branch! Also learned more about [async features](https://realpython.com/python-async-features/)  


### 20210709 Day82
Turns out the refactoring I was doing was just the tip of the iceberg.  
Read docs, got my PR reviewed by senior devs and looked at existing repos for standards.  
Ended up rehauling the whole project. But with this as a base, we are ready for future scaling  

### 20210707 Day81
Refactored code and made it more modular  

### 20210706 Day80
Fastest way to familiarize yourself with a giant codebase?  

Refactor and reorganize code but COMMIT NOTHING  
Basically, dismantle and reassemble differently  

If you end up improving it, you kill two birds with one stone  

### 20210705 Day79
HTTP 200 example JSON outputs were not showing correctly  
Experimented with a few different ways and had to bite the bullet of accepting imperfections (thanks for saving me from my tox side, teammate)  
Now we have sample successful responses!  

### 20210701 Day77-78
Learned about [gitflow workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)  
Started implementing it together with the team for better organizing the repo  
Little trick I learned from my teammate: name your branch the same as the ticket number + small explanation for better readability  
Will be writing Unit Tests for endpoints tomorrow  

### 20210623 Day76
Started using Black for formatting. Should've picked one earlier  
Also, if you set your default git difftool to VSCode you can stage and commit selected parts of your code  

### 20210621-22 Day74-75
Added some GET methods to the endpoints  
Also looking into gitx (a tool that allows individual lines to be commited)  
some methods are not working, so gotta fix those and then add the rest of the operations  

### 20210618 Day73
Pair programmed with a senior dev at work. It's unimaginable how much knowledge gets shared in casual conversation  
A lot of unknowns in our project made so much more sense and learned a lot of tips and tricks!  

### 20210616 Day72
Did not touch code today. Instead read a lot of fastapi and pydantic documentation  
Had an epiphany that we might be building an API proxy  
Will clarify tomorrow but would make life SO MUCH easier if that's what it is  

### 20210614 Day71
Migrated an individually owned repo to the big leagues in git. Mostly followed [this guide](https://smashingmagazine.com/2014/05/moving-git-repository-new-server/)

Couldn't push to the new remote due to conflicting master branches,  
new remote's ancient master branch had nothing  
old remote's recent master branch had some updates  

Was migrating from old remote to new remote
    
    git push --all new-remote

All branches were pushed okay except master.  
Originally planned to move default to another branch, delete master, push recent master to new remote and revert default to this recent master  
Instead just pressed F (for force) and Just. Pushed. Harder.

    git push -f <new_remote> <branch_name>


### 20210610 Day70
Clarified. First I need to get a JSON response (string) with my code  

    r = request.get("endpoint, path, param URL")
Then I'll need to json.parse(response) or something similar to convert it from string into a JS object  

    res_obj = r.json() 
    #OR
    res_obj = json.parse(r)
Then I need to map the available keys (essentially everything spewed from the giant db) to the required keys (from the front end's requirements) while dropping the unessential ones   
The copy values to new keys  

Before we do any of that, the required keys have already been defined by the product owners; must create models with those  
Now studying how to separate classes/files in python  

### 20210609 Day69 (Nice)
The api calls are working on Postman  
Seems like I'll need to write a Python script and use Requests to make the API call, then filter from this result  
I'm not really sure what to do with this filtered result.  
My senpai was talking about dynamic classes. Could be related, should ask  

### 20210608 Day68
Finalized scope and started building models from an existing templates file  
It's looking like an API wrapper imo  
There's a lot of data being returned from the big bad database  
We need to filter it down to what's needed in this project  
So the first thing would be to return all the data from the bigbaddb  
Then start filtering it down  


### 20210607 Day67
After a long (heart) break, finally started working on a new project at work.  
Repo ready, environment set, scope (not fully) defined, modeling tomorrow.  
