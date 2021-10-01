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

feature_row_enypd:
- title: "eNYPD"
  excerpt: "*eNYPD* is a static analysis for identifying entry points of applications. An entry point is any method that an external user or system can control directly. The information on entry points is necessary in many different security analyses, such as Threat Modeling, input validation analyses, or security metrics."
  image_path: "/assets/images/logo-enypd.png"
  alt: "eNYPD's log."
  url: "https://uni-bremen-agst.github.io/eNYPD/"
  btn_label: "More ..."
  btn_class: "btn--info"

feature_row_codapro:
- title: "CoDaPro"
  excerpt: "*CoDaPro* stands for component-based data processing and is a tool for data measurement, filtering, and preparation."
  image_path: "/assets/images/logo-codapro.png"
  alt: "CoDaPro's logo."
  url: "https://codapro.de"
  btn_label: "More ..."
  btn_class: "btn--info"

feature_row_seeauthz:
- title: "SeeAuthZ"
  excerpt: "*SeeAuthZ* is a configurable analysis tool for extracting the implemented authorization policy. Therefore, it extracts the authorization facts the program enforces while accessing a sensitive resource. This information can be used to re-document the authorization policy if the developers lost it or never wrote it  down or compare the implemented authorization policy with the planned policy to identify divergences."
  image_path: "/assets/images/logo-seeauthz.png"
  alt: "SeeAuthZ' logo."
  url: "https://github.com/uni-bremen-agst/SeeAuthZ"
  btn_label: "More ..."
  btn_class: "btn--info"
---

{% include feature_row id="feature_row_archsec" type="left" %}

{% include feature_row id="feature_row_codapro" type="right" %}

{% include feature_row id="feature_row_enypd" type="left" %}

{% include feature_row id="feature_row_seeauthz" type="right" %}
