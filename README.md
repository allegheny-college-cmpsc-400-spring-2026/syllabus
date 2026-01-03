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

## Your Instructor: Jeff Normile

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
teammates to develop coding activities and projects for the entire class, as
well as individually prepare material for a brief lecture highlighting a
specific assigned topic within that subject. You can expect to be responsible
for daily check-ins with the instructor for much of this time period.
 
### Act II: Relay

We'll then transition into a period of time dedicated to each team sharing the
content they've prepared with the rest of the class. Your teams will guide your
classmates through the completion of the coding projects you'll have prepared,
and each teammate will deliver the lectures they've individually prepared over
the course of a two-week period. Every two-week period will also culminate in a
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
