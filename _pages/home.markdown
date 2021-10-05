---
title: "About me"
permalink : /
layout: home
author: Bernhard Berger
author_profile: true
classes: wide
---
In September 2021, I left the [University of Bremen](https://www.uni-bremen.de), where
I was a research assistant and member of the [software engineering group](http://www.informatik.uni-bremen.de/st/index.php?language=en).
Now, I am a lecturer at the [Hamburg University of Technology](https://www.tuhh.de/alt/tuhh/startpage.html)
where I am part of the [Computer Engineering Group](https://www.tuhh.de/es/ce.html) at
the [Institute of Embedded Systems](https://www.tuhh.de/es/home.html).

## Current Research
Currently, I am working on different ideas in the area of software security
and static analysis. I try to continue my work on architectural risk analysis using
_ArchSec_. Furthermore, I am trying to combine machine learning with static analysis.
An interesting combination, which, hopefully, yields some interesting results. Lastly,
we created a new tool, called [eNYPD](https://uni-bremen-agst.github.io/eNYPD/) for
finding application's entry-points.


## Further Research
My PhD thesis took quite a while because of several additional research topics I
worked on. Besides of writing grant proposals, I already advised colleagues working
ond different research projects related to static analysis and software security.

In the last years, I started to use static analyses to extract different security
aspects of software systems. [SeeAuthZ](https://github.com/uni-bremen-agst/SeeAuthZ),
for instance, is a configurable analysis tool for extracting the implemented
authorization policy. Therefore, it extracts the authorization facts that enforced
if the program accesses a sensitive resource. This information can be used to
re-document the authorization policy if the developers lost it or never wrote it
down or compare the implemented authorization policy with the planned policy to
identify divergences. 

Furthermore, I started to work on different aspects related to the [collaborative
research centre 1232](https://www.uni-bremen.de/en/farbige-zustaende). The main
idea of the CRC is to find new materials using big data and machine learning. In
this context, [CoDaPro](https://codapro.de) was developed. _CoDaPro_ stands for
component-based data processing and is a tool for data measurement and filtering.
Additionally, I worked on aspects of the machine learning and evolutionary
algorithm's part. You can find more details on my publications page.

## PhD Topic
After my diploma thesis, I refocused on the topic of Software Security. In my PhD
thesis, I focused on automating [Microsoft's Threat Modeling](https://www.microsoft.com/en-us/securityengineering/sdl/threatmodeling)
process. The publications can be found in the [publications section](/pages/publications) and on my
[ResearchGate profile](https://www.researchgate.net/profile/Bernhard-Berger-2).
The result of my thesis is [ArchSec](https://archsec.de), the _Architectural Security
Tools Suite_. It is integrated into [Eclipse](https://www.eclipse.org/) and is based
on [Soot](https://github.com/soot-oss/soot), a great static analysis framework for
Java-bytecode based programs. To automate Microsoft's Threat Modeling, I use static
analyses to extract extended dataflow diagrams automatically. Furthermore, a
knowledge base was created hosting security flaw patterns. These patterns are
searched in the extended dataflow diagrams. For more details on _ArchSec_ you can
visit the [ArchSec homepage](https://archsec.de).

## Industry
After my graduation, I worked for [Axivion GmbH](https://www.axivion.com/en/) for
two years. Axivion is a static code analysis company, and their tools deal with
inner software quality aspects. In my time at Axivion, I worked on different
parts of their tool suite, starting with the frontends, scripting binding, and
their web interface. I also took part in workshops with customers regularly and
gained insight into their software development processes. After two years, I
decided to return to academia and focus on research.


## Studies
I graduated in December 2007 from the University of Bremen, and my diploma thesis,  which
I wrote at [Bosch Corporate Research](https://www.bosch.com/research/), deals with clone
detection for embedded software systems. The research question I  dealt with was whether
it is possible to reduce the memory footprint of embedded software systems using clone
detection. The short answer for this question was: _"No, it is not possible when using
heavily optimising compilers."_ During my studies, I focused on topics such as software
engineering, compiler construction, static analysis, and reverse engineering.




