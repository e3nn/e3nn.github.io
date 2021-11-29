# Welcome to `e3nn`! {#welcome}

This is the website for the `e3nn` repository
<br>
&nbsp;&nbsp;&nbsp;&nbsp;[https://github.com/e3nn/e3nn/](https://github.com/e3nn/e3nn/)
<br>
&nbsp;&nbsp;&nbsp;&nbsp;[Documentation](https://docs.e3nn.org/)

E(3) is the [Euclidean group](https://en.wikipedia.org/wiki/Euclidean_group) in dimension 3. That is the group of rotations, translations and mirror.
[`e3nn`](https://github.com/e3nn/e3nn/) is a [pytorch](https://pytorch.org) library that aims to create **E**(**3**) equivariant **n**eural **n**etworks.

![Spherical Harmonics](/assets/img/sphharm.gif)

# Getting Started {#started}

## How to use the Resources {#how}
If you'd like to generally learn what `e3nn` is and what it's used for, check out some of [previously recorded talks](#talks) and skimming some of the [papers](#papers). If you'd like to try out `e3nn`, the first step is to [install it](#installation).

[Once you have `e3nn` up and running](#installation), try out the Jupyter notebooks in [e3nn_tutorial](#tutorial). This will give you a feel for the primary data types and classes in `e3nn`. You can also read [e3nn_book](#book) in parallel and dive into more rigorous [math resources](#math). This reading will be helpful for parsing even the most techincal parts of the relevant [papers](#papers).

If you want to talk to other folks using `e3nn`, you are most welcome to join our [recurring monthly meetings](#recurring) which are shown in the [e3nn calendar](#calendar) and our [Slack](#slack).

We want to help eliminate any bottlenecks in making Euclidean equivariant neural networks and `e3nn` accessible to a broad audience, especially scientists whose primary expertise is not machine learning. If you have an application in mind but not sure how to structure a network around it or other questions not satisfied by this page's resources, feel free to reach out to Tess (`tess@e3nn.org`).

## Installation {#installation}

Be careful to install a version of `torch_geometric` that matches the <strong>same CUDA version</strong> that your `torch` installation uses (this is general advice and not `e3nn` specific)

The full instructions for installing `e3nn` can be found [here](https://github.com/e3nn/e3nn/blob/main/INSTALL.md).

# Resources {#resources}

## e3nn_docs {#docs}
The documentation is [here](https://docs.e3nn.org/)

## e3nn_tutorial {#tutorial}
* [MRS 2021 Fall Meeting Tutorial](https://e3nn.org/mrs)

## Math that's good to know {#math}

`e3nn` makes use of group theory and representation theory. You don't need to be knowledgeable on these topics to start using `e3nn` but it might be useful to have some relevant resources handy. Some of our favorite resources are:
* [Group Theory: Application the Physics of Condensed Matter by Dresselhaus, Dresselhaus, and Jorio](https://www.springer.com/gp/book/9783540328971)
* [Lie Algebras in Particle Physics by H. Georgi](https://www.taylorfrancis.com/books/9780429499210)
* [Lecture Note on Group Theory in Physics by D. Arovas](https://courses.physics.ucsd.edu/2016/Spring/physics220/LECTURES/GROUP_THEORY.pdf)
* [Group Theory in a Nutshell for Physicists by A. Zee](https://press.princeton.edu/books/hardcover/9780691162690/group-theory-in-a-nutshell-for-physicists)
* [Linear Representations of Finite Group by J-P. Serre](https://link.springer.com/book/10.1007/978-1-4684-9458-7)

## e3nn_book [in progress] {#book}
We are currently in the progress of compiling a more user-friendly introduction to the core concepts used in `e3nn`.

## Previous Talks {#talks}
Some previous recorded talks on `e3nn`.

2020/11 Euclidean Neural Networks for [Physics ∩ ML](http://www.physicsmeetsml.org/), November 18, 2020. ([slides](https://tinyurl.com/e3nn-physics-meets-ml) // [video](https://www.youtube.com/watch?v=VN2biLjqJXc&ab_channel=PhysicsMeetsML))

2020/09 Unintended Features of E(3)NNs, [Workshop on Equivariance and Data Augmentation](https://sites.google.com/view/equiv-data-aug/home) ([video](https://www.youtube.com/watch?v=vq4s8Xgsmeo&ab_channel=WorkshoponEquivarianceandDataAugmentation) // [slides](https://docs.google.com/presentation/d/1vOOPUC0ZiPye8R3dyrXil21IOqXExTO62-Qktm-sSv4/edit?usp=sharing)), University of Pennsylvania, September 4, 2020

2020/09 Lecture on Symmetry and Equivariance in ML, [Berkeley Lab Deep Learning School](https://dl4sci-school.lbl.gov/agenda) ([video](https://www.youtube.com/watch?v=8s0Ka6Y_kIM&t=3799s&ab_channel=NERSC) // [slides](https://docs.google.com/presentation/d/1Acz3YxUI-pH80n4UOeHWktnnpjslsTXkilmP5ZGBNo4/edit?usp=sharing)), Berkeley Lab, September 3, 2020.

2020/07 Neural Networks with Euclidean Symmetry for Physical Sciences, [1st Workshop on Scientific-Driven Deep Learning (SciDL)](https://scidl.netlify.app/) ([video](https://www.youtube.com/watch?v=ZbhBV0QThbA&feature=youtu.be) // [slides](https://docs.google.com/presentation/d/1mtElk2UaQ8020xz66VYGybXpfywdBnb3m2NQ65Qbeys/edit?usp=sharing)), July 1, 2020

2020/01 An autoencoder for discrete geometry, [Applied Machine Learning Days -- AI and the Molecular World](https://appliedmldays.org/tracks/ai-molecular-world) ([video](https://www.youtube.com/watch?v=xGGpxVSWdmg)), EPFL, January 27-28, 2020, Lausanne, Switzerland

2019/12 Euclidean Neural Networks for Emulating Ab Initio Calculations and Generating Atomic Geometries, [eScience Institute Seminar](https://escience.washington.edu/data-science-seminar-12/) ([video](https://youtu.be/4gKsQG9Deew)), University of Washington, Seattle, WA

2019/09 Euclidean Neural Networks for Emulating Ab Initio Calculations and Generating Atomic Geometries, [Workshop I: From Passive to Active: Generative and Reinforcement Learning with Physics](http://www.ipam.ucla.edu/programs/workshops/workshop-i-from-passive-to-active-generative-and-reinforcement-learning-with-physics/?tab=overview), ([video](http://www.ipam.ucla.edu/abstract/?tid=16346&pcode=MLPWS1) // [slides](http://helper.ipam.ucla.edu/publications/mlpws1/mlpws1_16346.pdf)),  IPAM at UCLA, Los Angeles, CA

## Poster {#poster}
[A poster overview of the `e3nn` framework.](https://tinyurl.com/e3nn-poster)

## Papers {#papers}

Please see [this repo](https://github.com/Chen-Cai-OSU/awesome-equivariant-network) for an up to date list of papers on equivariant networks.

## Slack {#slack}
The `e3nn` developers and several collaborators discuss ideas and help each other out with projects via Slack. If you'd like to join the Slack, please send an email to Tess `tess@e3nn.org`.

## Recurring Meetings / Events {#recurring}
`e3nn` has two recurring monthly meetings in addition to other events on our [calendar](#calendar).
* A monthly developers / collaboration 1.5 hour meeting on the first Wednesday of every month (typically) at 10 am Pacific Time. We typically go around and each give a brief update on what we've been working on and if there are any difficulties we are running into.
* A monthly tutorials / documentation hackathon on the second Wednesday of every month starting at 10 am Pacific Time and ending around 6 pm Pacific Time. This is a great opportunity to ask questions.

<strong>Everyone is welcome to join these meetings -- yes, that means you!</strong> The meeting links are in the calendar events show below. Feel free to reach out to `support@e3nn.org` to introduce yourself if you are new to joining the meetings.

# Help {#help}
To get help with a question or code bug, please [follow this link](https://github.com/e3nn/e3nn#help).

# Contributing {#contributing}
To get involved with the development and improvement of `e3nn`, please [follow this link](https://github.com/e3nn/e3nn#want-to-get-involved-great).

# Calendar {#calendar}
## with Upcoming Tutorials / Meetings / Hackathons
<iframe src="https://calendar.google.com/calendar/embed?src=c_mvmhtnsv9hrf3iac9dbslq8seg%40group.calendar.google.com&ctz=America%2FLos_Angeles" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

## `e3nn` Team {#team}

### Core-development team
(aka the people answering pull-requests)
* [Mario Geiger](https://mariogeiger.ch/) (`e3nn`'s [BDFL](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life), `mario@e3nn.org`)
* [Tess Smidt](http://blondegeek.github.io/) (`tess@e3nn.org`)
* [Ben Miller](http://mathben.com/)
* [Kostiantyn Lapchevskyi](https://atomicarchitects.github.io/#koctya)

### Collaborators and Contributors

{::nomarkdown}
<table>
<tr>
    <td>
        <ul>
            <li> Josh Rackers
            <li> Thomas Hardin
            <li> Simon Batzner
            <li> Boris Kozinsky
            <li> Eugene Kwan
            <li> Albert Musaelian
        </ul>
    </td>
    <td>
        <ul>
            <li> Frank Noé
            <li> Claire West
            <li> Zhantao Chem
            <li> Nina Andrejevic
            <li> Mingda Li
        </ul>
    </td>
</tr>
</table>
{:/}

