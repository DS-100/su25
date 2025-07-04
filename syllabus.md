---
layout: page
title: Syllabus
nav_order: 2
description: >-
  Principles and Techniques of Data Science
markdown: kramdown
course:
  semester: Summer 2025
  edstem: https://edstem.org/us/courses/74189
  bcourses: ""
  comms_email: data100.support@berkeley.edu
  email: data100.instructors@berkeley.edu
---

# Syllabus

{:.no_toc}

<a name = 'about'></a>

## About Data 100

Combining data, computation, and inferential thinking, data science is redefining how people and organizations solve challenging problems and understand their world. This intermediate level class bridges between [Data 8](http://data8.org/){:target="\_blank"} and upper division computer science and statistics courses as well as methods courses in other fields. In this class, we explore key areas of data science including question formulation, data collection and cleaning, visualization, statistical inference, predictive modeling, and decision making.​ Through a strong emphasis on data centric computing, quantitative critical thinking, and exploratory data analysis, this class covers key principles and techniques of data science. These include languages for transforming, querying and analyzing data; algorithms for machine learning methods including regression, classification and clustering; principles behind creating informative data visualizations; statistical concepts of measurement error and prediction; and techniques for scalable data processing.

### Goals

- Prepare students for advanced Berkeley courses in data-management, machine learning, and statistics, by providing the necessary foundation and context.
- Enable students to start careers as data scientists by providing experience working with real-world data, tools, and techniques.
- Empower students to apply computational and inferential thinking to address real-world problems.

<a name = 'prereq'></a>

### Prerequisites

While we are working to make this class widely accessible, we currently require the following (or equivalent) prerequisites. **Prerequisites will be enforced in Data 100. It is your responsibility to know the material in the prerequisites.** The instructors do not have the authority to waive these requirements. Undergraduates should fill out the [Enrollment Exception Form](https://cdss.berkeley.edu/class-enrollment-information#prerequisites){:target="\_blank"} managed by CDSS to request an exception.

- **Foundations of Data Science**: [Data 8](http://data8.org/){:target="\_blank"} covers much of the material in Data 100 but at an introductory level. Data 8 provides basic exposure to python programming and working with tabular data as well as visualization, statistics, and machine learning.

- **Computing**: The Structure and Interpretation of Computer Programs ([CS 61A](http://cs61a.org/){:target="\_blank"}) or Computational Structures in Data Science ([Data 88C](https://c88c.org/){:target="\_blank"}). These courses provide additional background in python programming (e.g., for loops, lambdas, debugging, and complexity) that will enable Data 100 to focus more on the concepts in Data Science and less on the details of programming in python.

- **Math**: Linear Algebra (Math 54, EECS 16A, Math 56, Math 110, or Stat 89A). We will need some basic concepts like linear operators, projections, and optimization to analyze and derive new prediction algorithms. **This may be satisfied concurrently to Data 100.**

Please consult the [Resources](../resources) page for additional resources for reviewing prerequisite material.

**Textbook**: There is no official textbook for Data 100 this semester; we will provide course notes that will be released with the respective lectures.

## Course Components

Below is a high-level “typical week in the course” for {{page.course.semester}}.

| Mo                                                 | Tu                                            | We                                                 | Th                                            | Fr                                                              |
| -------------------------------------------------- | --------------------------------------------- | -------------------------------------------------- | --------------------------------------------- | --------------------------------------------------------------- |
| <span style="color:Green">Live Lecture</span>      | <span style="color:Green">Live Lecture</span> | <span style="color:Green">Live Lecture</span>      | <span style="color:Green">Live Lecture</span> |                                                                 |
| <span style="color:Blue">Discussion Section</span> |                                               | <span style="color:Blue">Discussion Section</span> |                                               |                                                                 | 
| |<span style="color:#c91d1d">Next Homework or Project Released and Previous Homework or Project Due</span>|                                                    |                                               | <span style="color:#c91d1d">Next Homework or Project Released and Previous Homework or Project Due</span> |
| <span style="color:#c91d1d">Next Lab Released and Previous Lab Due</span>             |                                               |                                                    | <span style="color:#c91d1d">Next Lab Released and Previous Lab Due</span> |                                                                 |

- **All deadlines are subject to change.**
- The Office Hours schedule is on the [Calendar page](../calendar).
- Lectures, discussions, assignments, projects, and exams are scheduled on the [Home page](..).

### Lecture

Each week, there are 4 live **lectures** held Monday through Thursday, 11:00am-12:30pm, hybrid: in-person in Hearst Field Annex A1 and broadcasted live on Zoom. All session recordings, slides, activities, and examples should be uploaded to the course website within 24 hours of the lecture.

**Lecture participation**: While synchronous lecture attendance (in-person or through Zoom) is not mandatory, we expect you to "participate" in lecture by answering lecture poll questions in one of two ways: (1) synchronously during the lecture as poll questions are launched; or (2) asynchronously using a link provided after lecture.

- Lecture participation is graded using poll responses on a 0/1 basis.
  - Synchronous Participation: complete **at least one** participation poll question during the live lecture timeslot (11:00am-12:30pm, Monday through Thursday). As long as you submit a response to at least one poll question in this timeframe, you will receive synchronous attendance credit.
  - Asynchronous Participation: complete **all** participation poll questions from the link provided on the course website within one week of the corresponding lecture.
  - In both cases, participation is graded on completion, not correctness.
- See the [Policies](#policies) section for lecture participation drops.

### Discussion

Live **discussion sections** are one hour long, and held twice a week on Mondays and Wednesdays. The goal of these TA-led sessions is to work through problems, hone your skills, and flesh out your understanding as part of a team. The problems that you solve and present as part of discussion are important in understanding course material.

The lectures, assignments, and exams of this course are structured with the **expectation that all students complete the tasks in the discussion worksheet, either by attending section or on their own time.** The content covered in these sections is designed to solidify understanding of key lecture concepts and prepare students for homework assignments. It is to your benefit to actively participate in all discussions.

Each week, we will provide a conceptual review covering the topics pertinent to the discussion worksheet on a [YouTube playlist](https://youtube.com/playlist?list=PLQCcNQgUcDfo2QhEtkfq8Ln9YCcx9yhRD&si=pXZWxr2ipzA-l5NU). Slides for the content review can be found [here](https://drive.google.com/drive/folders/1bBo1Pvc6WujwKP3bALp7vOO9PbcJ3yN6?usp=sharing). We recommend watching the content review before your discussion section. Discussion sections will not include any content review; they will solely be focused on problem-solving and Q&A.

{: .important }

> This semester, we are offering two different grading schemes - graded versus ungraded discussion attendance. After the first week of the course, students will need to choose between the two grading schemes. Students who choose the Graded Discussion are assigned to a discussion slot based on their availability. Discussion attendance will be recorded starting with the second week of class.

- **Graded Discussion:** Discussion attendance will be recorded each week and account for 5% of the overall grade. Each weekly discussion will be graded on a 0/1 basis. You will only get credit for attending the discussion section that you are signed up for.
  - Online sections, if offered, are reserved for students with specific needs (e.g., DSP, etc.); these can be requested through the Pre-Semester and Discussion Selection Form.
  - All students are automatically granted 3 discussion attendance drops to use for illness, personal emergencies, or for other accommodations. These drops are designed to account for unexpected events. In other words, you should not plan to use them.
- **"No Discussion" Grading Scheme:** Instead, the 5% discussion weight will be redistributed to the assignments category of the grade. If you choose this option, you will not be assigned to a discussion section.

Students are not permitted to switch between the two grading schemes once finalized. However, if you would like to attend discussion at a later point in the semester, please reach out to us privately via Ed or [data100.instructors@berkeley.edu](mailto:{{page.course.email}}), and we may be able to accommodate you.

Please refer to [Grading Scheme](#grading-scheme) for a comprehensive grade breakdown.

### Homework and Projects

**Homeworks** are long form assignments that are designed to help students develop an in-depth understanding of both the theoretical and practical aspects of ideas presented in lecture. **Projects** synthesize multiple topics.

- All homeworks and projects must be submitted by their posted deadlines. There may be separate coding and written portals for the same assignment; please check that you are submitting the right part.
- Homeworks and projects have both public (visible) and hidden autograder tests. The public tests are mainly sanity checks. For example, a sanity check might verify that the answer you entered is a number as expected, and not a word. The hidden tests generally check for correctness, and are invisible to students while they are completing the assignment.
- The primary form of support students will have for homeworks and projects are **office hours** and **Ed**.
- Homeworks and projects must be completed individually, without the usage of any unauthorized resources (e.g., CourseHero). While large language models (LLMs) are permitted for use on homeworks and projects, students are only allowed to use LLMs in the specific manner outlined in the [Collaboration Policy](#collaboration-policy-and-academic-honesty). Inappropriate use of LLMs is considered cheating, and will be addressed as such.

### Lab

**Labs** are shorter programming assignments designed to give students familiarity with new ideas. They are meant to be completed prior to homework.

- All lab assignments must be submitted by their posted deadlines.
- All lab autograder tests are public (visible).
- We will not have lab sections for Data 100 this semester. Rather, we'll provide extensive lab support on Ed and accompanying video walkthroughs.
- All labs are intended to take about an hour.
- Lab submissions are mandatory.
- Your two lowest lab scores will be dropped.

### Exams

There are two exams in this course:

{: .important}

> - **Computer-based midterm** on **Thursday July 17 OR Friday July 18**.<br/><br/>
>   One of the following will be announced shortly after the midterm:
> - **Computer-based final** on **Wednesday August 13 OR Thursday August 14 OR Friday August 15**.
> - **Written two-part final** on **Wednesday August 13 AND Thursday August 14** during lecture time

We plan to administer the midterm in one of the computer-based testing facilities on campus on 7/17 and 7/18. Enrolled students will be able to sign up for a two-hour time slot to take the midterm during one of the two available days. More information will be provided shortly after the semester begins, including instructions for students with DSP accommodations.

The final exam will be administered EITHER on-paper during regular lecture time (11:30am - 1pm) on 8/13 AND 8/14 (i.e., a two-part exam), OR in one of the computer-based testing facilities (CBTF) on campus with the exam completed in ONE sitting on 8/13, 8/14, or 8/15.

You will not have a choice of final exam modality (i.e., on-paper or computerized). The instructors will choose a single exam modality for the entire class. We will announce our decision shortly after the midterm.

## Office Hours and Communication

We want to enable everyone to succeed in this course. We encourage you to discuss course content with your friends, classmates, and course staff throughout the semester, particularly during **office hours**.

- All office hours will be updated on the Calendar.
- In-person course staff office hours will be held in Warren Hall 101B.
- In general, students can come to staff office hours for any questions on course assignments or material.
- Instructor office hours are generally reserved for conceptual questions, course review, course logistics, research opportunities, and career planning.

Course Communication:

- **EdStem**, or **Ed** for short, is our course forum this semester. **_All course announcements will be through Ed._** We are not using bCourses this semester. Please check out [Ed](https://edstem.org/us/courses/80038){:target="\_blank"} and the [FAQ](https://ds100.org/faqs/su25/){:target="\_blank"} page first before emailing course staff directly.

  - Ed is a formal, academic space. We must demonstrate appropriate respect, consideration, and compassion for others. Please be friendly and thoughtful; our community draws from a wide spectrum of valuable experiences. For further reading, please reference [Berkeley’s Principles of Community](https://diversity.berkeley.edu/principles-community){:target="\_blank"} and the [Berkeley Campus Code of Student Conduct](https://conduct.berkeley.edu/code-of-conduct/){:target="\_blank"}.

  - Ed is your primary platform for asking questions about the class. It is monitored daily by course staff, so questions posted to Ed will likely receive the fastest response.

- For sensitive questions: our course staff email is [data100.instructors@berkeley.edu](mailto:{{page.course.email}}). This email is monitored by the instructors and a few lead TAs.
- For course accommodations/DSP: student accommodation requests will be handled via the [Additional Accommodations Form](https://docs.google.com/forms/d/e/1FAIpQLSeTMG5z-WeVyRH52sQzB0bVzUk2zCzkXAaq9xJNoYHRLUw56g/viewform). Our staff email for student support and DSP accommodations is [data100.support@berkeley.edu](<(mailto:{{page.course.comms_email}})>).
  - Please only contact the course instructors directly for matters that require strict privacy and their personal attention.

## Policies

### Grading Scheme

| Category              | Data 100 | Data 100 (no discussion) | Details              |
| --------------------- | -------- | ------------------------ | -------------------- |
| Homeworks             | 25%      | 30%                      | No drop              |
| Projects              | 10%      | 10%                      | No drop              |
| Labs                  | 5%       | 5%                       | Drop 2 lowest scores |
| Discussions           | 5%       | -                        | Drop 3 lowest scores |
| Lecture Participation | 5%       | 5%                       | Drop 3 lowest scores |
| Midterm Exam          | 20%      | 20%                      |                      |
| Final Exam            | 30%      | 30%                      |                      |

**To pass this course, students must achieve a total weighted average percentage of at least 50% across the midterm and final exams.** This means that even if a student excels in other components of the course, a total weighted average below 50% on these exams will result in a failing grade for the course.

While we do not have homework drops this semester, we will offer slip days for homeworks/projects, as well as an [Additional Accommodations Form](https://docs.google.com/forms/d/e/1FAIpQLSeTMG5z-WeVyRH52sQzB0bVzUk2zCzkXAaq9xJNoYHRLUw56g/viewform). See the next sections for more details.

### On-Time Submission

All assignments are due at **_11:59 PM Pacific Time_** on the due date specified on the [Home / Schedule](..) page. The date and time of this deadline are firm. Submitting even a minute past is considered late.

### Slip Days

Each student gets an extension budget of 12 total slip days for homeworks and projects (so use them wisely). You can apply these slip days to homework and projects only (not labs) during the semester.

Each project or homework can have a maximum of **4** slip days applied. After 4 days of the assignment due date, we will be not able to accept your submission unless you have additional accommodations. Slip days should be reserved for unforeseen circumstances. You should not plan to use your slip days regularly.

{: .note }

Slip days are automatically applied based on the additional hours you take to submit any assignment after its given deadline. We will use your recorded submission time. For example, if all 12 slip days are used for the first three homework assignments, you are out of slip days and cannot ask us to not consider one of the slip days previously used. Slip days are rounded up to the next day. For instance, 1 minute late counts as 1 day late.

### Additional Accommodations

We recognize that our students come from varied backgrounds and have widely-varying experiences. If you require any additional accommodations any time in the semester, please do not hesitate to let us know. The sooner we are made aware, the more options we have available for us to help you.

The **[Additional Accommodations Form](https://docs.google.com/forms/d/e/1FAIpQLSeTMG5z-WeVyRH52sQzB0bVzUk2zCzkXAaq9xJNoYHRLUw56g/viewform)** is for any circumstances that cannot be resolved via slip days and drops. Within two business days of filling out the form, a member of course staff will reach out to you and provide a space for conversation, as well as to arrange course/grading accommodations as necessary. For more information, please email [data100.support@berkeley.edu](mailto:data100.support@berkeley.edu).

We recognize that at times, it can be difficult to manage your course performance - particularly at Berkeley’s high standards. Sometimes emergencies just come up (personal health emergency, family emergency, etc.). The Additional Accommodations Form is meant to lower the barrier to reaching out to us, as well as build your independence in managing your academic career long-term. So please do not hesitate to reach out.

Note that you **cannot** use the Additional Accommodations Form if you encounter a logistical oversight, such as Datahub/autograder tests not passing, submitting only one portion of the homework, forgetting to save your notebook before exporting, submitting to the wrong assignment portal, or not properly tagging pages on the grading portal. It is the students’ responsibility to identify and resolve these issues well in advance of the on-time deadline.
We will not grant accommodations for these cases; instead, please use slip days to cushion these submission errors.

Finally, simply submitting a request does not guarantee you will receive an extension. You must submit your requests before running out of slip days. **Even if your work is incomplete, please submit before the deadline so you can receive credit for the work you did complete.**

### DSP Accommodations

{: .important }

If you are registered with the Disabled Students’ Program (DSP) you can expect to receive an email from us during the first week of classes. Otherwise, email [data100.support@berkeley.edu](mailto:data100.support@berkeley.edu). DSP students who receive approved extension accommodations will have an automatic 2-day extension on labs, homeworks, and projects. Please note that any extension, plus the slip days combined, cannot exceed **7 days**. Beyond 7 days, you are required to meet with a TA. DSP students can use the Additional Accommodations Form to request extension accommodations beyond the provided 2-days.

You are responsible for reasonable communication with course staff. If you make a request close to the deadline, we can not guarantee that you will receive a response before the deadline. Additionally, simply submitting a request does not guarantee you will receive an extension. **Even if your work is incomplete, please submit before the deadline so you can receive work for the work you did complete.**

### Regrade Requests

Students will be allowed to submit regrade requests for the autograded and written portions of assignments in cases in which the rubric was incorrectly applied or the autograder scored their submission incorrectly. Regrades for the written portions of assignments will be handled through the grading portal, and autograder regrades via a [Google Form](https://forms.gle/LAK5rWCPdoWARujR8). The deadline for regrade requests (autograded and written) is one week after the grades are released for the corresponding assignment.

**Always check that the autograder executes correctly!** The grading portal will show you the output of the public tests, and you should see the same results as you did on DataHub. If you see a discrepancy, ensure that you have exported the assignment correctly and, if there is still an issue, post on Ed _as soon as possible_.

Regrade requests will **not** be considered in cases in which:

- A student uploads the incorrect file to the autograder.
- The autograder fails to execute and the student does not notify the course staff _before the regrade request window closes_.
- A student fails to save their notebook before exporting and uploads an old version to the autograder.
- A situation arises in which the course staff cannot ensure that the student’s work was done before the assignment deadline.

### Collaboration Policy and Academic Honesty

We will be following the [EECS departmental policy on Academic Misconduct](https://eecs.berkeley.edu/resources/students/academic-misconduct/){:target="\_blank"}, which states that using work or resources that are not your own or not permitted by the course may lead to disciplinary actions, including a failing grade in the course.

**Assignments:** Data science is a collaborative activity. While you may talk with others about the homework and projects, we ask that you write your solutions individually in your own words. **If you do discuss the assignments with others please include their names at the top of your notebook.** Restated, you and your friends are encouraged to discuss course content and approaches to problem-solving, but you are not allowed to share your code nor answers with other students, nor are you allowed to post your assignment solutions publicly. Doing so is considered academic misconduct. We will be running advanced plagiarism detection programs on all assignments. **If you are unsure whether you are plagiarizing, contact the course staff.**

Not only does such copying count as academic misconduct, but it also circumvents the pedagogical goals of an assignment. You must solve problems with the resources made available in the course. You should never look at or have solutions in your possession from another student or another semester.

While instances of suspected plagiarism are documented during the grading process, the instructors do not address suspected plagiarism until the end of the semester. In other words, if you plagiarize an assignment, but the course staff does not contact you about suspected plagiarism shortly after your grade on the assignment is released, you are not "in the clear".

Working through challenging problems is a key step in learning. If you have an artificial intelligence (AI) system doing all the hard work for you, you won’t learn. Therefore, we have the following AI policy:

{: .important }

**Use of AI-assisted methods and large language models (LLMs), such as ChatGPT, to generate written or code solutions to assignments is prohibited. Usage of past assignment solutions is also prohibited. LLMs are only permitted for productive uses, which we define below.**

Copying or closely paraphrasing any text directly from a homework or lab problem into a large language model (LLM) is considered cheating in Data 100. Furthermore, engaging in this behavior is detrimental to your learning. You should break problems into steps and ask for help with each step in your own words. If you copy problems directly into ChatGPT, **you're not learning data science**. You're learning how to ask someone else to do sloppy and unreliable data science on your behalf.

However, we also know that AI assistants will be a key part of your future, and we want to encourage you to learn how to productively use these technologies as part of the learning process. Therefore, we encourage you to try using these technologies in appropriate ways. Here are some example prompts that might help you learn:

- “What does this error message mean? _\<error message\>_ What could I do to fix it?”
- “Pandas is confusing me; what does the following pandas expression do? _\<weird expression\>_”
- “How would I convert columns into separate rows in my dataframe?”
- “Can you explain why the regular expression r’[a-z]’ only matches one character? Can you give me a few practice regular expression exercises?”

When a grader identifies a suspected inappropriate use of an LLM, it is documented for later review. Instructors do not address these cases until the end of the semester. In other words, if you inappropriately use an LLM, but the course staff does not contact you about your LLM use shortly after your grade on the assignment is released, you are not "in the clear". **If you are unsure whether your use of LLMs is appropriate, contact the course staff.**

**Exams:** Cheating on exams is a serious offense. We have methods of detecting cheating on exams – so don’t do it! Students caught cheating on any exam will fail the course.

Plagiarism or inappropriate use of LLMs on any assignment, as well as other violations to Berkeley’s [Code of Conduct](https://sa.berkeley.edu/code-of-conduct){:target="\_blank"}, will be reported to the Center for Student Conduct. The CSC treats most first-time offenses as a [Non-Reportable Warning](https://conduct.berkeley.edu/wp-content/uploads/2024/01/Academic-Misconduct-Resource-Sheet-for-Students-UPDATED.pdf){:target="\_blank"}. Additionally we reserve the right to give you a negative full score (-100%) or lower on the assignments in question, an F in the course, or even dismissal from the university. It’s just not worth it!

Rather than copying someone else’s work, ask for help. You are not alone in Data 100! The entire staff is here to help you succeed. We expect that you will work with integrity and with respect for other members of the class, just as the course staff will work with integrity and respect for you.

Finally, know that it’s normal to struggle. Berkeley has high standards, which is one of the reasons its degrees are valued. Everyone struggles, even though many try not to show it. Even if you don’t learn everything that’s being covered, you’ll be able to build on what you do learn, whereas if you cheat you’ll have nothing to build on. You aren’t expected to be perfect; it’s ok not to get an A.

## Course Culture

Students taking Data C100 come from a wide range of backgrounds. We hope to foster an inclusive and safe learning environment based on curiosity rather than competition. All members of the course community — the instructors, students, and course staff — are expected to treat each other with courtesy and respect. Some of the responsibility for that lies with the staff, but a lot of it ultimately rests with you, the students.

### Be Aware of Your Actions

Sometimes, the little things add up to creating an unwelcoming culture to some students. For example, you and a friend may think you are sharing a private joke about other races, majors, genders, abilities, cultures, etc. but this can have adverse effects on classmates who overhear it. There is a great deal of research on something called “stereotype threat”: research finds that simply reminding someone that they belong to a particular culture or share a particular identity (on whatever dimension) can interfere with their course performance.

Stereotype threat works both ways: you can assume that a student will struggle based on who they appear to be, or you can assume that a student is doing great based on who they appear to be. Both are potentially harmful.

Bear in mind that diversity has many facets, some of which are not visible. Your classmates may have medical conditions (physical or mental), personal situations (financial, family, etc.), or interests that aren’t common to most students in the course. Another aspect of professionalism is avoiding comments that (likely unintentionally) put down colleagues for situations they cannot control. Bragging in open space that an assignment is easy or “crazy,” for example, can send subtle cues that discourage classmates who are dealing with issues that you can’t see. Please take care, so we can create a class in which all students feel supported and respected.

### Be Respectful

Beyond the slips that many of us make unintentionally are a host of behaviors that the course staff, department, and university do not tolerate. These are generally classified under the term harassment; sexual harassment is a specific form that is governed by federal laws known as Title IX.

{: .note }

> UC Berkeley’s [**Title IX website**](https://ophd.berkeley.edu/){:target="\_blank"} provides many resources for understanding the terms, procedures, and policies around harassment. Make sure you are aware enough of these issues to avoid crossing a line in your interactions with other students. For example, repeatedly asking another student out on a date after they have said no can cross this line.

Your reaction to this topic might be to laugh it off, or to make or think snide remarks about “political correctness” or jokes about consent or other things. You might think people just need to grow a thicker skin or learn to take a joke. This isn’t your decision to make. Research shows the consequences (emotional as well as physical) on people who experience harassment. When your behavior forces another student to focus on something other than their education, you have crossed a line. You have no right to take someone else’s education away from them.

### Communicate Issues with Course Staff and/or the Department

**We take all complaints about unprofessional or discriminatory behavior seriously.** Professionalism and respect for diversity are not just matters between students; they also apply to how the course staff treat the students. The staff of this course will treat you in a way that respects our differences. However, despite our best efforts, we might slip up, hopefully inadvertently. If you are concerned about classroom environment issues created by the staff or overall class dynamic, please feel free to talk to us about it. The instructors in particular welcome any comments or concerns regarding conduct of the course and the staff.

### Device Lending options

Students can access device lending options through the Student Technology Equity Program [STEP program](https://studenttech.berkeley.edu/devicelending){:target="\_blank"}.

### Data Science Student Climate

[Data Science Undergraduate Studies](https://cdss.berkeley.edu/dsus){:target="\_blank"} faculty and staff are committed to creating a community where every person feels [respected, included, and supported](https://data.berkeley.edu/equity-inclusion){:target="\_blank"}. We recognize that incidents may happen, sometimes unintentionally, that run counter to this goal. There are many things we can do to try to improve the climate for students, but we need to understand where the challenges lie. If you experience a remark, or disrespectful treatment, or if you feel you are being ignored, excluded or marginalized in a course or program-related activity, please speak up. Consider talking to your instructor, but you are also welcome to contact Executive Director Christina Teller at [cpteller@berkeley.edu](mailto:cpteller@berkeley.edu) or report an incident anonymously through this [online form](https://docs.google.com/forms/d/e/1FAIpQLSfBwaUe7VMQz6VzkYFvf4KYwNSTve9iJlBSQyAmsXoSE0LnWw/viewform){:target="\_blank"}.

### Community Standards

Ed is a formal, academic space. Posts in this forum must relate to the course and be in alignment with [Berkeley’s Principles of Community](https://diversity.berkeley.edu/principles-community){:target="\_blank"} and the [Berkeley Campus Code of Student Conduct](https://conduct.berkeley.edu/code-of-conduct/){:target="\_blank"}. We expect all posts to demonstrate appropriate respect, consideration, and compassion for others. Please be friendly and thoughtful; our community draws from a wide spectrum of valuable experiences. Posts that violate these standards will be removed.

As course staff, we are committed to creating a learning environment welcoming of all students that supports a diversity of thoughts, perspectives and experiences and respects your identities and backgrounds (including race, ethnicity, nationality, gender identity, socioeconomic class, sexual orientation, language, religion, ability, and more.) To help accomplish this:

- If your name and/or pronouns differ from those that appear in your official records, please let us know.
- If you feel like your performance in the class is being affected by your experiences outside of class (e.g., family matters, current events), please don’t hesitate to come and talk with us. We want to be resources for you.
- We (like many people) are still in the process of learning about diverse perspectives and identities. If something was said in class (by anyone) that made you feel uncomfortable, please talk to us about it.
- While the course staff understands that improving diversity, equity, and inclusion (DEI) are not enough to overcome systemic issues in academia such as racism, queerphobia, and other forms of discrimination and hatred, we also recognize the importance of DEI work.
  - The Data Science Department has some resources available at [https://data.berkeley.edu/about/diversity-equity-and-inclusion](https://data.berkeley.edu/about/diversity-equity-and-inclusion){:target="\_blank"}.
  - There’s also a great set of resources available at [https://eecs.berkeley.edu/resources/students/grievances](https://eecs.berkeley.edu/resources/students/grievances){:target="\_blank"}.
- If there are other resources you think we should list here, let us know!

## Academic and Wellness Resources

Our [Resources](../resources) page lists not only course-specific academic resources such as course notes, past exams, study guides, and prerequisite review links, but also campus wellness resources on COVID-19, academic support, technology support, mental well-being, DSP accommodations, dispute resolution, social services, campus community, and basic needs. Our staff will also refer to this page when supporting you through this course.

## We want you to succeed!

If you are feeling overwhelmed, visit our office hours and talk with us, or fill out the Additional Accommodations Form. We know college can be stressful and we want to help you succeed.

{: .important }
We are committed to being a resource to you, but it is important to note that all members of the teaching staff for this course are [responsible employees](https://svsh.berkeley.edu/responsible-employee){:target="\_blank"}, meaning that **we must disclose any incidents of sexual harassment or violence to campus authorities**. If you would like to speak to a confidential advocate, please consider reaching out to the [Berkeley PATH to Care Center](https://care.berkeley.edu/){:target="\_blank"}.

Finally, the main goal of this course is that you should learn and have a fantastic experience doing so. Please keep that goal in mind throughout the semester. Welcome to Data 100!

## Acknowledgments

Academic Honesty policy and closing words adapted from [Data 8](https://data8.org/){:target="\_blank"}. Course Culture inspired and adapted with permission from Dr. Sarah Chasins’ [Fall 2021 CS 164 Syllabus](https://inst.eecs.berkeley.edu/~cs164/fa21/syllabus.html){:target="\_blank"} and Grace O’Connell, the Asssociate Dean for Inclusive Excellence.
