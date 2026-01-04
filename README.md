# CMPSC 400: Operating Systems (Spring 2026)

## Boilerplate: Description, Distributions, & Objectives

### Course Description

The course description, per the academic bulletin, is as follows:

> A study of the principles used in the design, implementation, and evaluation
  of operating systems. Participating in hands-on activities that often require
  teamwork, students create and assess components of an operating system that
  runs on modern computer hardware. Leveraging insights and tools from an
  industry partner, students also investigate the resource management, process
  scheduling, and file sysems used in representative operating systems. During a
  weekly laboratory session students use advanced operating systems software to
  complete projects, reporting on their results through both written documents
  and oral presentations. Students are invited to use their own departmentally
  approved laptop in this course; a limited number of laptops are available for
  use during class and lab sessions.

### Distribution Requirements

This course fulfills two distribution requirements: **Quantitative Reasoning**
**(QR)** and **Scientific Process and Knowledge (SP)**. Again, per the academic
bulletin:

> **Quantitative Reasoning** is the ability to understand, investigate,
  communicate, and contextualize numerical, symbolic, and graphical information
  towards the exploration of natural, physical, behavioral, or social phenomena.

> Courses involving **Scientific Process and Knowledge** aim to convey an
  understanding of what is known or can be known about the natural world; apply
  scientific reasoning towards the analysis and synthesis of scientific
  information; and create scientifically literate citizens who can engage
  productively in problem solving.

### Course Learning Objectives

Students who successfully complete this course should expect to be able to:

1. Correctly describe and use the process management and CPU scheduling modules
   in an operating system.

2. Design, implement, and/or use a correct memory management module that can
   allocate and deallocate objects to a computer's memory.

3. Correctly implement and, in a step-by-step fashion, describe the behavior of
   concurrent and/or parallel computer programs.

4. Design and implement correct computer programs that use persistent storage
   modules, like block storage devices and file systems, to store varied types
   of data.

5. Create and use benchmarking tools to experimentally characterize the
   performance and correctness of operating system modules and the software
   programs that use them.

## Your Instructor: Prof Normile

### Contact

- **Email:** jnormile@allegheny.edu
- **Phone:** (814) 332-2883
- **Office:** Alden 106

### Office Hours

Given the relatively small population of our course, appointments will not be
necessary; i.e., **all office hours are walk-in only**. That means first come,
first serve.

| Day | Time          |
| :-- | ------------: |
| Mon | 4p - 5p       |
| Thu | 5p - 6p       |

### A Note on Contacting the Instructor

Unfortunately, I have obligations outside of Allegheny College (namely, a day
job with local aerospace manufacturer Acutec) that generally makes regular
communication during normal business hours difficult, if not sometimes
impossible. That having been said, I will make all efforts to reply to attempts
to communicate with me within a timely manner: generally within one 24-hour
period, excluding weekends and holidays (work-life balance is important for
*all* of us).

It's worth noting that my preferred mode of asynchronous communication is
Discord; however, I think you'll find that communicating face-to-face during
class/lab/office hours will be the most helpful!

## Textbook: *OSTEP*

No textbook purchases are required for this course. Rather, this course utilizes
content from Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau's
[*Operating Systems: Three Easy Pieces*](https://pages.cs.wisc.edu/~remzi/OSTEP/),
which is available for free in a webbook format.

## Course Overview: Learning by Teaching

> Teaching is the highest form of understanding.

The above quote is widely attributed to Aristotle, and it encapsulates an idea
that many of the teachers, professors, coaches, mentors, and trainers in your
life will likely affirm themselves. Anecdotal evidence aside, there's also some
[hard science](https://www.sciencedirect.com/science/article/abs/pii/S0361476X13000209)
that supports this notion.

Allow me to set expectations upfront: you will receive very few lectures from me
over the course of this semester. Instead, our time will be centered around
first equipping each of *you* to teach the material relevant to our course, and
then learning from each other! Given that this is a 400-level course, and each
of you are coming to this class equipped with a spread of experiences that
uniquely color your understanding of the computer and information sciences, this
will also allow us to experience a diverse spread of perspectives within the
comfort of our own classroom. It's a win-win!

To facilitate all of this, our time together will be split into three "acts", to
borrow some theater parlance.

### Act I: Research

The first few weeks of our course will focus on each of you developing specific
and targeted expertise on a particular operating systems topic through a mix of
guided and independent research. You will work in small groups dedicated to one
of four broader subjects: process management, memory management, concurrent
systems, and persistent storage, with each subject mapping back to one of our
course's first four learning objectives. Within these subjects, you'll work with
teammates to develop coding projects for the entire class, as well as
individually prepare material for a brief lecture highlighting a specific
assigned topic within that subject.
 
### Act II: Relay

We'll then transition into a period of time dedicated to each team sharing the
content they've prepared with the rest of the class. Your teams will guide your
classmates through the completion of the coding projects you'll have developed,
and each teammate will deliver the lecture they've individually prepared over
the course of a two-week period. Every two-week period will also culminate in an
expert forum where you and your teammates will respond to questions from your
classmates about the subject you've developed expertise in.

### Act III: Revisit

[Repetition is known to be an excellent mechanism for learning](https://www.pnas.org/doi/10.1073/pnas.2218042120).
We'll complete our time together by revisiting some of what we've built over the
course of the semester and apply the idea of "benchmarking" to our projects in
service of the final learning objective for the course. How exactly this
manifests will largely be of your own choosing, but prepare to quantifiably
measure the performance of what has been built so far, and investigate methods
for improving upon them.

### Course Calendar

This calendar is intended to only give you a birds-eye view of the course.
Specific deadlines and deliverables will be posted regularly to the GitHub
course organization home page as they become relevant to what we're working on.

| Week        | Meeting Days | Act          | Topic               |
| ----------- | ------------ | ------------ | ------------------- |
| 1/12 - 1/16 | M/Tu/Th      | Research     | Orientation         |
| 1/19 - 1/23 | Tu/Th        | Research     | Module Proposals    |
| 1/26 - 1/30 | M/Tu/Th      | Research     | Module Prototypes   |
| 2/2 - 2/6   | M/Tu/Th      | Relay        | Process Management  |
| 2/9 - 2/13  | M/Tu/Th      | Relay        | Process Management  |
| 2/16 - 2/20 | M/Tu/Th      | Relay        | Memory Management   |
| 2/23 - 2/27 | M/Tu/Th      | Relay        | Memory Management   |
| 3/2 - 3/6   | `null`       | Intermission | Spring Break!       |
| 3/9 - 3/13  | M/Tu/Th      | Relay        | Concurrent Systems  |
| 3/16 - 3/20 | M/Tu/Th      | Relay        | Concurrent Systems  |
| 3/23 - 3/27 | M/Tu/Th      | Relay        | Persistent Storage  |
| 3/30 - 4/3  | M/Tu/Th      | Relay        | Persistent Storage  |
| 4/6 - 4/10  | Tu           | Revisit      | Benchmarking        |
| 4/13 - 4/17 | M/Tu/Th      | Revisit      | Project Proposals   |
| 4/20 - 4/24 | M/Tu/Th      | Revisit      | Project Dev         |
| 4/27 - 5/1  | M/F (@9am)   | Revisit      | Outcome Sharing     |

## Grading: Assessing Your Learning

First and foremost, the purpose of our time together is to *learn*. We'll best
learn together by keeping up with course expectations and (of course) sharing
what we've discovered with one another. The grading strategies employed in this
class are built around those ideas.

There are exactly 100 points up for grabs over the course of the semester.
You'll begin with a score of 0, and each "act" will present a finite number of
opportunties to pump that score up. 

Furthermore, each act will contain two types of evaluation: *asynchronous* and
*synchronous*. When an activity is *asynchronous*, I mean that you're producing
some output on your own time and submitting it at your leisure before a stated
deadline. When an activity is *synchronous*, I mean you will be demonstrating
your learning in real-time through some form of presentation or oral
examination.

The breakdown of these available points is rendered below:

| Act          | Asynchronous Points | Synchronous Points | Total Points |
| ------------ | ------------------- | ------------------ | ------------ |
| I: Research  | 15                  | 5                  | 20           |
| II: Relay    | 30                  | 30                 | 60           |
| III: Revisit | 5                   | 15                 | 20           |

### Act I Available Points

The following **asynchronous** activities will be worth 5 points each during act
I:

- **Lecture Slides**: you'll be tasked with creating 5 slides that you will
  eventually use to deliver a lecture on a specific operating systems topic
  during act II. These slides will need to include at least one "infographic"
  style visual of some part of the topic.

- **Module Proposal**: you'll work with your teammates to propose a code module
  that demonstrates the learning objective associated with your group's broad
  topic, and ultimately craft a 5-point rubric that can be used to evaluate the
  module's success.

- **Module Prototype**: you'll work with your teammates to craft a completed
  working version of your proposed code, which will be evaluated against your
  proposed rubric. You'll also be expected to walk through a code review with
  the instructor as a group.

The following **synchronous** activity will be worth 5 points during act I:

- **Expertise Oral Examination**: you'll have a one-on-one conversation with the
  professor about your assigned topic, where you'll be asked to demonstrate what
  you've learned while researching that topic, and ultimately defend your
  purported expertise on the subject.

### Act II Available Points (Expert):

There will be a two-week period during act II where you will be one of the
resident experts for the topic at hand. During this time, the following
**synchronous** activities will be worth 5 points each:

- **Module Reveal**: you and your teammates will provide a 15 minute
  presentation revealing the coding module activity your team designed for the
  class. This will include a motivation for the module, relevant starting
  advice, and an explanation of the rubric you designed.

- **Lecture**: you'll be tasked with individually delivering a 20-30 minute
  lecture pertaining to your specific topic.

- **Expert Forum Leadership**: you and your teammates will lead a class-wide
  forum pertaining to the broad topic you all have researched together.

### Act II Available Points (Non-Expert):

There will be three two-week periods during act II where you will *not* be one
of the resident experts for the topic at hand. During each of these periods,
the following **asynchronous** activities will be available for 5 points each:

- **Module Completion**: you'll work with your teammates to complete the coding
  project designed by the current experts. Expect a code review with the
  instructor once the module is completed.

- **Infographic**: you'll work individually to produce a single infographic that
  captures a high-level understanding of the current topic and presents it in an
  easily digestible fashion. Expect to present it to the instructor and talk
  through what the infographic relays to the viewer.

During each of these periods, the following **synchronous** activity will be
available for 5 points:

- **Expert Forum Participation**: you will participate in a class-wide forum on
  the current topic, where your primary responsibility will be to provide
  insightful questions that can be addressed by the current experts.

### Act III Available Points:

The following **asynchronous** activity will be worth 5 points during act III:

- **Benchmarking Proposal**: you'll propose a specific investigation into the
  topic of benchmarking as it applies to one or more prior code modules from
  this semester.

The following **synchronous** activities will be worth 5 points each during act
III:

- **Benchmarking Outcome Presentation**: you'll present to the class your
  findings from your benchmarking investigation.

- **Cumulative Oral Examination**: you'll have a one-on-one conversation with
  the instructor where questions pertaining to all five learning objectives must
  be satisfactorily answered.

- **Performance Review**: you'll present your corpus of work this semester to
  the instructor in a one-on-one setting, and be asked to evaluate the quality
  of your work, and justify those evaluations.

### Letter Grade Conversion Chart

Your score at the end of the semester will determine the letter grade you
receive, based on the below chart:

| Score | Grade |
| :---- | :---: |
| 93+   | A     |
| 90+   | A-    |
| 87+   | B+    |
| 83+   | B     |
| 80+   | B-    |
| 77+   | C+    |
| 73+   | C     |
| 70+   | C-    |
| 67+   | D+    |
| 63+   | D     |

### Regarding Attendance

In order to win a ball game, you first have to show up. Same goes for your
future careers, and same goes for this class. In keeping with department
policies, excessive absences will negatively impact your grade. More
specifically, missing class (or lab) more than six times this semester will
result in a letter grade reduction. For these purposes, being late three times
will constitute one absence.

## Tokens: The Second Chance System

My job is to facilitate your learning, and that's most effective when we're all
learning *together*. Put another way: if you're on page five while the rest of
the book club is on page five-hundred, then you're not going to get much out of
book club, and book club isn't going to get much out of *you*.

This being the case, once a deadline has passed, there will be no opportunity to
reclaim any missed points...with two exceptions to be used at your discretion,
that is.

In keeping with department tradition, CMPSC 400 offers students two tokens
that can be cashed in to make up work for two missed deadlines.

Three guidelines apply to the cashing in of any tokens this semester:

1. Tokens cannot be applied to any missed points for act I.

2. Tokens cannot be applied to any missed points for **synchronous** activities,
   unless arrangements have been made with the instructor *at least 24 hours*
   before the synchronous activity takes place.

3. Tokens may only be used up to one week after a missed deadline.

It is unlikely that there will be chances to earn extra tokens this semester.

## Our Environment: Regarding Community & Accommodations

### Allegheny Statement of Community

> Allegheny students and employees are committed to creating an inclusive,
> respectful and safe residential learning community that will actively confront
> and challenge racism, sexism, heterosexism, religious bigotry, and other forms
> of harassment and discrimination. We encourage individual growth by promoting
> a free exchange of ideas in a setting that values diversity, trust and
> equality. So that the right of all to participate in a shared learning
> experience is upheld, Allegheny affirms its commitment to the principles of
> freedom of speech and inquiry, while at the same time fostering responsibility
> and accountability in the exercise of these freedoms.

Beyond the college-wide statement of community, the Allegheny Department of
Computer and Information Science has four core values that we will all strive
to emulate while taking classes within the department:

![Allegheny CIS shared values](assets/values.png)

### Academic Accommodations

> Students with disabilities who believe they may need accommodations in this
> class are encouraged to contact Student Accessibility and Support Services
> (SASS) at (814) 332-2898.  Student Accessibility and Support Services is
> located in Pelletier Library.  Please do this as soon as possible to ensure
> that such accommodations are implemented in a timely fashion. Please see here
> for more details.

Beyond college-sponsored academic accomodations, if you ever feel that you need
an extra helping hand to manage course workload, please get with me ASAP. My
goal is to ensure that we all learn *together*; achieving this requires that
none of us get left behind.

## Buyer Beware: A Note on AI

AI tools such as Copilot and ChatGPT are fairly ubiquitous these days, and they
have immense potential and utility in a variety of disciplines and industries.
I believe that part of responsibly preparing all of you for life beyond
Allegheny includes preparing you for the ways in which such AI tools can be a
boon, as well as a hindrance.

I encourage all of you to thoughtfully deliberate over which deliverables would
be conducive to AI assistance, and which would not. Knowing that the ultimate
goal of our time here is to *learn together*, I think you'll find you'll get the
most out of this class by honestly grappling with assignments as a human first,
and then tagging in your AI tools of choice to polish, refine, and elevate your
contributions.

A word of warning: regardless of the extent to which you rely on AI tools to
complete deliverables, the one-on-one instructor conversations that will take
place during the semester will see you in an environment sans AI where you
must successfully communicate what you've learned in the course, and make up
a significant percentage of the available points this semester.
