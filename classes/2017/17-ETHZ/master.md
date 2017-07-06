---
layout: page
title: Master's theses
longtitle: Master's theses related to Duckietown
permalink: classes/2017/17-ETHZ/masters/index.html
parent: classes/2017/17-ETHZ/index.html
---
<style>
h4 {
    /*display: block; font-weight: bold;*/
    /*float: left;
    clear: left;*/
    display:table-cell;
    /*color: red;*/
    font-weight: bold;
}
</style>

This page lists the Master theses available related to
Duckietown. These Master's theses are to be performed at the
[Institute for Dynamic Systems and Control][idsc] under the
direction of Prof. [Emilio Frazzoli] and [Andrea Censi];
for the "interdisciplinary" theses, collaboration with other
labs is encouraged.

<p class='under-construction'>
Note: This page is under construction and only
a few of the Master's theses are described in detail.
Please check back by mid July to read the complete list.
</p>


These are the Master's theses available:

1. [**Design of a worldwide low-cost robotics education experience**](#design-low-cost) -
  an interdisciplinary, entrepreneurial thesis.
2. **Optimal co-design of resource-constrained robots** - developed either as an interdisciplinary thesis in mechanical engineering/robotics, or as a theoretical thesis in applied mathematics.
3. **Vision-based SLAM under resource constraints** - a robotics robotics/vision thesis, can be developed more on the *algorithmic* side (focus on the implementation) or the _theoretical_ side (focus on models and theoretical prediction).
4. **Fleet coordination and management**
5. **Learning the rules of the road** - an algorithmic machine learning-focused thesis.
6. **Planning to learn and learning to plan**  - an algorithmic, with elements of machine learning-focused and robot planning and control
7. [**Scalable architectures for autonomy: from Duckiebot to an autonomous go-kart to a self-driving taxi**](#scalable).

## Master Thesis: Design of a worldwide low-cost robotics education experience {#design-low-cost}

Type of project: *interdisciplinary*, *entrepreneurial*.

#### Motivation

One of the goals of the Duckietown project is to design a low-cost platform.
Suppose there is 1 million people in the world interested in learning robotics
using Duckietown. How to make it feasible for 1 million people to have their
Duckiebot?

Here, when we say "low costs", we do not include only money, but also all the
other costs that are necessary to own and operate the platform.

Moreover, we do not consider the platform in isolation. If you are learning
robotics, probably you would also like to be learning embedded systems,
computer vision, and other similar topics that would use similar equipment.

In this sense, while the cost of a Raspberry PI 3 is $35, that monetary cost
should be amortized among other projects that could be performed with the same
hardware.

#### Methodology

In this thesis, in addition to engineering design methods, you will be
also interacting with the customers and possible industrial partners
that are interested in manufacturing the system at a large scale.

#### Expected results

The expected results are (a subset of) these:

- Market research for the Duckietown "customers", including:

    * Graduate and undergraduate learning institutions in high-income
      countries (such as ETH Zürich, MIT, and so on).
    * Graduate and undergraduate learning institutions in low-income countries.
    * K-12 institutions in high-income countries.
    * Self-guided learners in high-income countries.
    * Self-guided learners in low-income countries.

  We already have a network of contacts for all of these categories.

- A design, or a number of designs, for the Duckiebot and the Duckietowns,
  that could be scaled up to worldwide distribution.

- Establishing collaboration with possible industry partners
  that are interested in:

  * Manufacturing part of the system.
  * Packaging and distribution.

- Establishing the support of governments and NGOs to find help
  for publicizing and support the project.

## Scalable architectures for autonomy: from Duckiebot to an autonomous go-kart to a self-driving taxi {#scalable}

### Motivation

Robots come in all shapes and sizes. And for each one, the software is created
ad hoc. The software created for a robot cannot automatically be made to run on
another different robot, even if the sensors, the dynamics, and the task  are
similar, because it depends on a set of **implicit** assumptions about the
resources available, the precision of the sensor, the noise in the process, and
so on.

Is it possible to create a scalable architecture that works on a wide range of
platforms? For example, can we create an "autopilot" that can drive the humble
$150 Duckiebot, a professional $10,000 go-cart, and a full-sized self-driving
car?

### Methodology

To achieve that goal, it is necessary to create an architecture that has:

* Scalable perception algorithms;
* Scalable internal representations of the world;
* Scalable planning algorithms;

These three components should scale, up and down, with the resources available.

For representations, one type of scaling is achieved with configuration parameters:
For example, with low computation available, the map might have low resolution,
and the resolution increases when there is more computation.
Another type of scaling swaps in and out different "layers" of map.

For perception and planning algorithms, likewise, the change can be either in parameters
or in algorithms.

#### Expected results

An architecture that adapts to drive a Duckiebot (with a Raspberry PI 3 computer and 1 camera) and a self-driving car (with an nVidia Drive PX and 6 cameras). 


[idsc]: http://www.idsc.ethz.ch/
[Emilio Frazzoli]: http://www.idsc.ethz.ch/the-institute/people/person-detail.html?persid=224034
[Andrea Censi]: https://censi.science/
