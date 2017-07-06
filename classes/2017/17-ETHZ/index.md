---
layout: page
title: ETH Zürich
longtitle: "Autonomous Mobility on Demand (AMOD)"
permalink: classes/2017/17-ETHZ/index.html
---

Welcome to the webpage for the class **Autonomous Mobility on Demand (AMOD): from car to fleet** (catalogue number [151-0323-00L][official]), which is
informally known as "Duckietown".

[official]: http://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheitPre.do?semkez=2017W&ansicht=EINSCHRAENKUNGEN&lerneinheitId=119019&lang=en

This class is a new offering at ETH Zürich for Fall 2017
in the context of the [Master of Science in Robotics, Systems and Control][master]
and the [Master in Mechanical Engineering][master-meche]
in the [Department of Mechanical and Process Engineering (D-MAVT)][mavt].

This class follows
the [extremely succesfull first edition at MIT in 2016](/classes/2016/16-MIT/index.html).

[Read below about what makes this a special class](#special).

[master]: http://www.master-robotics.ethz.ch/
[mavt]: http://mavt.ethz.ch
[master-meche]: http://www.master-mechanical-engineering.ethz.ch/


**For ETH Zürich Students**:
Note that there is only a limited number of spots available,
because of resource constraints (e.g. each student gets a robot).

Please read this page thoroughly and sign up *only* if you
think the class is right for you. It might help to take a
look at the materials for the first edition of the class, at
the site [duckietown.mit.edu](http://duckietown.mit.edu).


<p class='under-construction'>
Please come back later in the summer to this page, as
we will prepare a questionnaire for you
which helps us fine-tuning the class to your background.
</p>





## Positions available

**For ETH Zürich Master Students**: We have available positions for:

* [TAs](TAs/);
* [Other work positions](other/).
* [Master's theses related to Duckietown](masters/).

**For ETH Zürich postdoctoral researchers (and very senior Ph.D. students)**: Last year,
at MIT, one of the collateral uses of Duckietown was to
provide an opportunity for postdocs to
develop their teaching and mentoring skills. We will reproduce
the same idea.

We are looking for:

* [mentors](mentors/)
* [lecturers](lecturers/)

[questionnaire]: #



## Dates and times

This is a 4 credits class.

Lecture times:

<table id='times'>
<thead>
    <tr><td>day</td><td>times</td><td>room</td></tr>
    </thead>
    <tbody>
    <tr><td>Monday</td>	<td>13-15</td>	<td>HG E 33.5</td></tr>
    <tr><td>Wednesday</td><td>10-12</td> <td>HG D 3.3</td></tr>
    </tbody>
</table>

There will be a lab session, whose time and space will be
announced later.

<style>
#times thead { font-weight: bold; }
#times tbody td { padding-right: 1em; padding-top:0.2em;}
</style>

## Instructors

<!-- Institute of Dynamic Systems and Control. -->

- [Prof. Emilio Frazzoli][frazzoli]
- [Dr. Andrea Censi][censi]
- [Dr. Jacopo Tani][tani]

[frazzoli]: http://www.idsc.ethz.ch/research-frazzoli.html
[censi]: https://censi.science/
[tani]: https://eapsweb.mit.edu/people/jtani

Guest instructors:

- TBD
- TBD
- TBD

*We are looking for postdocs [to give guest lectures on their specialties](lecturers/)*.

<!-- Please
contact [Andrea Censi][censi] if you are interested.* -->


## Syllabus


<p class='under-construction'>
To write. Please check back later.
</p>


## Grading

The grade is based on three factors:

1. the realization of a project (40%);
2. a project report (40%);
3. a project presentation (20%).

The projects will be group based, but the contribution of each student will be assessed individually.


## Prerequisites

These are necessary pre-requisites to take the class:

* Knowledge of basics of probability theory.
* Familiarity with Linux development.
* Familiarity with Python.
* Access to a laptop on which you can install a particular Linux distribution
  dedicated to the class. Virtual machines are unsupported (you will be on your own
  to debug problems related to the configuration.)
* Ability to store somewhere (at home or somewhere of campus), and to bring regularly to the lab, a box, or "Duckiebox", of dimensions 30 cm &times; 30 cm &times; 60 cm. This box has to be used to contain your Duckiebot and associate materials.

<p class='under-construction'>
We are finalizing the choice of distribution.
It will likely be Ubuntu Mate 16.04.
</p>

We will teach or provide points to these skills, but you are encouraged to read about them
before the class:

* Source code management using Git; use of Github; branching and pull requests.
* Logging and working in remote computers using `ssh`.
* Use of the `vi` editor.


## Related classes at ETH Zürich

There are several related classes available
to ETH Zürich students.
In particular, we recommend:

- Prof. [Siegwart][siegwart]'s and Prof. [Chli][chli]'s [Autonomous Mobile Robots (AMR)][AMR], in the second semester.
If you cannot get into AMOD, the AMR class will give you a solid introduction
to robotics. Because the content and format are different than AMOD, it makes
sense to take AMR as either a follow-up to AMOD or before AMOD.  Note also that
AMR is already available in EdX.

- Prof. [Scaramuzza][scaramuzza]'s [Computer Vision][scaramuzza-class] class. This class is taught in the same semester, and it is a great complement to this one.

[siegwart]: http://www.asl.ethz.ch
[scaramuzza]: http://rpg.ifi.uzh.ch
[scaramuzza-class]: http://rpg.ifi.uzh.ch/teaching.html
[chli]: http://margaritachli.com
[AMR]: http://www.asl.ethz.ch/education/lectures/autonomous_mobile_robots/spring-2016.html


# What makes this a special class {#special}


## Class philosophy

The best engineers are the ones who have solid theoretical foundations,
as well as practical experience in the domain of intereset.

In autonomous robotics, it is important to get the "feeling" of what actually
makes a robot work---how the success or failure depends on subtle interaction
between many hardware and software components.

To obtain enlightenment, it is necessary to study a complete system
like Duckietown --- the materials might be cheap, the appearance
might be playful, but the complexity of behaviors and representations
is comparable to those of deployed robotic systems.

<!-- Studying, and building from scratch, a complex system like the DuckeibotThe way to do this, is not to study every component in
isolation, but rather creating a complex system. -->

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


### A personal experience

Each student gets their own personal Duckiebot and can bring it home.

<!-- On the first day, you will be given a box of parts. -->


### Collaboration/competition with twin institutions

This class is offered at the same time at two others institutions:

- At the University of Montreal, Canada, lead by Prof. Liam Paull.
- At the University of Chicago / Toyota Technological Institute, led by Prof. Matthew Walter.

The three institutions will develop the autonomous fleets together, and there will be
a (very friendly) competition at the end.


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
