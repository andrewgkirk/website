---
title: Ultra-fast plasmonic PCR
summary: Accelerating the polymerase chain reaction using light for rapid detection of bacterial and viral infections.
tags:
- PCR
date: "2020-02-28T00:00:00Z"
authors:
- admin
# - Padideh-Mohammadyousef

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Image (C) Andrew Kirk 2020
  placement: 1
  focal_point: Smart
  placement: 2
 

links:
# - icon: twitter
 # icon_pack: fab
 # name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

 The polymerase chain reaction (PCR) is widely used to amplify and identify DNA samples. Most commercial PCR systems require over an hour to produce a result, but we have recently demonstrated a new approach that uses laser heating of gold nanoparticles to drive the reaction. This has allowed us to produce test results in under ***five minutes*** and opens the technique up to point-of-care applications.

 The gold nanoparticles are encapsulated and dispersed within the PCR solution. An 808 nm 2W laser then heats the particles, and cooling is accomplished using forced air. Because we heat and cool only the PCR solution and the thin-walled PCR tube, the wall-plug efficiency is much greater than in a standard thermocycler and the weight of the system is reduced. The method works well with standard 20 $\mu$L sample volumes and standard PCR tubes. It has been tested with a range of different polymerases and for PCR, RT-PCR and LAMP \[ [1](/publication/rn-1203) \]. It is possible to use a compact VCSEL laser to heat the tube directly with no intervening optics \[ [2](/publication/rn-1379) \].

 The technique is compatible with standard fluorescence qPCR techniques. However, we have also developed a fluorophore-free method to quantify amplicon production. Because the PCR tubes are not surrounded by bulky heaters we are able to shine UV light directly through the tube. By measuring the change in UV absorption as dNTPs are converted to DNA amplicons we can directly quantify the reaction. We have demonstrated sensitivity of less than 10 copies \[ [3](/publication/rn-1380) \] .   
{{< figure src="/img/UVgraph.png" caption="Direct detection of amplicon production via UV absorption measurement \[ [3](/publication/rn-1380) \]" >}}

 Current research efforts include extending the design to a multichannel system, developing a cartridge-based approach and developing a rapid test for the SARS-CoV-2 virus, responsible for COVID-19.

 The intellectual property generated from this project has been licenced to a McGill start-up company [Pronto Biomedical Devices](prontomedtech.com).

 **Students currently involved in this project:**
 - {{% mention "Padideh-Mohammadyousef" %}}
 - {{% mention "Mamoun-Benchekroun" %}}
 - {{% mention "Sihui-Shen" %}}

 **Collaborators:**  
 - [Prof. Mark Trifiro](https://www.mcgill.ca/endocrinology/facultydir/trifiromark) (Jewish General Hospital)
 - [Prof. Miltiadis Paliouras](https://www.mcgill.ca/expmed/dr-miltiadis-paliouras) (Lady Davis Institute)
 - [Prof. Viviane Yargeau](http://yargeau3cs.lab.mcgill.ca/) (McGill Department of Chemical Engineering)

 **Funding agencies:**
- Genome Quebec
- Genome Canada
- CIHR
- McGill Faculty of Engineering (William and Rhea Seath Award for Engineering Innovation)
- Trottier Institute for Sustainability in Engineering and Design (TISED) and McGill Planetary Health Programs
