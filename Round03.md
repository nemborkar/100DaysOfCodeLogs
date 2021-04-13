# #100DaysOfCode Round03 Log - Nem Borkar

The log of my #100DaysOfCode challenge. Started on [February 22, Sunday, 2021].

## Log

### 20210410 Day40

Finally wrote out the API function and complex queryset from yesterday in Django  

Next step is to figure out how to pass a list of integers through kwargs from the front  

Then plug the API into the rest of the project to start testing and optimizing  

### 20210409 Day39

Wrestled with Django QuerySet API; trying to understand a giant query with a subquery inside it. Based on this one, I need to write my own that will be slightly more complex as it will take multiple inputs  

This is more headache than I initially planned for  

### 20210409 Day38

Trying to take it easy on the weekend, so started reading the section about Data Structures in Cracking the Coding Interview  

### 20210408 Day37

Figured out the dependencies in the Django project and started writing the new API  
Also read about things to prioritise when writing code  

## Macro Mindsets:  
* Correct
> should work on all expected AND UNEXPECTED inputs
* Efficient
> Big O with time and space complexity  
* Simple
> Short and Sweet  
* Readable
> Anyone should be able to read and understand what's going on; use comments to explain  
* Maintainable
> Can be easy to change  

## Micro Habits:  
* Use Data Structures Generously
> if it doesn't impact big O time, use them generously
* Appropriate Code Reuse
> can you write generic functions that can be used for reusability
* Modular
> many little functions to do specific things > a giant script with global variables lol
* Flexible and Robust
> basically should scale well regardless of input
* Error Checking
> kinda like input validation; DO NOT FORGET

### 20210407 Day36

Nothing too intensive today. Learned about various software licenses.  
So far I love the MIT one followed by BSD  

Probably gonna be rebuilding an API tomorrow  

### 20210406 Day35

Setup the venv and IDE for this but mostly refamiliarized myself with an old project that I'm gonna get back into  
Good to return to python and django after dealing with the bane that is CSS  

Read a bit into BCR (best conceivable runtime) and where to draw the line when it comes to code optimization. It's interesting to see how if your BCR is O(n), everything that is O(n) or below can be counted within that time.
 
### 20210405 Day34

Mostly closed out for the client today  
Managed to hotfix a bug on my last day. The previous dev used a lot of intermediary tools, so was hard to pinpoint problems. Just very poorly designed and documented; or more like, used as an experiment to learn new stuff.  
Our changes in the file were not being reflected on the front end and I thought it was because they discontinued the customization options. So I went another way and made changes on the back end at the database level. Changes were approved but something else broke today and the office Dwight was adamant that the customizations can still be done!  

So I pulled the old code from the github repos and webpacked it together. Still didn't work  
Dwight was trying older versions of the code but then it hit me to use the minified code directly into the site instead of going via dropbox  
To my disbelief, it worked. I wasted my last week because dropbox was not passing the file  
The issue is, it's hard to work under pressure without a second opinion or a person to bounce ideas off of  
I finally see why pair programming is even a concept  

### 20210404 Day33

Installing djangorestframework globally on my machine solved yesterday's problem #DerpMoment  
Apparently, had installed it in the venv but not on my machine globally  

Finally finished writing the REST API in Django  
Will mess around with it and document the bare essentials tomorrow  


### 20210403 Day32

Trying to build APIs with Django REST framework and [this tutorial](https://medium.com/swlh/build-your-first-rest-api-with-django-rest-framework-e394e39a482c)  
Can't seem to import from the rest_framework package into the myapp/serializer.py file for some reason. Even tried in a different IDE to no avail.  

Folks on the overflow say it could be an issue with the virtual environment... will try to recreate it tomorrow  
