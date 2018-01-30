Title: CDS-001-001 Syllabus
Author: Dr. Glasbrenner
Author_Image: https://www.gravatar.com/avatar/49802fdfa5a0e63b3d932a5179d41c1e
Date: 2018-01-23 13:30
Course_Title: Introduction to Computational and Data Sciences
Course_Number: CDS-001-001
Semester: Spring 2018

## Description {#course-description data-magellan-target="course-description"}

During this course, students will develop basic skills for obtaining, cleaning, transforming, and visualizing real-world datasets using the R programming language and the RStudio integrated development environment.
Statistical methods for analyzing, interpreting, and predicting dataset trends are then introduced and approached from a computational point of view using randomization and simulation.
Additional topics may be covered, such as an introduction to advanced or special topics like cross-validation.
Throughout the course emphasis is placed on documenting one's scientific work using RStudio in conjunction with Github to fulfill the principles of reproducible research.
Connections are highlighted between statistical inference and the scientific method and how this is related to both the scientific method's power and its limitations.
These tools will also be used to critically examine statistical claims reported in mass media, demonstrating how scientific literacy and a basic knowledge in statistics are indispensable tools to making sense of our modern world.

*   **Classroom:** 1004 Exploratory Hall
*   **Meeting times:** Tues/Thurs 1:30pm -- 2:45pm
*   **University holidays:** Spring break, Mar. 12 -- Mar. 16 (no class)
*   **Credit hours:** 3.0 credit hours
*   **Prerequisites:** None, but a background in algebra is assumed.
*   **Mason Core:** Natural science (+lab when taken with CDS 102)

## Instructor {#course-instructor data-magellan-target="course-instructor"}

![](https://www.gravatar.com/avatar/49802fdfa5a0e63b3d932a5179d41c1e?s=128)

Dr. James K. Glasbrenner

*   **Office**: 253 Research Hall
*   **Phone:** (703) 993-4512
*   **Email:** [jglasbr2@gmu.edu](mailto:jglasbr2@gmu.edu)
*   **Office hours:** Tues. 3:00pm -- 4:00pm and Fri. 11:00am -- 12:00pm, or by appointment.

## Objectives {#course-objectives data-magellan-target="course-objectives"}

By the end of the course, students will be able to:

*   Use Github for collaborating on a reproducible research document
*   Obtain, clean, transform, and visualize a dataset using the R programming language
*   Interpret, and predict dataset trends using statistical inference and models
*   Critically examine and interpret statistical claims reported in mass media

## Materials {#course-materials data-magellan-target="course-materials"}

### Textbooks

This course utilizes two free textbooks that are made available under Creative Commons licenses:

::: {.textbook}

*   R for Data Science: Import, Tidy, Transform, Visualize, and Model Data
    *   Hadley Wickham
    *   Garrett Grolemund

![](/img/r4ds_cover.png){alt="R for Data Science textbook cover"}

[Click here to read the textbook for free online.][r4ds-online-ebook]

This is the free, [open-source][r4ds-github] data science textbook that we will use throughout the course.
This textbook is available under a [Creative Commons Attribution-NonCommercial-NoDerivs 3.0 United States License][r4ds-cc-license].

If you would like a physical copy of the textbook, you can [order it from Amazon][r4ds-amazon].

:::

::: {.textbook}

*   Introductory Statistics with Randomization and Simulation
    *   David M Diez
    *   Christopher D Barr
    *   Mine Çetinkaya-Rundel

![](/img/isrs_cover.png){alt="Introductory Statistics with Randomization and Simulation textbook cover"}

[Click here to download a free PDF copy of the textbook.][isrs-online-ebook]

This is the free, [open-source][isrs-github] statistics textbook that we will use during the second half of the course.
This textbook is available under a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported license (CC BY-NC-SA)][isrs-cc-license].

If you would like a physical copy of the textbook, you can [order it from Amazon][isrs-amazon].

:::

### Software

During the course, we will use the following free and open-source software to manipulate data, perform computations, and write documents:

*   Programming language: R ([https://www.r-project.org](https://www.r-project.org))
*   Version control: Git ([https://git-scm.com](https://git-scm.com))
*   PDF export: LaTeX ([https://www.latex-project.org](https://www.latex-project.org))
*   Programming software: RStudio ([https://www.rstudio.com](https://www.rstudio.com))

RStudio sits on top of R, Git, and LaTeX and provides a user-friendly interface to using these programs.
You can think of R, Git, and LaTeX as plugins that activate RStudio's main features.
In practice, RStudio is the software application that we will learn to use during the course.

*Students are highly encouraged to use Anaconda ([https://anaconda.com](https://anaconda.com)) to install the latest version of R, RStudio, and its other dependencies.*

### Platforms

The course will be administered through the following online platforms:

*   Course website ([http://spring18.cds101.com](http://spring18.cds101.com)) 
*   Github ([https://github.com](https://github.com/))
*   Slack ([https://masoncds101.slack.com](https://masoncds101.slack.com)) 
*   Blackboard ([https://mymasonportal.gmu.edu](https://mymasonportal.gmu.edu/))

The course website operates as the central repository for course materials, including an up-to-date schedule and posted slides and handouts.
Slack is the primary communication medium, replacing email (see the [Contact policy](#contact-policy) below) and serving as a discussion board.
Github is used for storing your classroom files, distributing and collecting homework assignments, handing out example code, and for project collaborations.Blackboard will be used for posting grades.

## Policies {#course-policies data-magellan-target="course-policies"}

### Contact policy

*All* correspondence is to be done using the private, invite-only Slack workspace for the course.
Direct messages on Slack are to be used for contacting me instead of emails.
Your Slack username *must* be registered and associated with your Mason `@gmu.edu` email address at all times.

My ground rules for direct messages are as follows:

*   I check and respond to messages during normal university hours.
*   Allow up to approximately 24 hours for a response during normal hours. 
*   Just because I view a message does not mean I will respond right away.
*   I generally don't respond to messages over weekends and school holidays.
*   If your questions are involved enough, I will ask you to come to office hours or schedule a Skype chat.
*   *On email:* During the first two weeks of the course, emails will be responded to, but I will send you my response on Slack.
    After two weeks, emails will be ignored.[^email-policy-footnote]

**[Please Note:]{.smallcaps}** the CDS-102 labs are a separate course from CDS-101.
I do not answer questions for the lab.
All correspondence regarding labs are to be directed to the teaching assistant.

### Attendance policy

Students are expected to attend every class and are responsible for obtaining and understanding the material that they miss, including any examples that derive from resources not available online.
Any missed work during an unexcused absence cannot be made up.
Unexcused absences, frequent tardiness, or leaving class early will reduce your participation grade.

Absences due to religious holidays, scheduled varsity sports trips, and short-term illnesses should be brought to my attention as early as possible.
Any make-up work is to be completed within 24 hours.
Exemptions may be granted at my discretion.

### Late work policy

Unless otherwise noted, assignments are to be submitted by 11:59pm on the due date.
The following penalties apply for most assignments (please note that weekends count as days):

*   First day late, by 11:59pm: -10%
*   Second day late, by 11:59pm: -20%
*   Third day late, by 11:59pm: -30%
*   Fourth day or later: no credit

The writeup for the midterm project and your final course portfolio are exceptions and must be submitted by the due date.
Late submissions will not be accepted.

Presentations, such as for the midterm project or the final interview, must be given on the scheduled date and cannot be made up.

Extensions or exemptions may be granted in the case of illness or a family emergency at my discretion, and it is the student's responsibility to inform me about these kinds of circumstances as soon as possible.

### Regrading appeals policy

Regrade appeals need to be in writing, printed out, and hand delivered to me within 48 hours of receiving back an assignment (not including weekends).
Appeals via Slack or email will not be accepted, no exceptions.
Appeals are only to be used for correct answers being marked as incorrect, misapplication of the grading rubric, or incorrectly tallied points.
Submissions need to clearly state what you want regraded and to justify the request by citing evidence[^regrading-appeals-footnote].
The number of points a question, exercise, or rubric category is worth or that were deducted for an incorrect answer or mistake cannot be appealed and are not up for debate or negotiation.

If I'm not available when delivering a request, please see Natalie Lapidot--Croitoru (231 Research Hall) or Karen Underwood (373 Research Hall).
Ask them to initial the request, write down the date and time of receipt, and to hold it for my pickup.

### Extra credit and grading curves policy

Individual requests for extra credit or a grading curve will not be granted, no exceptions.
Any opportunities to earn extra points will be offered to the entire class.
Grading curves are handled on a per-assignment basis and are applied to all students equally.

### Accommodations policy

Students with disabilities who need academic accommodations, please see me and contact the Office of Disability Services (ODS) at (703) 993-2474.
All academic accommodations must be arranged through the ODS: [http://ods.gmu.edu/](http://ods.gmu.edu/).

## Grading {#course-grading data-magellan-target="course-grading"}

### Breakdown

| Category           | Weight |
| :----------------- | :----- |
| Participation      |    10% |
| Reading responses  |    15% |
| Homework           |    25% |
| Midterm project    |    25% |
| Final project      |    25% |

### Schema

Based on the final total score, your final grade will be determined as follows:

| Score Range | Final Grade |
| :---------- | :---------- |
|     97--100 | A+          |
|      93--96 | A           |
|      90--92 | A-          |
|      87--89 | B+          |
|      83--86 | B           |
|      80--82 | B-          |
|      77--79 | C+          |
|      73--76 | C           |
|      70--72 | C-          |
|      65--69 | D           |
|         <65 | F           |

## Expectations {#course-expectations data-magellan-target="course-expectations"}

### Participation

Students are expected to come to class prepared.
Most course topics will require some amount of programming, which is a skill that's best learned by doing.
In-class activities and exercises will be provided to re-enforce these concepts, which at times may be completed in pairs or in groups.
Students are expected to give their full effort while completing an in-class exercise and to complete it within a reasonable timeframe.
A combination of speed of completion and quality of work will be factored into your participation grade.
A student's number of absences during the semester will also factor into his/her participation grade.

### Readings

Reading assignments will be regularly scheduled during the semester.
They will be posted on the course schedule with reminders sent via Slack.
Students are to complete the reading assignments by the specified date and be able to discuss it in class.

To help foster discussion of the reading assignments, students will be required to post one question per reading on Slack.
Posting more than one question per reading is encouraged.
Students are also required to reply to at least 10 questions during the semester and provide an answer.
These replies need to be spread out so that questions are answered throughout the course.
As such, a bare minimum of 5 answers need to be posted between January 23rd and March 9th, and another minimum of 5 answers need to be posted between March 19th and May 4th.

Some additional rules about the reading posts:

*   All questions and answers for the reading are to be posted in the `#4-discussion` channel.
*   Your question and answer posts **must** be labeled to tell us which assignment they're for. 
    *   For example, use `#reading2` if you're posting about the 2nd assigned reading.
    *   Include `#question` for a question post and `#answer` for an answer post.
*   When responding to a question, use "reply".
*   Questions must be posted by the due date to be eligible for full credit.
*   Answers can be posted up to 48 hours after the "read-by" due date.
*   Question and answer quality matters. 
*   Avoid Q/A duplications

### Homework

There will be 5 main homework assignments to complete during the semester.
Smaller, shorter mini-assignments may also be distributed from time to time.
Assignments will be submitted to Github as a new pull request.

Assignments submissions are documents consisting of interwoven segments of writing and code blocks.
It is expected that you will write in full sentences and use proper grammar and punctuation.
You will be expected to explain what you are doing with each chunk of code and to interpret the meaning of what you calculate.
The document's style and formatting will also be taken into account during grading and should follow the course's style guides for R and RMarkdown.

Students will be permitted to resubmit 1 of their assignments during the semester within a week of receiving their grade on the original assignment.
The resubmissions are eligible to receive full credit and replace the lower grade.
The updated assignment is to be submitted as a new pull request with a title that begins with the word **Resubmission**.

Students may discuss homework assignments using the `sp18-homework` Slack channel.
Take care to ensure that the final submission is in your own words.
See the academic integrity section for specifics.

### Midterm project

Students will complete a midterm project in assigned groups during the first half of the semester.
For this project, you will perform an exploratory data analysis on a dataset, focusing on "wrangling" the data so that you can produce meaningful visualizations and interpret basic trends.
More detailed information about the project will be provided in the coming weeks.

### Final project

In lieu of a traditional final exam, students will be building a portfolio containing both comprehensive notes on the major R functions used during the course and an overview of accomplishments demonstrating a student's learning and growth over the semester.
Students will also be given a couple of simulations to run, and then compare and contrast.
Templates for the format and content of the notes portion of the portfolio will be provided in the first few weeks and will be gradually built throughout the semester.
Students will then submit their portfolio about one week before the scheduled final exam.

During the scheduled final exam, I will conduct a brief 5-10 minute interview with each student based on their portfolio submission.
The interview will also contain a short exercise to complete.
More information on both the portfolio and the final interview will be provided in the coming weeks.

## Conduct {#course-conduct data-magellan-target="course-conduct"}

### Academic integrity

> Student members of the George Mason University community pledge not to cheat, plagiarize, steal, or lie in matters related to academic work.[^mason-academic-integrity-reference]

Students may discuss non-group work outside of class, however in all instances it is required that your submitted responses to assignments are written in your own words.
Do not duplicate or paraphrase another person's material or ideas and represent them as your own.
Content that comes from a resource or another student should be properly cited.

A note on sharing or reusing code found on other Github repos or on websites like *Wikipedia* or *Stack Overflow*.
I am aware that there are solution sets, sample snippets of code, etc.
that can be of use while working on your assignments, projects and exercises during the course.
It's common knowledge that researchers in both industry and academia will use search engines while writing code.
Being able to search for existing solutions so that you don't "reinvent the wheel" is a useful skill.
Therefore, unless I specify otherwise, you are permitted to use these resources as long as you provide a citation.

Exceptions to this rule are:

*   For individual assignments, you cannot reuse another student's code
*   For group assignments, you cannot reuse another group's code
*   You are not permitted to use solution sets for the two main textbooks we're using during the course

**[Any material that is taken in whole or in part from another source and not properly cited will be treated as a violation of Mason's Academic Honor Code.]{.smallcaps}**

Other violations of Mason's Honor Code will be treated similarly.
Suspected violations will be reported to the Office of Academic Integrity.
Please see the Honor Code page for details.

### Decorum/discourse

Students are expected to be civil in their classroom conduct and respectful of their fellow classmates and the instructor for the duration of the course.
Examples of expected behavior include, but are not limited to:

*   Showing up to class on time
*   Not interrupting your classmates or the instructor
*   Silencing your cell phone
*   Refraining from texting/messaging
*   Refraining from using devices for anything other than coursework[^devices-definition-footnote]
*   Removing ear-buds/headphones and sunglasses when class begins

The expectations of civil and respectful behavior still apply for all online discussions Students are expected to follow proper grammar and punctuation in online posts and to refrain from using internet slang, abbreviations, and sarcasm.

I will address violations of classroom decorum on a case-by-case basis and reserve the right to enact grade-based penalties for highly disruptive or repeat violations.
Penalties for decorum violations cannot be negotiated or appealed.

### Mason diversity statement

George Mason University promotes a living and learning environment for outstanding growth and productivity among its students, faculty and staff.
An emphasis upon diversity and inclusion throughout the campus community is essential to achieve these goals.
Diversity is broadly defined to include such characteristics as, but not limited to, race, ethnicity, gender, religion, age, disability, and sexual orientation.
Diversity also entails different viewpoints, philosophies, and perspectives.
Attention to these aspects of diversity will help promote a culture of inclusion and belonging, and an environment where diverse opinions, backgrounds and practices have the opportunity to be voiced, heard and respected.

## Support services

The Math Tutoring Center is in 344 Johnson Center; [http://math.gmu.edu/tutor-center.php](http://math.gmu.edu/tutor-center.php).
The Math Department also maintains a list of persons that have identified themselves as math tutors: [http://math.gmu.edu/tutor-list.php](http://math.gmu.edu/tutor-list.php)

Mason's Writing Center is in A114 Robinson Hall; (703) 993-1200; [http://writingcenter.gmu.edu/](http://writingcenter.gmu.edu/)

George Mason provides Counseling and Psychological Services (CAPS) for students.
Contact them at (703) 993-2380 or [http://caps.gmu.edu/](http://caps.gmu.edu/).

## Disclaimer {#course-disclaimer data-magellan-target="course-disclaimer"}

The instructor reserves the right to modify this syllabus at any time during the course to improve the learning experience and classroom environment.
These changes will either be announced during class or via Slack.
The digital version of the syllabus on the course website will be updated to reflect the changes.
The pacing of the course and the list of covered topics may also be altered in response to student progress.

The course objectives reflect what a student is expected to understand by the end of the course after putting in the necessary time and effort both inside and outside the classroom and completing all assignments.
These outcomes are not a guarantee, and students will get more out of the course the more they put into it.
Any acquired skills and knowledge can fade over time if not reviewed or practiced after the course concludes.

<!-- Footnotes -->

[^email-policy-footnote]: If there are special circumstances requiring that we communicate via email, it is your responsibility to inform me about it as soon as possible.
[^regrading-appeals-footnote]: Acceptable evidence includes in-class notes (provide date of class), a reading passage (provide full citation), or another valid source (textbooks, official publications, etc).
[^devices-definition-footnote]: The term "devices" is meant to be broad and includes classroom computers, laptops, cell phones, tablets and e-readers, smart watches, etc. Exceptions can be made in cases of family or personal emergencies, please speak to me before class.
[^mason-academic-integrity-reference]: Office for Academic Integrity. *2017-2018 Honor Code and Honor System.* Web. 27 Aug. 2017.

<!-- Implicit links -->

[r4ds-github]:       https://github.com/hadley/r4ds
[isrs-github]:       https://github.com/OpenIntroOrg/randomization-and-simulation
[r4ds-amazon]:       http://amzn.to/2aHLAQ1
[isrs-amazon]:       http://a.co/ixGTX7R
[r4ds-cc-license]:   http://creativecommons.org/licenses/by-nc-nd/3.0/us/
[isrs-cc-license]:   /doc/isrs_license.txt
[r4ds-online-ebook]: http://r4ds.had.co.nz/
[isrs-online-ebook]: /doc/Diez_Barr_%C3%87etinkaya-Rundel_IntroductoryStatisticsWithRandomizationAndSimulation.pdf

