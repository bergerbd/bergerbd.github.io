---
title: "Tools"
permalink : /pages/tools/
layout: home
author: Bernhard Berger
author_profile: true
classes: wide

feature_row_archsec:
- title: "ArchSec"
  excerpt: "*ArchSec* automates Microsoft's Threat Modeling process in two ways: First, it automatically extracts architectural views for component-based software systems. Second, it is capable of automatically identifying security flaws in architectural views."
  image_path: "/assets/images/logo-archsec.png"
  alt: "ArchSec's logo."
  url: "https://www.archsec.de"
  btn_label: "More ..."
  btn_class: "btn--info"

feature_row_rest:
- title: "CoDaPro"
  excerpt: "*ArchSec* employs more formal dataflow diagrams for representing architectural views of software systems. The core of these extended dataflow diagrams is its extensible schema, allowing them to define new node and edge types and specify implied attributes of such types."
  image_path: "/assets/images/dataflow-diagram.png"
  alt: "Exemplary dataflow diagram depiction."
- title: "eNYPD"
  excerpt: "*ArchSec* collects formalised threat descriptions in a knowledge base and automatically detects these threats in extended dataflow diagrams. The knowledge base allows non-security experts to use architectural risk analysis. Still, it offers advantages for security experts since not all security experts know all aspects of security equally well."
  image_path: "/assets/images/security-flaws.png"
  alt: "Security flaw pictogram."
- title: "SeeAuthZ"
  excerpt: "*ArchSec* collects formalised threat descriptions in a knowledge base and automatically detects these threats in extended dataflow diagrams. The knowledge base allows non-security experts to use architectural risk analysis. Still, it offers advantages for security experts since not all security experts know all aspects of security equally well."
  image_path: "/assets/images/security-flaws.png"
  alt: "Security flaw pictogram."
---

{% include feature_row_archsec type="left" %}

# CoDaPro
[CoDaPro](https://codapro.de) stands for component-based data processing and is a tool for data measurement, filtering,
and preparation.

# eNYPD
*eNYPD* is a static analysis for identifying entry points of applications. An entry point is any method that an external
user or system can control directly. The information on entry points is necessary in many different security analyses,
such as Threat Modeling, input validation analyses, or security metrics. You can find more information on *eNYPD*
[here](https://uni-bremen-agst.github.io/eNYPD/).

# SeeAuthZ
[SeeAuthZ](https://github.com/uni-bremen-agst/SeeAuthZ) is a configurable analysis tool for extracting the implemented
authorization policy. Therefore, it extracts the authorization facts the program enforces while accessing a sensitive
resource. This information can be used to re-document the authorization policy if the developers lost it or never wrote
it  down or compare the implemented authorization policy with the planned policy to identify divergences.
