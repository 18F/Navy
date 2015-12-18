# Navy Agile Prototyping Workshop
This is a repository for the Navy's Agile Prototyping Workshop.  This is a publicly accessible website - please refrain from publishing content not for public consumption.  

```
Interested in running your own agile prototyping workshop?  [Read this article] (https://18f.gsa.gov/2014/10/21/how-to-run-your-own-3-sprint-agile-workshop/)and [this one on protosketching!](https://18f.gsa.gov/2015/01/06/protosketch/)
```

## Overview
Over December 15-16 the U.S. Navy and 18F worked together on an Agile Prototyping Workshop.  Over two days, three teams worked over 5 sprints to create prototypes for three user stories.

## The three user stories
The three user stories selected for the workshop are best represented by *Junior Officers*, *Detailers*, and *Contracting Officers*. Previous research was used to established the leading user story for each team.

## Junior Officers
For our workshop, the Junior Officers represent users that seemed most interested in learning about career advancement opportunities, job fit, and information and reputation scores about potential jobs.

###User story
As a junior officer, I want to know _______ about available billets, so that I can explore opportunities that fit my career goals.

###Demo
Demo of working Talentlink prototype: http://fuzzylogic.knackhq.com/talentlink

## Detailers
Detailers represent users that were primarily interested in filling open positions and helping the Junior Officers better manage their careers.

###User story
As a detailer, I want to know _____________ about available junior officers, so I can find the most qualified officer to fill a given billet.

###Demo
* ![Screenshot 1](/Images/Detailer_screen_1.png)
* ![Screenshot 1](/Images/Detailer_screen_2.png)
* ![Screenshot 1](/Images/Detailer_screen_3.png)
* ![Screenshot 1](/Images/Detailer_screen_4.png)
* ![Screenshot 1](/Images/Detailer_screen_5.png)
* ![Screenshot 1](/Images/Detailer_screen_6.png)

##Commanding Officers
Commanding Officers represent users that were primarily interested in understanding how well a Junior Officer fits into a given job, and being able to see a global view of all open positions and other information important to Commanding Officers (a command dashboard).

###User story
As a commanding officer, I want to know ___________ about junior officers, so that I can understand whether a junior officer is a good fit for my command.

###Demo
* ![Screenshot 1](/Images/CO_screen_1.png)
* ![Screenshot 2](/Images/CO_screen_2.png)
* ![Screenshot 3](/Images/CO_screen_3.png)

#After-Action Report
* We'll need to do some work to figure out how the findings of the workshop plug into what Navy is attempting to do, and where there's some overlap
* Can we collect feature requests based on user feedback?  Do we need to start that prioritization process now?
* We need a better sense for what some of the ideas shared during the workshop might mean for the rest of our systems.  Can we have a sandbox to test assumptions against?  How many systems are we looking at integrating?

A short to-do list:

* Better understanding the architecture
* Assessment of what would cause this to be a catastrophic failture
* Understand the security constraints and requirements
* We might like to plug into the real systems, but need to work towards that before we can overcome that.  We may need to start by working with sanitized data.
* Needs to be a clear pathway towards real integration.

Two key, short-term activities:

* Prototype using sanitized data to demonstrate the concept; and
* Looking at how we connect to the actual enterprise-level systems.

In a prototype, the way forward might be modeling the database in the prototype environment, and when ready, “flipping the switch” to hit the real data.  Staged enterprise integration - how do we eventually move systems over to the real system?  We have to consider all the major systems that we might touch?  Better understanding users that are affected by multiple login systems is important.  How do we solve the multiple layer login systems, and accreditation?  Are there elements of the system that could go live before others?

Two key themes that emerged from the workshop:

* Importance of Data Integration and Visualization
* Importance of understanding better the Workflows and New Business Processes

Others had success using a group of users to be earlier adopters of the system - would something similar work?  Can we deduplicate a slate based partially off of real data?  Can we build an MVP off of what is possible?  Macros duplicate some of the data transformation processes - what can we learn from those?  A focus on the base enterprise architecture requirements is also important.  

If we could build a pristine system from the ground up, what would it look like?  

One important rule we'll need to consider: any prototyped system cannot disrupt your job.

Establishing and communicating the clear product vision is critical.

##Retrospective
The following is a general retrospective on the workshop.

###What worked...
* time limits for teams (around 40 mins) to synthesize around a design
* Teams of 5 further breaking into pairs to sketch concurrently
* Dedicated individuals to design and dev
* Having user stories available pre-workshop to save time and jump right into prototyping
* Seeing three different user groups come together and sketch at the same time provided the benefit of crosspollination of ideas during demos and feedback sessions
* A visual representation helped frame the conversation
* We had the right number and right mix of participants
* Positive energy contributed to high value production
* Change of scenery during the day (different rooms) kept things fresh
* Introduction of easy-to-use prototyping tools was effective and empowering
* Having actual, clickable prototypes was very helpful, as is opportunity to get remote feedback on designs after the workshop
* Information collected and what showed up in the prototypes was not anticipated
* Good engagement across all groups

###What needs addressing...
* Logistics are important - shuffling between breakrooms can be difficult given short time to work during sprints, white boards and scratch pads in all rooms
* Managing group participation from all involved is important
* Hard to accomodate discussions around culture and institutional barriers
* We didn't establish detailed measures of success or a definition of done clearly enough
* More cross pollination the groups, more interaction would have been helpful
* Having time to figure out how all three prototypes might fit together would have been valuable (ran out of time, but felt close)
* I’d like to see if we could get to a point where we have a better way to describe individuals in the system
* Flexibility to introduce new user stories might be necessary at certain points in the process

###What didn't work.
* Jumping into prototyping without any discovery, even though research was available, was hard on some participants in the group
* Still difficult to get out of as-is model quickly during prototyping sessions - we need permission to get there
* Difficult to address constraints (like the availability of data) within the short time period
* It proved hard to address all questions regarding agile and process within allotted time
* Needed more opportunities to collect feature requirements, what’s the longer term vision, more user perspectives
* Sometimes difficult to separate the technical possibilities from the business processes

#Resources

## Slides
Slides for the workshop [can be found here](https://docs.google.com/a/gsa.gov/presentation/d/1TKOt2pSmpcYFTo7Ud2Fs-eqkwFjcghz_jV1E--ENvzE/pub?start=false&loop=false&delayms=3000).

## The agile process and user centered design in government initiatives
* 18F's own dashboard and description of phases - see https://18f.gsa.gov/dashboard/
* Building digital by default - https://www.gov.uk/service-manual/start
* U.S. Digital Services Playbook - https://playbook.cio.gov/
* On acquisition strategy: U.S. Digital Services TechFAR Handbook - https://playbook.cio.gov/techfar/
* Choosing design over architecture blog post - https://18f.gsa.gov/2015/11/17/choose-design-over-architecture/

## Some examples of tools to get you started with sketching...

* Powerpoint + [Keynotopia](http://keynotopia.com/tutorials/)
* [Balsamiq](https://balsamiq.com/)
* [Invision](invisionapp.com)

## Other examples, resources and writings of interest...

### Open Opportunities Dashboard
The Open Opportunities Dashboard allows government employees a way to find short-term assignments (with supervisor approval) and advertise skillsets they have.  Open source repository is [here](https://github.com/18F/openopps-platform).
[https://openopps.digitalgov.gov/](https://openopps.digitalgov.gov/)

### Medical Matching Service 
See http://www.nrmp.org/

