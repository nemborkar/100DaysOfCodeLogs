# #100DaysOfCode Log - Nem Borkar

The log of my #100DaysOfCode challenge. Started on [February 22, Sunday, 2021].

## Log

### 20210312 Day17

Here's something I'm trying to figure out: my local Starbucks' wifi doesn't allow #VPN traffic.  
Not sure if it's the ports that get blocked or explicit 'no-encryption' rules or somehow disallowed at a DNS level or something else.  
Built a small checklist to troubleshoot this  

Side note, my pull request from yesterday was merged into the main project. Best. Birthday gift. Ever!!

### 20210311 Day 16

Remember the API I miserably failed to improve on Day 8 and somehow did it by just removing code on Day 11? Well, it came back to haunt me today.  

Turns out it was being called by another page too. BUT my idea to make it modular got the thumbs up! So I did it and latency improved by 33%!  

Probably the last big achievement of my 20s!  

previously combined,  
details page: 900min-1600max ms  
graph page: 1000min-3800max ms  

after making them modular,  
details page: 700min-1400max ms  
graph page: 800min-2500max ms  

### 20210310 Day 15

Brushed up on Data Structures and Algorithms for more complex parts to come.  
Getting a new client next week, so learning their stack.  

### 20210309 Day 14

Played around with Python runtime optimization techniques  
Took extensive notes; should try coding challenges with these rules for optimization  

### 20210308 Day 13

Took a deep dive into Big O to improve the running time of code. Gotta look into Python specific optimizations tomorrow.  

### 20210307 Day 12

To add some variety, started reading Cracking the Coding Interview  

### 20210305 Day 11

Tried to get a better understanding of how the api calls are made and how the functions are invoked. Learned that **kwargs are passed from the URL.  

Turns out the API was delivering a small history list with a hefty for loop behind it. Didn't seem to be useful on the front end. So tried to remove. Latency improved significantly. No changes to the front too! Submitted my first PR at the new job  

### 20210304 Day 10

The overall goal is to improve the loading time of the graphs; perhaps I can take a look at some of the other functions and get some ideas.  

Actually, trying to speed up loading times for a JsonResponse object in Django  

Tomorrow we try out,  
- Lists, Tuples and other object types? instead of dictionaries
- A different type of encoding for the JsonResponse
- Actual code optimization 


### 20210303 Day 09

Mostly went through documentations today.  
Learned more about how models are connected to the database and how to write querysets.  

Practiced writing QuerySets with Django's QuerySets API; very fun, kinda intuitive  

Tomorrow:  
Don't read all but go through the [QuerySet API reference doc](https://docs.djangoproject.com/en/3.1/ref/models/querysets)  
Learn how to render the data to the templates/views  

Later:  
Gotta think about writing fast, optimal querysets  



### 20210302 Day 08

Ended taking up a challenge to optimize an api. Learned a lot about Django ORM.   
Encountered a procrastination mindset; gotta be aware of that and careful.  
Couldn't actually do anything, so feeling kinda down but I have a lot to learn.  
Gotta pick up and continue.  


### 20210301 Day 07
Day 7 of #100DaysOfCode  

Started working with a larger team on a real project today. Very excited with the new job! The CTO gave me a tour of the project. Got venv setup today and basically looked at the structure of the project.  

After trying to run the server, what I thought was a package version issues, turned out to be me working on the wrong branch lol. Learned about how to correctly read remote and local git branches.
[Essentially remotes/origin/main vs main, respectively]  

All in all a good day; learned a lot!  


### 20210228 Day 06
Yet another busy day and got home with just enough time to do the 1 hour of code  

Pulled objects from database to display on the main page  
Got HTTP POST to work  

Input is not being validated correctly and the form isn't saving.  
Will look into this tomorrow.  


### 20210227 Day 05
Couldn't do much yesterday and today was busy too but pushed through to finalize the database model and added forms. Really wanted to power through and get this done but need sleep and my 1 hour is out.  

Tomorrow, accept inputs on the HTML page and make sure the object is added all the way in the database  


### 20210225 Day 04 
Was low on motivation but managed to pull a pretty productive hour  
Project was lacking a base.html and got home.html to extend from it  

Explored bootstrap and my goodness, this simplifies SO MANY THINGS. The docs are super helpful with examples to work with. I wanna deep dive into this when I need to work on a more formal project. Just brilliant <3  

Gonna rethink the models tomorrow and add forms to actually add objects to the database  



### 20210224 Day 03
Made a new repo for logs  

Now to continue with the todo app and front end side of things.  

Features to add,  
- [x] 1 - have a link on the main page to the todos page  
- [x] 2 - make sure there's a box/form over the add button to accept input;  
[Tomorrow] 3 - make sure this creates an object in the database  

Refamiliarized myself with the old project and chose some features to add. Almost started a deep dive into Django redirect() but looking at a sample project on stackoverflow, what I actually needed was a simple URL built-in template instead  

Link for Redirect deepdive: https://realpython.com/django-redirects/  
Might do that in tomorrow's study session  



### 20210223 Day 02
Spent 2 hours figuring out why my site on netlify couldn't clear fcc's tests and tinkering with github to register commits so the site gets updated  

Decided to just use the inbuilt IDE on fcc just to get things going; the curriculum could've just been a link to the docs  
It's too basic, the ratio of learning to time spent is poor, so dropping that curriculumin favour of articles and best practices docs  

I really don't think following a tutorial/curriculum is the way to go for this. Going back to my own projects (that will actually be useful in the new job) So I will study something for 1 hour and build it for the next. That's the new plan  


### 20210222 Day 01
Been already working on a simple Django app; putting that on hold.  
Starting with this [Quality Assurance](https://www.freecodecamp.org/learn/quality-assurance) course to write reliable code and improved tests.

Started the quality assurance curriculum on fcc  
Chose to use Netlify to deploy sites on  
Spent the hour configuring the Netlify CLI and test site  
Ran into some unknowns with build commands and publish directory but figured it out eventually  
Will actually get to work on the fcc JS tomorrow  

