# Course overview & procedure

For a solid number of years now, the majority of experimental work within science requires the use of computers. No matter if "simple" `literature search`, `data managment`, `data acquisition` or `analyses`, computer-aided research is almost impossible to avoid and if done right, can be incredible helpful and even enable new types of `analyses` to obtain insights that are otherwise inaccessible. Rather surprisingly to most folks, the efficient utilization of `computers` within `research` also includes `programming` or even requires it. Besides making `research` faster, more streamlined, efficient, stable, eaier to reproduce and less prone to errors, some parts of the  `research workflow` might actually require certain `programming skills`.

<p align="center"><iframe src="https://giphy.com/embed/sgZdwNkOH43wZOEUJ2" width="240" height="240" frameBorder="0" vspace="0" class="giphy-embed" allowFullScreen style="overflow-y: hidden;"></iframe></p><p align="center"><a href="https://giphy.com/gifs/parksandrec-episode-9-parks-and-recreation-rec-sgZdwNkOH43wZOEUJ2"><small>via GIPHY</small></a></p></p>

While most thesis projects (undergrad and grad), PhD and other positions that actively work with `data` expect `programming` knowledge and/or experience, most programs however don't enable students to gather this skill set as their curricula don't include respective courses or do not provide adequate support and time to hone this skillset. Obviously, we won't be able to turn you into experts on all things digital, but this course is intended to provide you with a good basic understanding of the necessary knowledge and tools to navigate the pitfalls of scientif work. Specifically, this course should build the basis for further endeavors, setting you up with everything you need to know for that (especially how and when to look for help).    

### TL;DR

Within this course we will explore what it means to be "digitally literate" and porvide you with a basic Setup, to scientific work using open source tools. To do so, we will follow a "learning by doing" approach in a tripartite manner. Starting from a basic introduction into `theory` (Block I), `common tools` (Block II) and `how to apply them in a scientific context` (Block III). Thus, we actively seek out `realistic examples` and deomstrate how an open-source `workflow` could look like.  Along the way we will also talk about important adjacent topics such as `computing environments` and `IDE`s.


### How to reach the content creators

<p align="center"><iframe src="https://giphy.com/embed/U6GunJi6B1o7ecMfKc" width="240" height="240" frameBorder="0" vspace="0" class="giphy-embed" allowFullScreen style="overflow-y: hidden;"></iframe></p><p align="center"><a href="https://giphy.com/gifs/justviralnet-funny-mistake-spelling-U6GunJi6B1o7ecMfKc"><small>via GIPHY</small></a></p></p>

The contact information of the instructors are as follows:

[Michael Ernst](https://github.com/M-earnest)

- Office hours: upon request
- E-mail: `ernst@psych.uni-frankfurt.de`
- preferred mode of contact: vie e-mail

```{admonition} How to address one another?
:class: dropdown
He/Him. When contacting me, please refrain from using honoraries and formal language, "Michael" or "you" is fine as long as the content is respectful, fair and constructive (I aim for the same when I reply).
However, please let me know if you have a preferred way of interacting with other folks, including how you would liked to be addressed, your pronouns and the level of formality.
```



### Gimme the details

Below you will find important details regarding the course summarized in a compact form. Please consult and familiarize yourself with the information presented there prior to and/or within the first few days of the course. 

#### When and where

The course will officially run from x , although homework and coding assignments may be open until the end of the semester (we'll discuss apropriate time-frames and course load with you, no worries!).

e.g.
<iframe width="425" height="350" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://www.openstreetmap.org/export/embed.html?bbox=8.661464452743532%2C50.12589530933526%2C8.67423176765442%2C50.130778644149046&amp;layer=mapnik&amp;marker=50.12833703902714%2C8.667848110198975" style="border: 1px solid black"></iframe><br/><small><a href="https://www.openstreetmap.org/?mlat=50.12834&amp;mlon=8.66785#map=17/50.12834/8.66785">View Larger Map</a></small>


#### What about the pandemic? 

This course is designed to be run fully online, so no worries! Although, We'll host a discord server where you can get in contact, as well as ask and get your questions answered.

If this ever changes, the following rules are in effect at the moment:

Until further notice, it is assumed that the course will take place in person. This may be subject to change given everything we experienced and learned in the last years. Therefore the course is setup in a way that would allow both in person and virtual meetings. Should changes to the course format be mandated, you'll be notified ASAP.
If you feel uncomfortable doing a busy commute to sit in a room with several other people, please let me know and I'll give my best to come up with a hybrid format. However, based on current regulations there won't be any recordings. Just in case: yes, everyone should wear a mask at all times (although this is not to be understood as an official regulation, as is not permitted by the university)!

<iframe src="https://giphy.com/embed/opPuISKbzCXAFHhZFJ" width="280" height="280" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/opPuISKbzCXAFHhZFJ">via GIPHY</a></p>



#### Can I use my calculator?

Well, depends on your calculator, but you'll need frequent access to a computer that can run Python. None of the analyses that we will be doing will be very computationally intensive, so this does not need necessarily be a modern or "fast" computer. Still, it will need to be running a standard operating system like Windows, Mac OS X, or Linux. Unfortunately, tablets running mobile operating systems (iOS, Android) probably won't work for this purpose. **If this is an issue for you, please get in touch with the instructor as soon as possible so that we can try to figure out a solution**. Regarding software and installation thereof, please check the next section.

<iframe src="https://giphy.com/embed/DHqth0hVQoIzS" width="240" height="103" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/maths-DHqth0hVQoIzS">via GIPHY</a></p>

#### How do I get all the software and do I have to apply for a loan to get it?

Nah, everything we'll use is [open-source software](https://en.wikipedia.org/wiki/Open-source_software) or at minimum free of charge and publicly available. 
Why? Because teaching students via [proprietary software](https://en.wikipedia.org/wiki/Proprietary_software) is just not fair and won't help anyone: students have to obtain licenses or use those from the university (which usually doesn't have enough for everyone), leading to tremendous problems regarding inequity now and in the future. Additionally, [opens-source software](https://en.wikipedia.org/wiki/Open-source_software) can do everything, if not more than [proprietary software](https://en.wikipedia.org/wiki/Proprietary_software) and is furthermore usually better supported, tested and documented, creating a fantastic sense of community. 

In order to help you get all the software required for the course, a [comprehensive installation instruction](x) was compiled. In a step-by-step manner it guides you through the installation process, covering several `OS`: `windows`, `macos` and `linux`. Now the installation of the required packages probably goes beyond the scope of how most people engage with their computers on a daily basis, therefore errors and following frustration may occur. **Please do not be discouraged! If any problems occur during the installation process, please contact me ASAP and we'll get that sorted out**

<iframe src="https://giphy.com/embed/CTX0ivSQbI78A" width="240" height="177" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/internet-computer-technology-CTX0ivSQbI78A">via GIPHY</a></p>

#### Where is everything?

All course materials (lecture slides, lecture demo notebooks, lab notebooks, homework assignments, etc.) will be available on the [course website](x), i.e. the one you're looking at right now. Everything will be completely open and free to use, thus constituting an [open educational resource](https://en.wikipedia.org/wiki/Open_educational_resources) you are **free to explore, enhance and share**. Thus, this website and all materials will also remain up for the entire duration of the course and beyond, ideally to end of the internet. The usage of this resource and the materials therein will be explained at the beginning and throughout the course.  

<iframe src="https://giphy.com/embed/c20UV66B7zCWA" width="240" height="155" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/superman-phone-looking-c20UV66B7zCWA">via GIPHY</a></p>

#### Syllabus and Text

As noted above, this page serves as the syllabus for this course, with the precise outline indicated in the [respective section](x). This syllabus is subject to change; students who miss class are responsible for learning about any changes to the syllabus.

Additional reading material might be added but will always be open & free with students being informed about any addition.

<iframe src="https://giphy.com/embed/9dFvgd4ID6ne0" width="240" height="135" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/community-nbc-ken-jeong-9dFvgd4ID6ne0">via GIPHY</a></p>

#### How to get those credits?


##### Exams and Assignments

There will be `# a number of homework assignments`. Assignments will be communictaed in the respective sections of this course and during the lectures.


##### Grading



##### Late Homework & Extension Policy

`Homework assignments` will in general have a clearly stated due date, so as to manage course load clearly. Exceptions will be communicated. Please check the respective sections of this course and don't hesitate to ask questions if things are unclear. Generally `Homework assignments` must be turned in on the due date in order to to earn participation credits for the course and receive full scores.  Homework assignments must be turned in on the due date in order to receive full credit. Homework assignment turned in less than 1 week late will be accepted but the score will be penalized by 10%. Homework has to be handed in via e-mail to the [instructor](ernst@psych.uni-frankfurt.de).

Late `homework assignments` will also be accepted under _exceptional circumstances_ (e.g., medical or family emergency etc.) and at the discretion of the instructor (e.g. exceptional "gedenotes a rare event) with no penalty. This policy allowing for exceptional circumstances is definitely a right, but courtesy to be used when needed and not abused. Should you encounter such circumstances, simply email the assignment to instructor and note "late submission due to exceptional circumstances". **You do not need to provide any further justification or personally revealing information regarding the details.**

##### Academic Honor Code

You are encouraged to discuss problem sets with classmates and work on them together, but certain written submissions must reflect your own, original work. If you worked with other students on a problem set, no worries, please include their names in a statement like "I worked on this homework with XX and YY" on the assignment. If in doubt, ask the instructor.
**Using online-ressources to help you programm is endorsed and advised, but please note that if code is copied from the internet without alterations and not clearly marked as such, this will be understood as an attempt at deception and treated as such.** The same goes for any kind of reproduction of any other published work, as per usual.

##### Notice about missed work due to religious holy days

We might miss some things, so please notify the instructors of your pending absence at least 7 days prior to the date of observance of a religious holy day. If you must miss a class, an examination, a work assignment, or a project in order to observe a religious holy day, I will give you an opportunity to complete the missed work within a reasonable time after the absence.


### Student Accommodations

- Please request a meeting as soon as possible to discuss any accommodations.
- Please notify me as soon as possible if the material being presented in class is not accessible.
- Please notify me if any of the physical accomodations are difficult to use or access for you.

### Code of conduct

This course has a `Code of conduct`. Please inform yourself about the specifics by carefully reading through the [respective section](x).

<iframe src="https://giphy.com/embed/l5s71uAp3CzKwxwkoZ" width="240" height="200" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/theoffice-nbc-the-office-tv-l5s71uAp3CzKwxwkoZ">via GIPHY</a></p>


### How to Get Your Question(s) Answered and/or Provide Feedback

It’s great that we have so many ways to communicate, but it can get tricky to figure out who to contact or where your question belongs or when to expect a response. These guidelines are to help you get your question answered as quickly as possible and to ensure that we’re able to get to everyone’s questions.

That said, to ensure that we’re respecting everyone's time we'll mainly answer questions between normal working hours (M-F 9AM-6PM). However, we know that may not be when you may be doing your work. So, please feel free to post messages whenever is best for you while knowing that if you post late at night or on a weekend, you may not get a response until the next weekday. As such, do your best not to wait until the last minute to ask a question.

If you have:

**- questions about course content** - these are awesome! We want everyone to see them and have their questions answered too, so either use the [hypothes.is](https://web.hypothes.is/) plugin, `e-mail` or the [GitHub repository](x).

**- a technical assignment question** - shoot an e-mail and make an appointment. Answering technical questions is often best accomplished ‘in person’ where we can discuss the question and talk through ideas. However, if that is not possible, post your question to `discord`. Be as specific as you can in the question you ask (and include error messages when appropriate!). And, for those answering, help your classmates as much as you can without just giving the answer. Help guide them, point them in a direction, provide pseudo code, but do not provide code that answers assignment questions.

**- been stuck on something for a while (>30min) and aren’t even really sure where to start** - Programming can be frustrating and it may not always be obvious what is going wrong or why something isn’t working. **That’s OK - we’ve all been there!** IF you are stuck, you can and should reach out for help, even if you aren’t exactly sure what your specific question is. To determine when to reach out, consider the 2-hour rule. This rule states that if you are stuck, work on that problem for an hour. Then, take a 30 minute break and do something else. When you come back after your break, try for another 30 minutes or so to solve your problem. If you are still completely stuck, stop and contact us (office hours, post on `discord`). If you don’t have a specific question, include the information you have (what you’re stuck on, the code you’ve been trying that hasn’t been happening, and/or the error messages you’ve been getting).

**- questions about course logistics** - first, check the [overview](x) & [syllabus](x). If you can’t find the answer there, first ask a classmate. If still unsure, post on `discord`.

**- something super cool to share related to class or want to talk about a topic in further depth** - feel free to post on `discord`, contact the instructors or come to office hours. 

**- some feedback about the course you want to share anonymously** - If you’ve been offended by an example in class, really liked or disliked a lesson, or wish there were something covered in class that wasn’t but would rather not share this publicly, etc., please fill out the anonymous Google Form*

*This form can be taken down at any time if it’s not being used for its intended purpose; however, you all will be notified should that happen.

### Acknowledgements
