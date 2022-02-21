---
title: Syllabus
toc: true
---

<div class="meeting-time">

<div class="meeting-specifics">

Below are the meeting times for our class

-   **Term:** Spring 2022
-   **Time:** Monday, 1:00-3:50
-   **Classroom:** Lokey Education, 115
-   **Instructor:** Daniel Anderson, PhD
    -   *email:* (preferred contact method) <daniela@uoregon.edu>
    -   *office hours*: By appointment
    -   *pronouns:* he/him/his

</div>

<div class="logo">

<img src = "../edld653-logo.png" height = 200px>

</div>

</div>

## Course Overview

This is the third course in the *educational data science* specialization.
This course builds upon the content covered in the first two courses, with a
specific focus on becoming a better programmer and improving workflows.
Students will continue to work with the [tidyverse](https://www.tidyverse.org)
suite of packages in [R](https://cran.r-project.org), with a emphasis on
[{purrr}](https://purrr.tidyverse.org) for functional programming. At its core,
functional programming is a technique to iterate a function over a vector, or
set of vectors, to complete repetitive tasks. We will compare and contrast
{purrr} functions with base R approaches, including
`for` loops and the `apply` family of functions. Functional programming helps
reduce redundancies in code, making it more efficient, less error-prone and,
often, more readable. The course will also cover writing custom functions,
which can also help in completing repetitive tasks, but can also extend the
functionality of R, and is a key component of functional programming. The
course concludes with a brief introduction to
[shiny](https://shiny.rstudio.com/) for building interactive applications which,
although somewhat outside of the scope of functional programming, requires
using (and often writing) functions.

## Student Learning objectives

By the end of this course, students should be able to:

-   Understand and be able to describe the differences in R’s data structures
    (including the four main vector types, data frames, and lists) and when each
    is most appropriate for a given task
-   Explore `purrr::map` and its variants, how they relate to base R functions,
    and why the {purrr} variants are often preferable.
-   Work with lists and list columns using `purrr::nest` and `purrr:unnest`
-   Convert repetitive tasks into functions
-   Understand elements of good functions, and things to avoid
-   Write effective and clear functions to continue with the mantra of
    “Don’t Repeat Yourself”

# Course Reading List And Other Resources

All course readings are freely available online or will be provided by the
instructor.

## Course Readings

We will have select chapters from a number of different books. These chapters
are all freely available online. We will have chapters from each of the following books:

{{< course-books >}}

Each of the above links to either the full book, if it is online, or a link to purchase the full book if you so choose. The “other” listed above will include additional readings for topics not covered by the books. See the [schedule](../schedule) page for details on specific readings.

## Assignments and Grading

Your final grade will be composed of five components:

-   3 labs at 10 points each (30 points; 15%)
-   Midterm Quiz: 10 points (5%)
-   Midterm take-home: 60 points (30%)
-   Final Project: 100 points (50%)

I would like to, as much a possible, stick to the deadlines for all assignments as listed in the [schedule](../schedule) page. This will allow us to go over the material together as a group *after* everyone has submitted their assignment. However, **if you need additional time for any reason** please just send me a note letting me know. You do not need to justify why. This is a very weird time we’re living in and I am more than happy to work with you however I can. I would just ask that you please **not** attend class during the time we are going over the assignment (but please do attend the rest of the class if you are able).

### Labs (30 points; 15%)

There are 3 labs during the course, scored at 10 points each. All labs will be scored on a “best
honest effort” basis, which generally implies zero or full credit (i.e., the
assignment was or was not fully completed). However, labs may require
students complete specific portions before moving on to the next sections. If
you find yourself stuck and unable to proceed, **please contact the instructor
for help rather than submitting incomplete work**. Contacting the instructor
is part of the “best honest effort,” and can result in full credit for an
assignment even if the the work is not fully complete. **If the assignment is
not complete, and the student has not contacted the instructor for help or
visited office hours, it is likely to result is a partial credit score or a
zero**.

### Midterm Quiz (10 points; 5%)

A quiz will be assigned on canvas to assess your knowledge on content covered during the first half of the term. This will be short, including a maximum of 10 questions, and will be scheduled to occur in-class. The quiz will be timed (20 minutes), which should be more than sufficient time if you do not have to search for the content.

### Midterm take-home (60 points; 30%)

The take-home midterm is just a standard homework assignment that happens to come in the middle of the quarter. Unlike labs, responses will be scored on a correct/incorrect basis. You are free to work in small groups, with the added condition that all work be completed and submitted through a collaborative GitHub repository.

### Final Project (100 points; 50%)

The final project has multiple components that are due at different points throughout the term. These include

-   Outline (5 points; 2.5%)
-   Draft data preparation script (10 points; 5%)
-   Peer review (15 points; 5%)
-   Final product (70 points)
    -   No code is used repetitively (no more than twice) \[10 points\]
    -   More than one variant of `purrr::map` is used \[5 points\]
    -   At least one {purrr} function outside the basic `map` family (`walk_*`,
        `reduce`, `modify_*`, etc.) \[5 points\]
    -   At least one instance of parallel iteration (e.g., `map2_*`, `pmap_*`) \[5 points\]
    -   At least one use case of `purrr::nest %>% mutate()` \[5 points\]
    -   At least two custom functions \[20 points; 10 points each\]
    -   Each function must do exactly one thing
    -   The functions **may** replicate the behavior of a base function - as noted
        above this is about practicing the skills you learn in class
    -   Code is fully reproducible and housed on GitHub \[10 points\]
    -   No obvious errors in chosen output format \[5 points\]
    -   Deployed on the web and shareable through a link \[5 points\]

Please see the [assignments](../assignments) page for full details on the final
project.

## Grading Components (200 points possible)

{{< bootstrap-table "table table-hover" >}}

| **Lower percent** | **Lower point range** | **Grade** | **Upper point range** | **Upper percent** |
|:-----------------:|:----------------------|:---------:|:---------------------:|------------------:|
|      0.970+       | (194 pts or more)     |    A+     |                       |                   |
|       0.930       | (186 pts)             |     A     |       (193 pts)       |             0.969 |
|       0.900       | (180 pts)             |    A-     |       (185 pts)       |             0.929 |
|       0.870       | (174 pts)             |    B+     |       (179 pts)       |             0.899 |
|       0.830       | (166 pts)             |     B     |       (173 pts)       |             0.869 |
|       0.800       | (160 pts)             |    B-     |       (165 pts)       |             0.829 |
|       0.770       | (154 pts)             |    C+     |       (159 pts)       |             0.799 |
|       0.730       | (146 pts)             |     C     |       (153 pts)       |             0.769 |
|       0.700       | (140 pts)             |    C-     |       (145 pts)       |             0.739 |
|                   |                       |     F     |   (139 pts or less)   |             0.699 |

{{< /bootstrap-table >}}

## Student Engagement Inventory

Graduate: 1 credit hour = 40 hours of student engagement (3 credit hours = 120 hours of student engagement)

{{< bootstrap-table "table table-hover" >}}

| **Educational activity** | **Hours student engaged** | **Explanatory comments (if any):**                                                                               |
|:-------------------------|:-------------------------:|:-----------------------------------------------------------------------------------------------------------------|
| Course attendance        |           28.3            | 10 meetings, at 170 minutes per meeting                                                                          |
| Assigned readings        |           28.7            | Weekly readings are assigned, and are expected to take roughly as long to complete as the in-seat time per week. |
| Labs                     |            10             | 3 labs assignments, at approximately 3.3 hours each outside of class                                             |
| Take-home midterm        |            20             |                                                                                                                  |
| Final Project            |            33             | Securing data (\~2 hours); Peer review (5 hours); analysis/processing (25 hours); deployment (1 hour)            |
| Total hours:             |            120            |                                                                                                                  |

{{< /bootstrap-table >}}

## Campus Emergency

In the event of a campus emergency that disrupts academic activities, course requirements, deadlines, and grading percentages are subject to change. Information about changes in this course will be communicated as soon as possible by email, and on Canvas. If we are not able to meet face-to-face, students should immediately log onto Canvas and read any announcements and/or access alternative assignments. Students are also encouraged to continue the readings and other assignments as outlined on this syllabus or subsequent syllabi.

## Fluidity, Attendance, Participation

As the university community adjusts to teaching and learning remotely in the context of the COVID-19 pandemic, course requirements, deadlines, and grading percentages are subject to change. We will be mindful of the many impacts the unfolding events related to COVID-19 may be having on you. During this challenging time, we encourage you to talk with me about what you are experiencing so we can work together to help you succeed in this course.

## Expected Engagement

**Participate and Contribute:** Students are expected to participate by sharing ideas and contributing to the collective learning environment. This entails preparing, following instructions, and engaging respectfully and thoughtfully with others. More specific participation guidelines and criteria for contributions will be provided for each specific activity.

**Please use good “online etiquette”:** Identify yourself with your real name and use a subject line that clearly relates to your contribution. Write or speak in the first person when sharing your opinions and ideas but when addressing other students or discussing their ideas, use their names. Respect the privacy of your classmates and what they share in class. Understand that we may disagree and that exposure to other people’s opinions is part of the learning experience. Good online etiquette also means using humor or sarcasm carefully, remembering that non-verbal cues (such as facial expressions) are not always possible or clear in a remote context. In addition, your language should be free of profanity, appropriate for an academic context, and exhibit interest in and courtesy for others’ contributions. Be aware that typing in all capital letters indicates shouting. Certain breaches of online etiquette can be considered disruptive behavior.

**Expect and Respect Diversity:** All classes at the University of Oregon welcome and respect diverse experiences, perspectives, and approaches. What is not welcome are behaviors or contributions that undermine, demean, or marginalize others based on race, ethnicity, gender, sex, age, sexual orientation, religion, ability, or socioeconomic status. We will value differences and communicate disagreements with respect.

**Help Everyone Learn:** Our goal is to learn together by learning from one another. As we move forward learning during this challenging time, it is important that we work together and build on our strengths. Not everyone is savvy in remote learning, including your instructor, and this means we need to be patient with each other, identify ways we can assist others, and be open-minded to receiving help and advice from others. No one should hesitate to contact me to ask for assistance or offer suggestions that might help us learn better.

**Specific guidelines for best practices using Canvas Discussion:**

1.  Use subject lines that clearly communicate the content of your post
2.  Write clearly and concisely and be aware that humor or sarcasm often doesn’t always translate in an online environment.
3.  Be supportive and considerate when replying to others’ posts. This means avoiding use of jargon or inappropriate language, and it means disagreeing with respect and providing clear rationale or evidence to support your different view.
4.  Try to use correct spelling and grammar and proofread your submissions. After submitting, use the edit feature to make corrections and resubmit (don’t create a new or duplicate post that corrects your error).
5.  Contribute and interact often!

**Specific guidelines for best practices using Zoom:**

1.  Please test your video and audio prior to joining a live class session. You can learn more about testing your audio and video by visiting the UO Service Portal.
2.  Try to be on time when the class starts. It can be distracting to have participants join late.
3.  Use a microphone or speak closely to your computer microphone so that others can hear you.  
4.  Mute your audio when you are not actively contributing. When contributing, avoid making other noises such as typing or having side conversations with others that might be present with you.
5.  Use chat to pose questions or offer insights “on the side” while others are contributing. The chat can be read by all and should reflect a high standard of respect for our class community.
6.  For help and troubleshooting with Zoom, visit the UO Service Portal.

## Course Policies

### Attendance and Absence Guidelines

Attendance at all class and discussion groups is expected and required. Students must contact the instructor in case of illness or emergencies that preclude attending class sessions. Messages can be left on the instructor’s e-mail at any time of the day or night, prior to class. If no prior arrangements have been made before class time, the absence will be unexcused. If you are unable to complete an assignment due to a personal and/or family emergency, you should contact your instructor as soon as possible. On a case-by-case basis, the instructor will determine whether the emergency qualifies as an excused absence.

### Absence Policy

There may be situations beyond the control individual students that lead to excessive absences such as becoming ill, caring for others, managing home schooling, etc. Students are expected to attend class, however if a student misses more than two consecutive classes they will be asked to complete a make-up assignment to be developed by the instructor to compensate for the missed class time. Each student who is experiencing difficulty attending scheduled class times or class activities must contact the instructor to develop a plan for making up the class time and satisfactorily meeting the credit hours required.

### UO COVID-19 Regulations

The University of Oregon (UO), in accordance with guidance from the Centers for Disease Control, Oregon Health Authority, and Lane County Public Health requires faculty, staff, students, visitors, and vendors across all UO locations to use face coverings, which include masks (note: masks with exhaust valves are discouraged), cloth face coverings, or face shields, when in UO owned, leased, or controlled buildings. This includes classrooms. Please correctly wear a suitable face covering during class. Students unable to wear face coverings can work with the Accessible Education Center to find a reasonable accommodation. Students refusing to wear a face covering will be asked to leave the class.
Students should maintain 6 ft. distance from others at all times. Classrooms tables and seats have been marked to accommodate this distance. Please do not move any furniture in the classroom or sit in areas that have been blocked off or otherwise marked as unavailable.
Students should obtain wipes available outside of classrooms before they enter class and use them to wipe down the table and seat they will use. See https://coronavirus.uoregon.edu/regulations for more information.

### Diversity, Equity and Inclusion

It is the policy of the University of Oregon to support and value equity and diversity and to provide inclusive learning environments for all students. To do so requires that we:

-   respect the dignity and essential worth of all individuals.
-   promote a culture of respect throughout the University community.
-   respect the privacy, property, and freedom of others.
-   reject bigotry, discrimination, violence, or intimidation of any kind.
-   practice personal and academic integrity and expect it from others.
-   promote the diversity of opinions, ideas and backgrounds which is the lifeblood of the university.

In this course, class discussions, projects/activities and assignments will challenge students to think critically about and be sensitive to the influence, and intersections, of race, ethnicity, nationality, documentation status, language, religion, gender, socioeconomic background, physical and cognitive ability, sexual orientation, and other cultural identities and experiences. Students will be encouraged to develop or expand their respect and understanding of such differences.

Maintaining an inclusive classroom environment where all students feel able to talk about their cultural identities and experiences, ideas, beliefs, and values will not only be my responsibility, but the responsibility of each class member as well. Behavior that disregards or diminishes another student will not be permitted for any reason. This means that no racist, ableist, transphobic, xenophobic, chauvinistic or otherwise derogatory comments will be allowed. It also means that students must pay attention and listen respectfully to each other’s comments.

### Indigenous Recognition Statement

The University of Oregon is located on Kalapuya Ilihi, the traditional indigenous homeland of the Kalapuya people. Today, descendants are citizens of the Confederated Tribes of the Grand Ronde Community of Oregon and the Confederated Tribes of the Siletz Indians of Oregon, and they continue to make important contributions in their communities, at UO, and across the land we now refer to as Oregon.

### Using Pronouns and Personal Preference

The College of Education is always working to include and engage everyone. One way we can do this is to share your pronouns, or the words you want to be called when people aren’t using your name. Like names, pronouns are an important part of how we identify that deserves to be respected. And we recognize that assuming someone’s gender can be hurtful, especially to members of our community who are transgender, genderqueer, or non-binary. As a community, we are all learning together about the importance of pronouns and being better allies to the trans community on campus. Please discuss the pronouns you wish to be used with your professor to help them be aware of how to address you respectfully. Please visit [this university website](https://studentlife.uoregon.edu/pronouns) for more information. You can also add [pronouns in Canvas](https://canvas.uoregon.edu/courses/161255/pages/personal-pronouns-in-canvas?module_item_id=2655408).

### Your Well-Being

Life right now is very complicated. Students often feel overwhelmed or stressed, experience anxiety or depression, struggle with relationships, or just need help navigating challenges in their life. If you’re facing such challenges, you don’t need to handle them on your own – there’s help and support on campus.

As your instructors, if we believe you may need additional support, we will express our concerns, the reasons for them, and refer you to resources that might be helpful. It is not our intention to know the details of what might be bothering you, but simply to let you know we care and that help is available. Getting help is a courageous thing to do—for yourself and those you care about.

University Health Services help students cope with difficult emotions and life stressors. If you need general resources on coping with stress or want to talk with another student who has been in the same place as you, visit the Duck Nest (located in the EMU on the ground floor) and get help from one of the specially trained Peer Wellness Advocates. Find out more at https://health.uoregon.edu/ducknest.

University Counseling Services (UCS) has a team of dedicated staff members to support you with your concerns, many of whom can provide identity-based support. All clinical services are free and confidential. Find out more at https://counseling.uoregon.edu or by calling 541-346-3227 (anytime UCS is closed, the After-Hours Support and Crisis Line is available by calling this same number).

### Food Insecurity

Any student who has difficulty affording groceries or accessing sufficient food to eat every day, or who lacks a safe and stable place to live and believes this may affect their performance in the course is urged to contact the Dean of Students Office (346-3216, 164 Oregon Hall) for support.

This UO [webpage](https://blogs.uoregon.edu/basicneeds/food/) includes resources for food, housing, healthcare, childcare, transportation, technology, finances, and legal support.

#### Feed the Flock – Services for Students Facing Food Insecurity

The following is a list of services and programs that offer free food, meals, and support for accessing resources. Their availability and operation remain fluid and subject to change without notice. We will do everything we can to ensure that we are communicating as quickly as possible. We are working to shift our resources and efforts to ensure that students facing food insecurity have multiple avenues of support. Program descriptions can be found [here](https://emu.uoregon.edu/ducks-feeding-ducks)

The Student Sustainability Center ([uo_ssc](https://www.instagram.com/uo_ssc/)) will try to aggregate changes and information for all programs via facebook and Instagram. For food security specific resources, follow [feedtheflockuo](https://www.instagram.com/feedtheflockuo/). Please follow for the most up to date information regarding program changes.

-   **ECM Student Food Pantry** – Open 4-6pm Wednesdays and Thursdays. 710 E. 17th Ave. Eugene, OR 97401. Check the Student Food Pantry facebook for updates including the possible addition of Saturday hours.

-   **Produce Drops** – Free, fresh produce for students every Tuesday of the month from 3-5pm during the academic term (ie, not during Winter Break). Produce Drops take place in the EMU amphitheater rain or shine.

-   **SNAP Enrollment help** – The Student Sustainability Center and the Duck Nest are working to ensure continuity in SNAP enrollment help. SNAP enrollment drop-in hours with the Duck Nest are posted on the Duck Nest Instagram ([uo_ducknest](https://www.instagram.com/uo_ducknest/)). The SSC also has SNAP drop-in hours which are updated on their Instagram ([feedtheflockuo](https://www.instagram.com/feedtheflockuo/)). Please follow the Duck Nest and the Student Sustainability Center on social media to stay up to date.

-   **Ducks Feeding Ducks** – Emergency meal dollars will remain available and can be used wherever Duck Bucks are accepted. To qualify, students must not have more than \$4 in their Duck Bucks account and may not have used the program already this term. Additional funds can be received upon meeting with the Dean of Students office.

-   **Hearth to Table Meals** – Free community meals and meal preparation with professional Chef. Hearth to Table will not hold meals during finals week or Winter Break. Starting week 1, kitchen teams will be reduced to 4 people. Student volunteers must sign up in advance by emailing sisterclare@welcometocentral.net. Communal meals will continue being served with increased distance between tables and only 4 seats at each table. Total number of diners will be capped at 32. Meals are served 6:30 pm to any student for free. Check Hearth & Table facebook and Instagram for updates. Check the [feedtheflockuo](https://www.instagram.com/feedtheflockuo/) Instagram for Hearth and Table updates.

#### Additional Resources via FOOD for Lane County:

-   **Free Produce and Groceries** - Call FOOD for Lane County at 541.343.2822 to find out which location best serves you. All times and dates are subject to change, please call Food for Lane County or check out their website for the most up to date information.

-   **Hot meals**

    -   The Dining Room – 270 W 8th Ave; passing out to-go meals; M-Th 12-12:45pm

    -   St. Vincent de Paul Service Station – 450 B Hwy 99 N; (18+ only); limited number of guests in the building, outdoor respite space available

    -   Ebert Memorial Methodist Church – 532 C St. Springfield; passing out to-go meals Monday 8:30-10:30am & Tuesday/Thursday 8-11:15am

    -   Eugene Catholic Worker 5th and Washington; Weds-Sat 8:30am-9:30am; Tuesday-Thursday 4:30pm-5pm

    -   Free People! – Lamb’s Cottage at Skinner’s Butte, Eugene; Saturday Breakfast 9:15-9:45am, Saturday dinner

    -   Burrito Brigade – First Christian Church; 1143 Oak Street, Eugene; Sun 11am-2pm

    -   First Christian Church – 1166 Oak Street, Eugene; Sun 7:45am-9:15am

    -   Food Not Bombs – 10 E. Broadway, Eugene; Friday 3pm

-   **Food Pantry**

    -   Daily Bread – 89780 N. Game Farm Road, Eugene; 2nd and 4th Thursday, 2-6pm. Double Up Food Bucks! – Receive up to \$10 for fruits and vegetables with SNAP at farmer’s markets when you spend \$10 on your SNAP card. Go to the token vendor, spend \$10 and get an additional \$10!

### Children in class

I applaud all of you who go to graduate school with children! I had both of my girls while a doctoral student, and I understand the difficulty in balancing academic, work, and family commitments. I want you to succeed. Here are my policies regarding children in class:

1.  All breastfeeding babies are welcome in class as often as necessary.
2.  Non-nursing babies and older children are welcome whenever alternate arrangements cannot be made. As a parent of two young children, I understand that babysitters fall through, partners have conflicting schedules, children get sick, and other issues arise that leave parents with few other options.
3.  In cases where children come to class, I invite parents/caregivers to sit close to the door so as to more easily excuse yourself to attend to your child’s needs. Non-parents in the class: please reserve seats near the door for your parenting classmates.
4.  All students are expected to join with me in creating a welcoming environment that is respectful of your classmates who bring children to class.

I understand that sleep deprivation and exhaustion are among the most difficult aspects of parenting young children. The struggle of balancing school, work, childcare, and graduate school is tiring (not to mention being in the middle of a pandemic!), and I will do my best to accommodate any such issues while maintaining the same high expectations for all students enrolled in the class. ***Please do not hesitate to contact me with any questions or concerns.***

### Accessible Education

Please let me know within the first two weeks of the term if you need assistance to fully participate in the course. Participation includes access to lectures, web-based information, in-class activities, and exams. The Accessible Education Center (http://aec.uoregon.edu/) works with students to provide an instructor notification letter that outlines accommodations and adjustments to class design that will enable better access. Contact the Accessible Education Center for assistance with access or disability-related questions or concerns.

### Reporting Obligations

We are designated reporters. For information about our reporting obligations as employees, please see Employee Reporting Obligations on the Office of Investigations and Civil Rights Compliance (OICRC) website. Students experiencing any form of prohibited discrimination or harassment, including sex or gender-based violence, may seek information and resources at http://https://safe.uoregon.edu, http://https://respect.uoregon.edu, or http://https://investigations.uoregon.edu or contact the non-confidential Title IX office/Office of Civil Rights Compliance (541-346-3123), or Dean of Students offices (541-346-3216), or call the 24-7 hotline 541-346-SAFE for help. We are also mandatory reporters of child abuse. Please find more information at Mandatory Reporting of Child Abuse and Neglect.

### Reporting Title IX Experiences

Any student who has experienced sexual assault, relationship violence, sex or gender-based bullying, stalking, and/or sexual harassment may seek resources and help at safe.uoregon.edu. To get help by phone, a student can also call either the UO’s 24-hour hotline at 541-346-7244 \[SAFE\], or the non-confidential Title IX Coordinator at 541-346-8136. From the SAFE website, students may also connect to Callisto, a confidential, third-party reporting site that is not a part of the university.

Students experiencing any other form of prohibited discrimination or harassment can find information at aaeo.uoregon.edu or contact the non-confidential AAEO office at 541-346-3123 or the Dean of Students Office at 541-346-3216 for help. As UO policy has different reporting requirements based on the nature of the reported harassment or discrimination, additional information about reporting requirements for discrimination or harassment unrelated to sexual assault, relationship violence, sex or gender based bullying, stalking, and/or sexual harassment is available at http://aaeo.uoregon.edu/content/discrimination-harassment

Specific details about confidentiality of information and reporting obligations of employees can be found at https://titleix.uoregon.edu.

### Academic Misconduct Policy

The University Student Conduct Code (available at conduct.uoregon.edu) defines academic misconduct. Students are prohibited from committing or attempting to commit any act that constitutes academic misconduct. By way of example, students should not give or receive (or attempt to give or receive) unauthorized help on assignments or examinations without express permission from the instructor. Students should properly acknowledge and document all sources of information (e.g. quotations, paraphrases, ideas) and use only the sources and resources authorized by the instructor. If there is any question about whether an act constitutes academic misconduct, it is the students’ obligation to clarify the question with the instructor before committing or attempting to commit the act. Additional information about a common form of academic misconduct, plagiarism, is available at https://researchguides.uoregon.edu/citing-plagiarism.

### Academic Integrity for Remote Learning

The University Student Conduct Code defines academic misconduct, which includes unauthorized help on assignments and examinations and the use of sources without acknowledgment. Academic misconduct is prohibited at UO. We will report misconduct to the Office of Student Conduct and Community Standards—consequences can include failure of the course. In our remote class, we may ask you to certify that your products are your own work. If a technological glitch disrupts your work, don’t panic. Take a photo to document the error message you’re receiving and then email us.

### Conflict Resolution

Several options, both informal and formal, are available to resolve conflicts for students who believe they have been subjected to or have witnessed bias, unfairness, or other improper treatment.
It is important to exhaust the administrative remedies available to you including discussing the conflict with the specific individual, contacting the Department Head, or within the College of Education, fall term you can contact the Associate Dean for Academic Affairs, Lillian Durán, 541-346-2502, lduran@uoregon.edu. Outside the College, you can contact:

-   UO Bias Response Team: 346-3216 http://bias.uoregon.edu/whatbrt.htm
-   Investigations and Civil Rights Compliance: 346-3123 http://aaeo.uoregon.edu/

### Grievance Policy

A student or group of students of the College of Education may appeal decisions or actions pertaining to admissions, programs, evaluation of performance and program retention and completion. Students who decide to file a grievance should follow University student [grievance procedures](https://policies.uoregon.edu/grievance-procedures) and/or consult with the College Associate Dean for Academic Affairs (Lillian Durán, 346-2502, lduran@uoregon.edu).

### In Case of Inclement Weather

In the event the University operates on a curtailed schedule or closes, UO media relations will notify the Eugene-Springfield area radio and television stations as quickly as possible. In addition, a notice regarding the university’s schedule will be posted on the UO main home page (in the “News” section) at http://www.uoregon.edu. Additional information is available at http://hr.uoregon.edu/policy/weather.html.

If an individual class must be canceled due to inclement weather, illness, or other reason, a notice will be posted on Canvas or via email. During periods of inclement weather, please check Canvas and your email rather than contact department personnel. Due to unsafe travel conditions, departmental staff may be limited and unable to handle the volume of calls from you and others.

### Course Incomplete Policy

Students are expected to be familiar with university policy regarding grades of “incomplete” and the time line for completion. For details on the policy and procedures regarding incompletes, Please see: https://education.uoregon.edu/academics/incompletes-courses
