---
title: "About me"
permalink : /
layout: home
author: Bernhard Berger
author_profile: true
classes: wide
---

I am a lecturer at the [Computer Engineering Group](https://www.tuhh.de/es/ce.html) at
the [Institute of Embedded Systems](https://www.tuhh.de/es/home.html). The institute belongs
to the [Hamburg University of Technology](https://www.tuhh.de). Before working here, I was
a research assistant and member of the [software engineering group](https://www.uni-bremen.de/en/st) at the [University of Bremen](https://www.uni-bremen.de).

## Research
My PhD thesis took quite a while because of several additional research topics I
worked on. Besides writing grant proposals, I already advised colleagues working
on different research projects related to static analysis and software security. After
my PhD, I continued working on these topics and started with new topics related to
the existing topics.

### Architectural Risk Analysis
I continue my work on architectural risk analysis using _ArchSec_. Currently, we transfer
the ideas to the area of hardware design. Therefore, we are working on ideas to model
hardware components using *ArchSec* and on a knowledge base containing hardware-related
security flaws. 

### Optimisation research
Based on different research ideas, we are working on a research software for optimisation
research and extended it with our research ideas. The corresponding tool,
[*EvoAl*](https://www.evoal.de) focuses on making optimisation algorithms configurable. We
aim at reducing the programming overhead to zero for standard optimisation algorithms. Instead,
you write a configuration file using a domain-specific language to orchestrate the optimisation
algorithm with different options.


### Static Analysis and Security Research
We worked on using static analyses to extract different security
aspects of software systems. [SeeAuthZ](https://github.com/uni-bremen-agst/SeeAuthZ),
for instance, is a configurable analysis tool for extracting the implemented
authorization policy. Therefore, it extracts the authorization facts that is enforced
if the program accesses a sensitive resource. This information can be used to
re-document the authorization policy if the developers lost it or never wrote it
down or compare the implemented authorization policy with the planned policy to
identify divergences. 

For improving static analysis of enterprise systems, we created a new tool, called
[eNYPD](https://uni-bremen-agst.github.io/eNYPD/) for finding application's entry-points
and understanding the wiring of modern component-based software systems.

An interesting combination, which, hopefully, yields some interesting results is the
combination of static analysis and machine learning to identify security bugs. In a 
joint project with the [Federal Office for Information Security](https://www.bsi.bund.de/EN/Home/home_node.html),
we used ICFGs to identify suspicious parts of a software system without explicitly
coding security bug patterns.

### Data processing
Furthermore, I started to work on different aspects related to the [collaborative
research centre 1232](https://www.uni-bremen.de/en/farbige-zustaende). The main
idea of the CRC is to find new materials using big data and machine learning. In
this context, [CoDaPro](https://codapro.de) was developed. _CoDaPro_ stands for
component-based data processing and is a tool for data measurement and filtering.

## PhD Topic
After my diploma thesis, I refocused on the topic of Software Security. In my PhD
thesis, I focused on automating [Microsoft's Threat Modeling](https://www.microsoft.com/en-us/securityengineering/sdl/threatmodeling)
process. The publications can be found in the [publications section](/pages/publications)
and on my [ResearchGate profile](https://www.researchgate.net/profile/Bernhard-Berger-2).
The result of my thesis is [ArchSec](https://archsec.de), the _Architectural Security
Tools Suite_. It is integrated into [Eclipse](https://www.eclipse.org/) and is based
on [Soot](https://github.com/soot-oss/soot), a great static analysis framework for
Java-bytecode-based programs. To automate Microsoft's Threat Modeling, I use static
analyses to extract extended dataflow diagrams, an architectural view of a software
system, automatically. Furthermore, a knowledge base was created to host security flaw 
patterns. These patterns are searched in the extended dataflow diagrams. For more details
on _ArchSec_ you can visit the [ArchSec homepage](https://archsec.de).

## Industry
After my graduation, I worked for [Axivion GmbH](https://www.axivion.com/en/) for
two years. Axivion is a static code analysis company, and their tool suite deals with
inner software quality aspects and is now part of the [Qt group](https://www.qt.io).
In my time at Axivion, I worked on different parts of their tool suite, starting with
the analyser frontends, scripting binding, and their web interface. I also took part in
workshops with customers regularly and gained insight into their software development 
processes. After two years, I decided to return to academia and focus on research.


## Studies
I graduated in December 2007 from the University of Bremen, and my diploma thesis,  which
I wrote at [Bosch Corporate Research](https://www.bosch.com/research/), deals with clone
detection for embedded software systems. The research question I  dealt with was whether
it is possible to reduce the memory footprint of embedded software systems using clone
detection. The short answer to this question was: _"No, it is not possible when using
heavily optimising compilers."_ During my studies, I focused on topics such as software
engineering, compiler construction, static analysis, and reverse engineering.




