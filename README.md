# Intro to DevOps from a Network and Telephony Perspective

DevOps is the new hotness and/or buzzword in the Technology industry.  This document is a brief overview of what I've learned recently DevOps is and things a Network / Telephony / Infrastructure engineer needs to know to stay relevant in the industry.

## What is DevOps?

Here's the Google Link to Wikipedia.
[Wikipedia link to DevOps Definition](https://en.wikipedia.org/wiki/DevOps)

It's the merging of Software Engineering and Infrastructure engineering into one team or group.

In a practical terms, the Infrastructure teams are going to be looking for Software Engineers to add to their teams rather than more Infrastructure Engineers.  Your skills will have less of a demand in the market place if they don't also include some Software Engineering Skills.

## What does this mean to you?
In the next 5 years I predict all new Network / Telephony / Infrastructure gear will be be programmed primarily via API's.  

This means as an Infrastructure Engineer you need to learn new skills.

* What do Software Engineers do?
* What tools do they use?
* What is an API?
* How can I use it to make my box do stuff?

*I didn't mention learning software languages.  I believe this will be useful, but not required at first.*


## Why do I need to learn this?
I come from a Telecom background.  In the early 2000's when IP Telephony started happening, Telecom engineers who wanted to stay relevant had to learn new skills.  What's in IP address?  What a subnet?  The network engineer didn't care about this.  Nor did s/he have to.  They already had enough on their plate without having to learn about dial plans and hunt groups.  

It was painful at first, I had to get my CCNA, but once I did, it made working in the space much easier because I could speak their language and tell them what i wanted / needed.

The same shift is occurring with the move to the DevOps Model.  Software engineers don't care about Telephony Dial Plans or Subnets.  They care about API's, Collaboration Tools, Open Source and various other things that I'm not fully aware of at this point in time.


## Do I need to learn to become a programmer?
Yes and No.  The more you learn, the more useful you'll be in the long run, but you're talking years of learning and studying to get good at it.  Unless you find you're really passionate about learning to program, you don't really need to.  You mostly need to know how to talk to the programmers and how to let them know what is needed.

To be clear, you'll need to know the basics, but as far as the more advanced things, that will come with time.


## Where do I start?
**Start with [GitHub](http://www.github.com)**

* Create an account.  
* Learn how it works.
* Pull down this document onto a local repository and edit it.
  * At the end I'm going to have a visitor log, add your name to this document.
  * If you have some edits you'd like to make, go for it.  I'll review and commit if they make sense.
  * This document is at https://github.com/joej164/DevOps-Getting-Started

Use this document as a way to practice contributing to other people’s GitHub accounts.  Create your own.  

I'm creating this document as a way of understanding how GitHub works as well as a also helping spread my knowledge I've learned in the last several months.

**Learn [Postman](https://www.getpostman.com/)**

This is a tool for parsing REST API's.  I think you can also use it for SOAP API's also, but i've not investigated.  What's really cool is you can create functional code snippets for whatever language your Programmers want to use.  

At that point, it's really easy to create scripts.  The code may not be nice and pretty, but they it works.

Pro Tip:
*There are 2 versions of Postman, thick and thin.
Use the thick client if you're working on Lab Boxes.
The Google Plugin doesn't work well with devices that require HTTPS but don't have secure connections.*



I plan on writing a guide to using Postman from a non-programmers point of view.  I'll link that here in the future.

**Learn API's**

Google Maps has an easy REST API, look that up.  A number of other open source tools have REST API's on the public internet.  Do some google searches, then use Postman to start querying them.

Once you have the basics down, move on to understand how your devices API work.  Your Software Engineers aren't going to know the ins and outs of your devices, that's your job.  Make it easy for them and they'll make your life much easier.

## Learn a programming language
Once you've figured out how to query API's then start worring about a programming language.

* Pick a programming language to learn, start with one
  * JavaScript is the language of the web browsers
    * Node.js is a standalone version of JavaScript that doesn't require a web browser to run the code.
  * Python 3 is fairly easy to learn
    * It is being adopted by Cisco for a lot of their training
    * Good business language as it's easy for other people to read, even non-programmers
  * Both options are free and lots of training exists on the web for these topics

*Python 2 and Python 3 are similar but different.  Python 2 is end of support in 2020, so learning Python 3 would probably be a better choice long term.*

## Other things to learn

The following are some topics I think are going to be useful in not sounding completely lost when talking to programmers.

- Containers: This is another way of abstracting an operating system that's coming up in the industry
  - Docker is one program
  - Kubernetes is another
- Open Source: Understand what this means and programmers love it
- JSON vs XML: Why do programmers love JSON and hate XML?
- IDE: Integrated development environment
- I'm sure there are others, please mention them to me or propose an edit.


# Visitor Log
Want to practice doing a commit to someone else document.  Put your name (even a fake name) on the lines below.  Include a funny joke, or some Markup emoticons.  Keep it clean and I'll merge it into this doc. 

Also, if you have an idea for an improvement, let me know, we can expand this doc, or create a new doc.

**Visitor Name**
- Joe Jacobs: Author of this doc
