# Matrícula 


<div align="center">
   
[Documentación en Español](https://github.com/nekotletta/matricula/blob/main/README-es.md)

</div>

<div align="center">
<h2>Overview</h1> 
</div>

Matrícula is a project built explicitly to improve on University of Puerto Rico's (UPR) enrollment system. This project aims to showcase what could be possible if UPR decided to modernize their system. The project is built with a UX focus, to make it as easy to navigate as possible.

This project was used using React for the frontend and Django for the backend.

![Matricula showcase](https://github.com/nekotletta/matricula/blob/main/matricula-home.png)

<div align="center">
<h2>Context</h2>
</div>

UPR's enrollment system is an incredibly outdated system (built in the 70s), entirely built on a terminal, as opposed to a webpage.

This has always been a huge issue due to how unfriendly the whole system is for students. Students who use it for the first time are often confused and scared of it, since they've never used a terminal before. Not only that, but the navigation isn't straightforward either.

<div align="center">
<h2>FAQ</h2>
</div>

### Why was this project created?

This project was created as a showcase on what could be possible if UPR's system were to be modernized. It aims to address the complaints that students are the most vocal about.
### Is this project affiliated with UPR in any way?

No, this project is completely independent from the UPR. The only thing from the UPR that this has is the data for the courses.


### If I enroll in courses using this site, will it reflect on my actual UPR profile?

No, this project is not connected directly to the UPR in any way. This is just a showcase. If you wish to enroll on a course in the UPR, you must go to the university's site. 

### Who developed this?

This project was developed by a single computer science (CS) student for the UPR. Please note that due to this, not everything will work perfectly, or something you think should be in the project is missing.

<div align="center">
<h2>Features</h2>
</div>

The project has all the features that the enrollment system has, along with two additional ones.

### Registry and login

UPR's enrollment system has no registration, as all necessary information is in the university records. This project, however, doesn't have those records, meaning that anyone who wishes to use this platform must register.

#### How it was improved 

- Users don't need to provide their SSN to login to the platform.
- Users can create their own passwords, as opposed to relying on UPR's insecure authentication methods.

### Navigation menu

UPR's enrollment system doesn't have a straightforward way to navigate the terminal. Each page is a non-intuitive code that students are expected to simply memorize.

#### How it was improved

A straightforward menu was implemented, in which each page is clearly labeled. This menu can be accessed from every page with a simple click.

### User profile 

UPR's enrollment system already has a section in which the student can see the classes they are currently enrolled in.

#### How it was improved 

Cleaned up the presentation of the information. Added a section in which users can see which courses they have completed. This can help users keep track of their degree progress.
### Course schedule visualizer

UPR's enrollment system doesn't have this feature. This was built after seeing everyone rely on external sites, or writing courses by hand, to build their schedule. 

How it works: users can bookmark specific courses in the platform. These courses are saved, and can be accessed later to add them to their optimal schedule. 

### Enrollment 

The way a student enrolls in courses in UPR's system is not straightforward at all. It also, again, lacks the clicking-on-a-button function. Students need to enter specific codes and hit enter to enroll or drop a course 

#### How it was improved

A straightforward click-to-enroll menu was implemented. Students also don't have to type the codification of the course they wish to enroll in. Students can select classes from their bookmarked classes and that places the classes automatically to enroll in them.

### Classes lookup

UPR's system only has a basic search for every single class available.

#### How it was improved 

The course search is divided by faculties. Students select the faculty they wish to look for courses in.

The following features are not present in UPR's system:

- Search by professors: Students can search a professor up to only show the classes they teach.
- Bookmarking: Students can bookmark certain courses they may wish to enroll in. Bookmarked courses can be accessed when creating the optimal schedule.
- Advanced settings: Students can tweak the foklowing settings when looking for courses:
   - Only show courses with available spots
   - Only show student's bookmarked courses
   - Only show laboratory courses (useful for biology / chem / physics courses)
   - Only show courses are either in-person, online, or hybrid
   - Only show courses that start and end between specified times
   - Only show courses that are given during specified days
