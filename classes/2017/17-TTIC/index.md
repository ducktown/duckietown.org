---
layout: page
title: TTIC and UChicago
longtitle: "Self-driving Vehicles: Models and Algorithms for Autonomy"
permalink: classes/2017/17-TTIC/index.html
---

Welcome to the webpage for **Self-driving Vehicles: Models and Algorithms for Autonomy** (TTIC 31240), which is
informally known as "Duckietown". This is the first time that the course is being offered at TTIC, following    the [extremely successful first edition at MIT in 2016](http://duckietown.mit.edu).

[Read below about what makes this a special class](#special).

**We looking for people to help me and get involved in any way. Please see  [available positions](#positions) below**

<div class='figure-with-caption'>
    <a href="/media/classes/duckietown-mit.jpg"><img src="/media/classes/duckietown-mit.jpg"/></a>
    <p>Duckietown at MIT in 2016</p>
</div>

<div class='figure-with-caption'>
    <a href="/media/classes/duckietown-taiwan.jpg">
    <img src="/media/classes/duckietown-taiwan.jpg"/>
    </a>
    <p>Duckietown at NCTU in 2016</p>
</div>

<div style='clear: both;'></div>

<style>
    .figure-with-caption img { height: 15em; width: auto;}
    .figure-with-caption {
        padding: 1.5em;
        display: block; float: left;
    }
</style>

# For students interested in taking the class

The number of spots available is extremely limited due to resource constraints (e.g., each student gets a robot). Consequently, registration is subject to instructor approval.

Please read this page thoroughly and sign up *only* if you
think the class is right for you. If you are not sure whether you would like to take the class, we would encourage you to:
* [Have a look at the site for last year's class at MIT](/classes/2016/16-MIT/index.html)
* [Read the ICRA paper about the project][duckietown-icra]
* [Read below about what makes this a special class](#special).

[duckietown-icra]: http://people.csail.mit.edu/lpaull/publications/Paull_ICRA_2017.pdf

If you'd like to register for the course, you **must** first complete this [questionnaire][questionnaire], which helps us fine-tune the class to your background. Please be verbose with the long-answer questions and include anything that might help you stand out. This class is a collaborative learning experience and we're looking for a good mix of talents and personalities.

**We invite everyone to come to the first class on Monday September 25 at 9:00am in TTIC Room 530. We will decide on enrollment following the first class.**

Note that there are no official prerequisites for the course and, while desirable, previous experience with robotics is not required. However, a strong background in programming is important, while at least a basic familiarity with computer vision and estimation are beneficial.

**NB: You need to have your own laptop to take this course, and you need to be willing to install a fresh Ubuntu 16.04 partition on it for the duration of the class (I can help you with this)**

[questionnaire]: https://goo.gl/forms/L1pQhBYMjVuxh9y32

# For non-students who want to get involved {#positions}

## University Professors and Postdocs in the Chicago area

We are looking for excellent guest lectures to include in the class. The topic of the lectures is very flexible, but if you see something that is already [in the syllabus](syllabus/) then that's even better. Please [contact me asap][walter].

Additionally, we are looking for postdocs to act as mentors in the course project phase of the class. In the MIT version we had about 15 or so of these magical postdocs helping with the class. It is not impossible that you get your name on a paper out of it! (But no promises..). Please [contact me asap][walter].

## Anyone else that wants to help

We have many needs from small to large. Whatever your expertise, it is likely that we can use your help. Not least of all would other students who want to act as teaching assistants (I might be able to pay you). Please [contact me asap][walter].


# Syllabus

See the official [course syllabus](syllabus/) for more details on the class.

## Dates and times

Lecture times:

<table id='times'>
<thead>
    <tr><td>day</td><td>time</td><td>room</td></tr>
    </thead>
    <tbody>
    <tr><td>Monday</td>	<td>9am-11am</td>	<td>TTIC 530</td></tr>
    <tr><td>Wednesday</td><td>9am-11am</td> <td>TTIC 530</td></tr>
    </tbody>
</table>

<style>
#times thead { font-weight: bold; }
#times tbody td { padding-right: 1em; padding-top:0.2em;}
</style>

## Instructor

<!-- Institute of Dynamic Systems and Control. -->

- [Prof. Matthew Walter][walter]

[walter]: http://ttic.edu/walter

**Learning assistants**:

- Andrea Daniele
- Zhongtian (Falcon) Dai
- TBD

*We are looking for more [learning assistants](LAs/). Please
contact [Matthew Walter][walter] if you are interested.*

**Guest lecturers**:

- TBD
- TBD

*We are looking for postdocs [to give guest lectures on their specialties](lecturers/). Please
contact [Matthew Walter][walter] if you are interested.*


## Grading

The grade is based on:

* the realization of a project (percentage TBD);
* a project report (percentage TBD); and
* a project presentation (percentage TBD). The projects will be group-based, but the contribution of each student will be assessed individually.


## Prerequisites

* Familiarity with the GNU/Linux development environment.
* Access to a laptop with Ubuntu 16.04 installed.


## Related classes at TTIC

The most relevant course at TTIC is:

- [Planning, Learning, and Estimation for Robotics and Artificial Intelligence][robot-learning] (aka Robot Learning and Estimation).
If you cannot get into Self-driving Vehicles: Models and Algorithms for Autonomy, the Robot Learning and Estimation class
will give you a solid introduction to robotics.
Because the content and format are different than this course, it would be most beneficial to take Robot Learning and Estimation first, but the two can be taken in either order.

[robot-learning]: http://www.ttic.edu/courses/#robo


# What makes this a special class? {#special}


## Class philosophy

The best engineers are the ones who have solid theoretical foundations,
as well as practical experience.

In autonomous robotics, it is important to also get the "feeling" of
what actually makes a robot work. The way to do this, is not to study every component in isolation,
but rather to integrate the components as part of a complex system.

For more information about the class philosophy, please
refer to this paper:

<cite class='pub-ref-desc' id='bib:tani16duckietown'>
    <a href='https://eapsweb.mit.edu/people/jtani'>Jacopo Tani</a>, <a href='http://people.csail.mit.edu/lpaull/'>Liam Paull</a>, <a href='https://eapsweb.mit.edu/people/zuber/'>Maria Zuber</a>, <a href='http://danielarus.csail.mit.edu/'>Daniela Rus</a>, <a href='http://www.mit.edu/~jhow/'>Jonathan How</a>, <a href='https://marinerobotics.mit.edu/'>John Leonard</a>, and
    <a href="https://censi.science">Andrea Censi</a>.
    <strong class="title">Duckietown: an innovative way to teach autonomy.</strong>
    <span class="booktitle">In <em>EduRobotics 2016</em>. Athens, Greece, December 2016.</span>
    <span class="links"><span class="pdf"><a href="http://people.csail.mit.edu/lpaull/publications/Tani_EDU_2016.pdf">
    <img style='border:0; margin-bottom:-6px; width:17px; height: 17px' src='/media/pdf.png'/> pdf</a></span></span>
</cite>


## A personal experience

Each student gets their own personal Duckiebot and can bring it home.

<!-- On the first day, you will be given a box of parts. -->


## Collaboration/competition with twin institutions

This class is offered at the same time at two others institutions:

- The University of Montreal, Canada, lead by Prof. Liam Paull.
- ETH Zürich, lead by Dr. Andrea Censi.

The three institutions will develop the autonomous fleets together, and there will be a (very friendly) competition at the end.


# Support

We are grateful to TTIC, whose support made this class possible.

<!-- ### Broader impact beyond ETH Zurich

As a student at ETH Zurich, however you arrived here,
you have been lucky.

So, a great part of this

In particular, the only ones where there is an
practical robotics part

Everything produced by the class will be open source.

### A broader, broader impact

In all of this, the whimsical aspects ...



## Class format

-->


<style>
[href="#"] {color: red; }
[href="#"]:after { content: " (broken link) ";
    color: red;}
</style>
