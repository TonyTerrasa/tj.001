# Welcome

Hello, this is my first attempt at a CATSOOP course for learning English! The purpose of this site is to post materials and and questions for use in both private and for in-school lessons. 

My basic goals were to:
- [x] post various types of questions with instant feedback including multiple choice, fill in the blank
- [x] post readings for students to read
- [x] publish the site so it can be available publicly for my students

All of these having now be achieved, I'm moving towards:
- [x] create and store student accounts
- [x] how to direct the domain directly to the website, not to the CATSOOP home (might at some point submit this to the documentation)
- [x] how go set up student accounts?
- [ ] admin page to see student submission, account enrollment, etc
- [ ] allow students to submit extended response questions to me so that I can read them on my own
- [ ] how to allow file submissions (like if I want to be able to listen to their audio)
 
# Progress Log

## December 9 2022
Now at a relative point of fluency. I've been able to add a lot of class activities and even added practice exercises for both my private and in-school studetnts. These activities have answers-checkers. 

I'm still not sure how I see the performance of my students on these exercises. For right now, it's not urgent, but a big goal moving forward is the to figure out account admin for if I want to use this structure moving forward for classes where I'm the head teacher.


## October 16 2022

I've now successfully used the website as a way to distribute information and instructions in class. 

I was able to fix the issue of having the domain go directly to my specific CATSOOP page (not the default CATSOOP landing page). 

I've figured out how to make it so that students can make accounts. Problem is that as far as I can tell, CATSOOP is looking at the authentication type specified in my server's catsoop config, not the authentication type specified in the `preload.py`. 

Specifically for my applications, as I'm adding a lot of new content to the site constantly. 

## October 8 2022

First sucessful deployment where you could access the site from a public URL. 

For right now, I don't like that if you go to the domain, you get to the page home catsoop page. Instead, I want the URL to go directly to the page.

## September 16 2022

Today, I learned that in order to see real changes as I am making them, I need not restart catsoop, rather just reload the page

Today, I also explored the main `preload.py` file which containts information on users, colors, and the navigation of the coarse site.
