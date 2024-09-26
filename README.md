# ECS179 - Gameplay Programming
## UPDATES FOR FALL 2024
The course is moving from Unity to Godot. 

# Syllabus
## Basic Information

### Instructor
Dr. Joshua A. McCoy, Assistant Professor  
Computer Science & Cinema and Digital Media Departments  
Email: jamccoy at ucdavis dot edu  
Office: 3033 Kemper Hall  
Office Hours: TBD   
http://joshmccoy.com  
https://faculty.engineering.ucdavis.edu/mccoy/  
~~https://www.twitter.com/deftjams~~  

### TA Team


### Course
Lecture Meeting Time: Tuesdays and Thursdays at 1:40-3:00 PM in Cruess 1003
Discussion: Tuesdays at 6:00-6:50 PM in  
Holiday:   
Final Examination Period:   

## Course Description

This course is about the design and development of nuanced and highly contextual gameplay systems built on the foundation of traditional game engines. Technical game development has many facets, including graphics engines, sound engines, networking, and animation systems. Many of these facets are well-established and provided for in modern game engines. The focus of this course is on the remaining areas that are difficult to abstract and engineer into game engines as they depend on the genre or details of a specific game design.

## Materials

Godot Engine version 4.3-stable Standard. Download [here](https://godotengine.org/download/archive/4.3-stable/).  

## Grading and Assessment

* [45] Group Game Project
* [45] Exercises
* [10] Participation and Attendance

### Grade Scale

Grade | Point Threshold
------ | -------
A  | 94
A- | 90
B+ | 87
B  | 84
B- | 80
C+ | 77
C  | 74
C- | 70
D+ | 67
D  | 64
D- | 60
F  | 0

### Exercises
The programming exercises consist of projects in Godot in which you must implement significant game systems or capabilities. These exercises are to be completed individually and will be worth equal points. Each will have two components, which are described below with a typical amount of grade points they are worth:
1. [70] The individual programming assignment.
2. [30] Peer-reviewing the work of another pseudo-randomly assigned student.
 
*Individual Programming Assignment* - The exercise repositories, with project descriptions and work specifics, will be distributed via GitHub Classroom. You will be responsible for completing the exercise objectives, code quality, and following the best practices described in class. Final submissions will be made via GitHub Classroom.

*Peer review* - For each programming exercise, each student will peer review another student's work. The reviewing student will be given access to the repository of another student's submission for review. The peer reviewer will be responsible for a code review based on C# style guides, an assessment of how well the submission achieved the objectives of the assignment and notes for improvement. This review should be done in the master branch and in the root directory of the repo (the same folder that contains the assignment's README). 

### Group Game Project

You will design and develop your own game given a set of themes and constraints in teams. Each team member will have a main role and a sub-role in the game.

### Quizzes

Light quizzes may be given during class meetings. Their contents will be based on recent lectures and readings.

### Participation and Attendance

Students are required to attend and participate in class, labs, and team meetings. Attendance will be taken during lectures and discussion sections.

#### Participation

Each submitted participation code is worth 1 grade point. You need at least five codes to max out your participation grade.

#### Attendance

The attendance rules are suspended while the course is offered remotely.  

The attendance algorithm is as follows:  
AttendanceGrade = Min(5, 5 * (SubmittedAttendanceCodes / (ClassesWhereAttendanceWasTaken - 1)))

## Schedule

Week | Topic | Reading | Discussion Plan | Assignments and Due Dates
----- | ----- | ----- | ----- | -----
1 | Overview of the course, game engines, anatomy of game development, command pattern. | Salen and Zimmermen ch. 4 & 5 | Dissecting Godot projects. | [Getting started with Godot materials](https://github.com/dr-jam/GameplayProgramming#preparing-for-projects)
2 | Unity structures, Code standards, best practices, style guides, camera systems, lerp. | [Command Pattern](https://gameprogrammingpatterns.com/command.html), [Style Guide and Best Practices](), [Scroll Back: The Theory and Practice of Cameras in Side-Scrollers](https://docs.google.com/document/d/1iNSQIyNpVGHeak6isbP6AHdHD50gs8MNXF1GCf08efg/pub) by Itay Karen. | Overview of Programming Exercise 1: Command Pattern |  [Exercise 1]()
3 | Gameplay mechanics, Game Events and the Observer Pattern.Data-driven game systems.| [Defining Game Mechanics](http://gamestudies.org/0802/articles/sicart) by Miguel Sicart, [Pubsub](https://gameprogrammingpatterns.com/event-queue.html) | Overview of Exercise 2: Camera Controllers | [Exercise 2: Cameral Control](),<br />  Exercise 1 Implementation
4 | Mechanics, rules, gameplay systems, component systems. | Salen and Zimmermen ch. 11, 12, 13, [Component design pattern](https://gameprogrammingpatterns.com/component.html) | Overview of Exercise 3 | [Exercise 3]()<br />  Exercise 2 Peer Review<br /> Exercise 1 Peer Review,<br /> Exercise 2
5 | Interactivity, factory pattern. | Salen and Zimmermen ch. 6, Crawford [The Art of Game Design, ch. 1, INTERACTION section](https://www.digitpress.com/library/books/book_art_of_computer_game_design.pdf)|  | Exercise 4,<br /> Exercise 3,<br /> Exercise 2 Peer Review
6 | Game combat algorithms, game design documents.| [The Craft of Game Systems](https://craftofgamesystems.wordpress.com/) by Daniel Achterman
7 | The Jump. | [Game Feel by Steve Swink](http://www.game-feel.com/) | | 
8 | Game AI: character behavior, agents, and real-time performance. | TBA | ~~Introduce pitches and game design docs with examples~~
9 | Procedural content generation. | TBA | ~~3 minute final project pitches from each group~~ | ~~Final project design doc due~~
10 | Game AI: analytics and applications of data science and machine learning. | TBA | ~~Final project demo~~ |

## Development and Design Resources


### Are you prepared?


[![World of Warcraft: The Burning Crusade Cinematic Trailer](https://img.youtube.com/vi/IBHL_-biMrQ/0.jpg)](https://youtu.be/IBHL_-biMrQ?t=142)  
*You are not prepared!*  
-- [Illidan Stormrage](https://youtu.be/IBHL_-biMrQ?t=142)

Illidan's words may resonate with you as computer science and game development are both difficult disciplines whose surrounding communities are laced with high expectations and elitism. Below are resources that can cut through assumptions and feeling though self-examination.

Introductory practice exercises for C# and game systems (you can run these in Unity, .Net, or MonoDevelop):
1. [Final Fantasy VI Combat System](https://docs.google.com/document/d/144-2AXOJX79Sw03EwPXGYxdZJOk0zqVZRnSgKHiStA0/edit?usp=sharing)
2. [Crystal Warriors](https://docs.google.com/document/d/1lvsscM-no1C31GW-NSpH_a2u4a2PGHmWhGRHpY7cxyk/edit?usp=sharing)
3. [Fantasy Fight](https://docs.google.com/document/d/1DX_LwKX4Yg7oCnHDdarZkJdcausVmn9BE9hKh_D-Fac/edit?usp=sharing)

[Unity and C# Practice Exam for New Programmers](https://docs.google.com/document/d/1_GUQKvwa-ZqboAhgp63pToQQvR6WdVvVJ3kcRDQ1qR0/edit?usp=sharing)

### Preparing for Projects

This is a 5-day regimen of training tutorials to learn the basics of Unity for use in this course. Each day consists of between 2 and 3 hours of material per day.

Day | Material
------ | -----
1 | [Create Unity Student Account](https://unity.com/products/unity-student) - [Start Creating](https://learn.unity.com/project/start-creating-1) - [Exploring the Editor Layout](https://learn.unity.com/tutorial/exploring-the-editor-layout-2019-3?uv=2022.3) - [Microsoft .NET Interactive Introduction to C#](https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/intro-to-csharp/) (ignore *101 Linq Samples*)
2 | [Roll-a-ball Tutorial](https://learn.unity.com/project/roll-a-ball) - [Scripting Overview](https://docs.unity3d.com/Manual/ScriptingConcepts.html), 
3 | [Beginner Scripting](https://learn.unity.com/project/beginner-gameplay-scripting) (You can use nearly any 3D project with this tutorial.)
4 | [Intermediate Scripting Tutorial](https://learn.unity.com/project/intermediate-gameplay-scripting) (You can use nearly any 3D project with this tutorial.)
5 | [Unity Tips](https://learn.unity.com/tutorial/unity-tips) (This is long; watch as many as you can or care to.)

### Unity

[Unity User Manual](https://docs.unity3d.com/Manual/index.html)  
[Unity Tutorials](https://unity3d.com/learn/get-started)

#### Learning the Basics

* [Important Classes](https://docs.unity3d.com/Manual/ScriptingImportantClasses.html) - Basic descriptions and links to MonoBehavior, Transform, and RigidBody(2D).
* [Unity C# class relationship diagram](resources/UnityClassHierarchy.png) (originally from this [Reddit post](https://www.reddit.com/r/Unity3D/comments/70ra7b/after_surprising_response_from_the_first_thread_i/))
* [Vector Cookbook](https://docs.unity3d.com/Manual/VectorCookbook.html) - A basic introduction to vector operations in Unity.
* [2D or 3D projects](https://docs.unity3d.com/Manual/2Dor3D.html) - A guide to the differences between 2D and 3D projects in Unity.
* [Graphics](https://docs.unity3d.com/Manual/Graphics.html) - The entry point to the graphics capabilities of Unity.
* [Physics](https://docs.unity3d.com/Manual/PhysicsSection.html) - The entry point to Unity's physics system.
* [Scripting](https://docs.unity3d.com/Manual/ScriptingSection.html) - The entry point into scripting in Unity.
* [Scripting Tutorials](https://unity3d.com/learn/tutorials/s/scripting) - An index of beginner, intermediate, and topical scripting tutorials and lessons.

### Additional Texts 
Vanhove, Sander. Learning GDScript by Developing a Game with Godot 4: A Fun Introduction to Programming in GDScript 2. 0 and Game Development Using the Godot Engine. 1st ed. Birmingham: Packt Publishing, Limited, 2024. Print.  
https://search.library.ucdavis.edu/permalink/01UCD_INST/1hjlc2p/cdi_proquest_ebookcentral_EBC31290475  
Entry-level text to basic Godot constructs and GDScript.  

Bradfield, Chris. Godot 4 Game Development Projects : Build Five Cross-Platform 2D and 3D Games Using One of the Most Powerful Open Source Game Engines. Second edition. Birmingham, England: Packt Publishing Ltd, 2023. Print.  
https://search.library.ucdavis.edu/permalink/01UCD_INST/9fle3i/alma9920761168606531  
Entry-level text to basic Godot constructs and GDScript.  

Wang, Wally, and Tonnetta Walcott. Programming for Game Design : A Hands-On Guide with Godot. 1st ed. 2024. Berkeley, CA: Apress, 2024. Web.  
https://search.library.ucdavis.edu/permalink/01UCD_INST/9fle3i/alma9920512123506531  
Entry-level text focusing on programming and GDScript suitable for those with a programming background in another language.  

Bradfield, Chris. Godot 4 Game Development Projects : Build Five Cross-Platform 2D and 3D Games Using One of the Most Powerful Open Source Game Engines. Second edition. Birmingham, England: Packt Publishing Ltd, 2023. Print.  
https://search.library.ucdavis.edu/permalink/01UCD_INST/9fle3i/alma9919503225306531  
Series of small game projects.  

Johnson, Jeff. Godot 4 Game Development Cookbook : Over 50 Solid Recipes for Building High-Quality 2D and 3D Games with Improved Performance. 1st ed. Birmingham, England: Packt Publishing Ltd., 2023. Print.  
https://search.library.ucdavis.edu/permalink/01UCD_INST/9fle3i/alma9919344194606531  
More advanced topics like shaders and multiplayer.  

Campos, Henrique. ESSENTIAL GUIDE TO CREATING MULTIPLAYER GAMES WITH GODOT 4.0 : Harness the Power of Godot Engine’s GDScript Network API to Connect Players in Multiplayer Games. 1st edition. Birmingham, UK: Packt Publishing Ltd., 2024. Print.  
https://search.library.ucdavis.edu/permalink/01UCD_INST/9fle3i/alma9920561598006531  
A more advanced text for learning Godot's networking libraries.  

Pitt, Christopher. Procedural Generation in Godot : Learn to Generate Enjoyable Content for Your Games. Berkeley, CA: Apress, 2023. Print.  
https://search.library.ucdavis.edu/permalink/01UCD_INST/9fle3i/alma9918897363706531  
A collection of entry-level PCG techniques mixed with reconstructions of existing  games.  

#### Learning C#
* [Getting started with C#](https://docs.microsoft.com/en-us/dotnet/csharp/getting-started/) from Microsoft .NET documentation.
* [Mastering C# : a beginner's guide](https://search.library.ucdavis.edu/permalink/01UCD_INST/9fle3i/alma9917226567406531)
* [Simple and Efficient Programming with C#: Skills to Build Applications with Visual Studio And .NET](https://search.library.ucdavis.edu/permalink/01UCD_INST/1hjlc2p/cdi_askewsholts_vlebooks_9781484287378)
* [C# 12 Pocket Reference](https://search.library.ucdavis.edu/permalink/01UCD_INST/1hjlc2p/cdi_safari_books_v2_9781098147532)

### Game Design

##### How Games are Made
* [Fallout: A Postmortem](https://www.gdcvault.com/play/1015843/Classic-Game-Postmortem) by Timothy Cain
* [Postmortem: Ion Storm's Deus Ex](http://www.gamasutra.com/view/feature/131523/postmortem_ion_storms_deus_ex.php) by Warren Spector
* [How Long Does It Take to Make an Indie Game?](https://www.gamedeveloper.com/business/how-long-does-it-take-to-make-an-indie-game-) by Joseph Mirabello

#### Design Documents
* [The "Core" of a Game](https://bbrathwaite.wordpress.com/2008/10/15/the-core-of-a-game/) by Brenda Romero
* [A Feature Set from a “Core”](https://bbrathwaite.wordpress.com/2008/10/17/a-feature-set-from-a-core/) by Brenda Romero
* [Creating a Game Design Document](https://bbrathwaite.wordpress.com/2008/11/30/creating-a-game-design-document/) by Brenda Romero
* [One Page Designs](http://www.gdcvault.com/play/1012356/One-Page) by Stone Librande
* [A GDD Template for the Indie Developer](https://www.gamedeveloper.com/design/a-gdd-template-for-the-indie-developer) by Jason Bakker
* [Effectively Organize Your Game's Development With a Game Design Document](http://code.tutsplus.com/articles/effectively-organize-your-games-development-with-a-game-design-document--active-10140) by Gamux

#### Game Feel
 * [Jan Willem Nijman - Vlambeer - "The art of screenshake"](https://www.youtube.com/watch?v=AJdEqssNZ-U) by Jan Wellem Jijman (Valmbeer)
 * [Juice it or lose it](https://www.youtube.com/watch?v=Fy0aCDmgnxg) by Martin Jonasson and Petri Purho

#### Production Cycles
* [The four phases of game development](https://www.gamedeveloper.com/business/the-four-phases-of-game-development) by Pascal Bestebroer

#### Development teams
* [pp. 39-56 of Game Development and Production](https://books.google.com/books?id=m5exIODbtqkC&lpg=PR1&pg=PA39#v=onepage&q&f=false) by Erik Bethke [free preview]

#### Techniques for Team Development
* [Scrum: A Breathtakingly Brief and Agile Introduction](http://www.agilelearninglabs.com/resources/scrum-introduction/) by Agile Learning Labs
* [Try Git: Code School](https://try.github.io/) by GitHub

#### Scrum and GitHub

* [Agile Lessons from Ryse and Crysis 3](http://www.gdcvault.com/play/1020790/Agile-Lessons-from-Ryse-and) by Patrick Payne
* [Beyond Scrum: Lean and Kanban for Game Developers](https://clintonkeith.com/resources/Beyond%20Scrum_%20Lean%20and%20Kanban%20for%20Game%20Developers.pdf) by Clinton Keith
* [git - the simple guide](http://rogerdudler.github.io/git-guide/) by Roger Dudler

#### Project Versioning and Control
* [GitHub for Noobs (1/4) – A Short History](https://youtu.be/1h9_cB9mPT8) by Travis Neilson
* [GitHub for Noobs (2/4) - Common Workflows](https://youtu.be/_ALeswWzpBo) by Travis Neilson
* [GitHub for Noobs (3/4) Using the GitHub Desktop App](https://youtu.be/BKr8lbx3uFY) by Travis Neilson
* [GitHub for Noobs (4/4) Using the Command Line](https://youtu.be/JPKOESR1k04) by Travis Neilson

#### User Interface and User Experience (UI/UX)
* [The Interface is Part of Gameplay](https://bbrathwaite.wordpress.com/2010/04/15/the-interface-is-a-part-of-gameplay/) by Brenda Romero

#### Game Trailers and Press Kits
* [Game Trailer and Press Kit](http://drive.google.com/open?id=1-cVwNxSJyvt37HPLE-af_c9y9iXNahkaXlVaJzGuToo)

## Attendance Policy
This course has no formal attendance policy. However, regular attendance is greatly recommended to succeed in the course, as many class meetings will involve programming and one-on-one learning. If you expect to miss more than three class meetings, please discuss the situation with your instructor. The instruction team reserves the right to penalize grades due to excessive absences. 

## UC Davis Code of Academic Conduct

The UC Davis Code of Academic Conduct (http://sja.ucdavis.edu/files/cac.pdf) will be strictly enforced in this class. In particular, plagiarism, academic dishonesty, and cheating will be dealt with severely.  Any breach of the Code of Academic Conduct can result in failing the assignment, failing the course, and disciplinary action via the Office of Student Support and Judicial Affairs (http://sja.ucdavis.edu/).

## Technology in the Classroom Policy
In general, the use of laptops and technology is encouraged in this course as long as they are not disruptive to the rest of the class. If you choose to use a device with a screen, please sit in the back of the room to avoid distracting your fellow students. You must ask for permission before making a video or audio recording in the classroom. In general, students will be treated as adults capable of managing their technological lives while being respectful of others in the classroom.

## Social Media Policy
Students are not permitted to make visual or audio recordings, including live streaming, of classroom lectures or any class-related content using any recording device (e.g., smartphone, computer, digital recorder, etc.) unless prior permission from the instructor is obtained and there are no objections from any of the students in the class. If permission is granted, personal use and sharing of recordings and any electronic copies of course materials (e.g., PowerPoints, formulas, lecture notes and any classroom discussions online or otherwise) is limited to the personal use of students registered in the course and for educational purposes only, even after the end of the course.

To supplement the classroom experience, lectures may be audio or video recorded by faculty and made available to students registered for this class. Faculty may record classroom lectures or discussions for pedagogical use, future student reference, or to meet the accommodation needs of students with a documented disability. These recordings are limited to personal use and may not be distributed (file share), sold, or posted on social media outlets without the written permission of the faculty.

Unauthorized downloading, file sharing, distribution of any part of a recorded lecture or course materials. or using information for purposes other than the student's learning is prohibited unless the instructor gives prior authorization.
