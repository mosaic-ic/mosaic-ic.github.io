---
title: "The Ultimate MOSAIC Bootcamp 2022 Documentation"
layout: post
date: '2022-08-24 10:00:00 +0200'
categories:
- learningnotes

---
The <b>Modular Open Source Analog IC Design</b> (MOSAIC) bootcamp had a goal to connect all independent parties working on automated analog design frameworks and workflows to "touch base"- to share the ideas and developments that had previously been fragmented and largely independent.

Speakers, contributors, and participants travelled to Linz, Austria from all over the world- Germany, US, Philippines, South Korea, Chile, Netherlands including of course people from other cities in Austria.


Seven student participants came on the invitation of Dr. Mirjana Videnovic-Misic to participate in the bootcamp. We were introduced to programmatic analog IC design and layout in the hopes of spreading the use of the paradigm in other organizations.

<img src="\images\IMG_20220817_174706.jpg" style="width:75%;margin-left:auto;margin-right:auto;display:block">

Student Participants:

* Hanyang University - NiftyLab Team
   * Taeho Shin (신태호)
   * Seonghyun Park (박성현)
   * Youngmin Oh (오영민)
* University of the Philippines - Microlab Team
   * Ryan Antonio
   * Lawrence Quizon
* Universidad Técnica Federico Santa María - AC3E Team
   * Aquiles Viza
   * Kevin Pizarro

Offline Participants:

* Silicon Austria Labs
  * Mirjana Videnovic-Misic
  * Martin Koehler
  * Fatemeh Abbassi
  * Khuram Shehzad
  * Hazem Salama
* Infineon
  * Christoph Sandner
  * Thomas Brandtner
  * Florian Renneke
* OS Community
  * Matthias Koefferlein (also Infineon)
  * Thomas Parry
* Curtis Mayberry (Skyworks)
* Stephan Gether (CISC)
* Benjamin Prausch (Fraunhofer)
* Carinthia University of Applied Sciences
  * Vinayak Hande
  * Osheen Mikhail

## Talks

<div style="text-align:center">
<h1> <a href="https://www.youtube.com/playlist?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS"><img src="\images\2022-08-25-10-21-29.png" style="width:25%;height:25%"></a>
</h1>
</div>
<br><br>
<div style="display:grid; grid-template-columns: 50% 50%; grid-template-rows: 23vh 23vh 23vh 23vh 23vh 23vh 23vh 23vh 23vh 23vh 23vh 23vh;column-gap:1vh;row-gap:13vh">
    <div class="wrapper" style="grid-area:1/2;align-self:center">
    <iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/IzJbVG-FHJc" title="Anagen Motivation | Christoph Sandner | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:1/1;align-self:center">
    The bootcamp kicked off with a talk from <b>Christoph Sandner discussing Infineon's motivation for automated analog generation </b>, which they called formerly called Anagen.
    </div>
    <div class="wrapper" style="grid-area:2/2;align-self:center">
    <iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/gqVwUhRU2OQ?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS" title="Democratizing IC Design | Boris Murmann | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:2/1;align-self:center">
    <b>Boris Murmann from Stanford University talked about the advent of open-source IC design </b>, the initiatives being performed for it, its benefits, with the open-sourcing of Skywater's 130nm PDK and soon its 90nm PDK.
    </div>
    <div class="wrapper" style="grid-area:3/1;align-self:center">
    <b>Florian Renneke introduced Infineon's</b> new software framework called the "MOSAIC Orchestra (MOSAIC Framework)" designed to act as a connector to merge the design flows of different analog generation frameworks.
    </div>
    <div class="wrapper" style="grid-area:3/2;align-self:center"><iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/tcUeRRgeEG4?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS" title="Open Source MOSAIC Framework Workshop | Florian Renneke | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:4/1;align-self:center">
    <b>Taeho Shin, Youngmin Oh, and Seonghyun Park</b> discussed LAYGO2's internal workings, from the grid definitions, templates, and PDK abstractions.
    </div>
    <div class="wrapper" style="grid-area:4/2;align-self:center"><iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/RI0rDiXslOE?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS" title="LAYout with Gridded Objects (LAYGO2) | Taeho Shin, Youngmin Oh, Seonghyun Park | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:5/1;align-self:center">
    <b>Jean-Paul Chaput</b> from LIP6 talked about CORIOLIS: a set of tools (including automatic place & route) for programmatic VLSI design with support for digital, analog and mixed-signal designs. 
    </div>
    <div class="wrapper" style="grid-area:5/2;align-self:center"><iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/WoS4USiYLuc?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS" title="CORIOLIS | Jean-Paul Chaput | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:6/1;align-self:center">
    <b>Martin Jan Köhler</b> from Silicon Austria Labs held a workshop on using BAG2 (Berkeley Analog Generator 2) with his new software abstractions to automate some of the workflow. (Multiple Videos)
    </div>
    <div class="wrapper" style="grid-area:6/2;align-self:center"><iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/57lnhDF0c0k?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS" title="BAG2 Part 1 - Virtuoso Template Sample Flow | Martin Jan Köhler | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:7/1;align-self:center">
    <b>Zhaokai Liu</b> from UC Berkeley's Wireless Research Center shared his experiences and methods with using BAG2 and the newer BAG3 with his PHD research and tapeouts.
    </div>
    <div class="wrapper" style="grid-area:7/2;align-self:center"><iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/r13YkVNSFik?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS" title="" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:8/1;align-self:center">
    <b>Santerri Porrasma</b> from Aalto University also shared his experiences with using BAG for his own PHD work, including an introduction to TheSyDeKick (The System Development Kit), a framework made for SoC development.
    </div>
    <div class="wrapper" style="grid-area:8/2;align-self:center"><iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/GnoHu1doMP4?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS" title="PhD work with BAG: Thoughts and experiences | Santeri Porrasma | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:9/1;align-self:center">
    <b>Mehdi Saligane</b> discussed Michigan Integrated Circuits Laboratory's OpenFASoC that performs design automation by generating analog layouts from specifications with other design flows such as to make it compatible with the Verilog design flow with digital P&R and logic synthesis.
    </div>
    <div class="wrapper" style="grid-area:9/2;align-self:center"><iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/wXegh9I5UO8?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS" title="OpenFASoC update | Mehdi Saligane | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:10/1;align-self:center">
    <b>Curtis Mayberry introduced Cascode Labs'</b> Virtue and Softworks. Virtue marries Python and Cadence SKILL code, allowing two-way access of each to the other. Softworks allows Cadence to have new cellview types allowing full design workflows that use Python to be performed entirely inside Cadence. 
    </div>
    <div class="wrapper" style="grid-area:10/2;align-self:center"><iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/5GJbBLpHo6s?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS" title="Virtue & Softworks | Curtis Mayberry, Cascode Labs | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:11/1;align-self:center">
    <b>Harald Pretl</b> from Johannes Kepler University talked about his recent paper Fifty Nifty Two-Transistor Circuit Variations, showing how powerful and useful circuits with two transistors can be. The bootcamp's student participants created generators these two-transistor circuits because of their usefulness and reusability.
    </div>
    <div class="wrapper" style="grid-area:11/2;align-self:center"><iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/jL7MVr5wY5w?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS" title="Fifty Nifty Variations of Two-Transistor Circuit | Harald Pretl | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:12/1;align-self:center">
    <b>Mathias Koefferlein</b> held a workshop on using KLayout: a popular tool he developed that started as a GDS viewer but has since gotten powerful editing and scripting features, support for reading and writing many layout filetypes, and its own programming environment. 
    </div>
    <div class="wrapper" style="grid-area:12/2;align-self:center"><iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/5t78kJ991js?list=PLXTGiaUILPlX6tQz377Hqm6DnZw2G7RzS" title="Producing Layout with KLayout session 1 | Matthias Koefferlein | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="wrapper" style="grid-area:13/1;align-self:center">
   <b>Ayan Biswas</b>, the current lead developer of BAG3, discussed the details of the BAG3 workflow- how it's different from BAG2 and what they've added (EM simulation, partial layout, design loops). He also discusses the BWRC projects that have used it, including his own, and his opinion on the effectiveness of the paradigm.
   </div>
   <div class="wrapper" style="grid-area:13/2;align-self:center"><iframe style="width:100%;height:181px" src="https://www.youtube.com/embed/Lim_A1x9yQM" title="Generator based Design Methodology using BAG 3.0 | Ayan Biswas | MOSAIC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
   </div>
</div>
<br>
<br>
<br>

## Things we made

### 1. [LAYGO2 inside the MOSAIC Orchestrator](https://gitlab.com/mosaic_group/mosaic_framework/mosaic-laygo2/-/tree/sdf_integration)

#### Aquiles Viza, Lawrence Quizon, Ryan Antonio, Kevin Pizarro,

In the first week, the students worked on familiarizing themselves with Infineon's MOSAIC Orchestrator by integrating the first fully open-source design flow into it: LAYGO2 + MAGIC VLSI. 

Using the Orchestrator's task-based cache-enabled designs allowed the LAYGO2 design to flow faster and be more automated. Lifting common calls to templates and grids and design initializations to a superclass made the generator code more specific with less coding overhead to the designer.

By lifting all PDK-related template calls to the Orchestrator's PDK abstraction, the generator code no longer requires particular knowledge of the PDK to create- also possibly enabling generator codes.

We also integrated MAGIC VLSI into the Orchestrator as a registered tool, allowing it to transform LAYGO2 designs into mag files handled hierarchically for every task with caching.

![](\images\2022-08-29-21-21-39.png)

### 2. [FiftyNifty Generators using LAYGO2 and virtuoso_template](https://github.com/Lawrence-lugs/MOSAIC-bootcamp-2022-student-generators)

#### Student Participants

After that, the students went on creating LAYGO2+SKY130 generators for the basic two-transistor circuits from the FiftyNifty, and some other basic circuits. See repository here.

**LAYGO2+SKY130**

1. (Nifty 7) Current Mirror (Kevin)
2. (Nifty 1) Inverter (Lawrence)
3. (Nifty 8) Differential Pair (Ryan)
4. (Nifty 14) Transmission Gate (Lawrence)
5. **NOT NIFTY** 2to1MUX (Lawrence)
6. Seonghyun's 19/50 Nifty Generators (Seonghyun)
   * (Nifty 1) Inverter
   * (Nifty 3) Tie-Zero
   * (Nifty 5) NAND
   * (Nifty 6) NOR
   * (Nifty 7) Current Mirror
   * (Nifty 8) Differential Pair
   * (Nifty 9) Source Follower
   * (Nifty 10) CS Amp
   * (Nifty 11) CS Cascode Amp
   * (Nifty 12) Cascode CG Amp
   * (Nifty 13) CG Amp
   * (Nifty 14) TGate
   * (Nifty 15) 2to1MUX
   * (Nifty 17) CS Amp with Diode Load
   * (Nifty 18) Folded CS Amp with Diode Load
   * (Nifty 19) ClassB PushPull Follower
   * (Nifty 20) Degenerated CS Amp
   * (Nifty 21) Variable Degeneration CS Amp
   * (Nifty 24) PN Bias Voltage Generator

**AnalogBase+cds_ff_mpt (finfet tech)**

1. (Nifty 1) Inverter, NAND Gate (Taeho)
2. NOR Gate (Seonghyun)
3. Tri-state Inverter, NAND Gate (Youngmin)
4. (Nifty 24, 25) PN, Stable Voltage References (Lawrence)
5. NAND Gate, (Nifty 7, 1) Diff Pair, Inverters (Ryan)
6. (Nifty 7) Sophisticated Current Mirrors (Kevin)

![](\images\2022-08-29-21-31-19.png)

### 3. KLayout and LAYGO2 

#### Ryan Antonio, Kevin Pizarro

By using the LAYGO2 package and framework inside KLayout's scripting environment, students managed to enable KLayout to show previews of LAYGO2 designs and allow it to export to GDS, which may eventually allow a complete LAYGO2 workflow to be automated (say, with the Orchestrator, XSchem and netgen) inside KLayout.

![](\images\2022-08-29-21-07-21.png)

### 4. The open-source BAG2 Template (Temp Name)

#### Matthias Koefferlein, Thomas Parry

By replacing virtuoso-template's existing skill.py, which handles communication with Virtuoso, with a new handler, opensource.py, they were able to port BAG2's SKILL requests workflow to KLayout and XSchem instead.

```
gen make inverter_gen
```

This creates a GDS for KLayout, and a schematic file for XSchem

This enables the use of BAG2 with open-source tools paving the way for open-source IC development with analog generators.

![](\images\2022-08-25-14-58-47.png)

![](\images\2022-08-25-15-01-13.png)

## Bootcamp Experiences

Lawrence Quizon

> Before the bootcamp, I tried to learn using these analog generators by myself.  I found that most of them do not have satisfactory documentation, and have very high learning curves. In the bootcamp, since a lot of people with experience using (and developing) these generators firsthand, it very quickly closes the learning curve and gets you ready to use it for your own research.
> 
<!-- > For us in Microlab, the reusable analog generation paradigm is a very important tool for IC design research. With the enablement of this paradigm with open-source tools, which is a vision that MOSAIC has, it will also enable a lot of other Philippine universities to use analog generators, fostering cooperation. -->
>
> \[The bootcamp\] was kinda like a proto-conference on layout generation, for which everyone has different amounts of progress and different approaches and different software. It's a way to remap the progress in the heads of everyone who wants to work on these things.

Taeho Shin

> The most valuable discovery of this bootcamp is that all participants are professional in their own fields and inspired when they are working on enabling open-source IC design. I’m very glad to have the chances to teach LAYGO2, which is a powerful framework for programmatic IC design, to the participants of the bootcamp. Also, I could have learned about various perspectives of other participants on automatic analog IC design. Joining this bootcamp is definitely the turning point of my IC design experience.


Aquiles Viza

> This is very important for AC3E, because it is cooperation outside the bubble. It was very interesting to hear different POVs about the tools from people with different backgrounds (Digital, Software, Analog only, Layout generation people.)

Kevin Pizarro

> Before the Bootcamp I had only a little bit of knowledge about the analog generators or the vision that everyone is pursuing. It was with the presentation of Boris Murmann where I put my feet on the ground, and I realized what is needed and which is the chosen way, changing the paradigm. It was super interesting begin with not knowing LAYGO2, even LAYGO, to learn the basis and how to use LAYGO2, investigate and learn other tools like KLayout or about Analog Base, understand the MOSAIC ambition and look for the convergency of a common solution, not to reinvent the wheel.
>
> Thank you to everyone that participate in the Bootcamp, to NiftyLabs for teaching us about the mighty tool that is LAYGO2, to Ryan and Lawrence for been so supportive and great teammates, to Fatemeh and Martin for teaching us about Analog Base,to Matthias for the brilliant tool that is KLayout, to Infineon team with MOSAIC and to Mirjana that makes this Bootcamp possible, this amazing experience. In summary, thank you all, everyone contributes something to this. I hope that we can keep collaborate and help to each other, following the vision of the automated IC design, from a programmatic perspective.

Ryan Antonio

>The MOSAIC bootcamp was an an inspiring event! It had a diverse collaboration between universities and indusries from different countries.
>
>I actually learned and experienced more than what I anticipated. It was inspiring to see how professionals help each other in developing an open-source community. The tools are free, the knowledge are free, and you get an abundant amount of support. This is the step forward to make programmatic IC design a part of the current college curriculums. On top of that, I am convinced that programmatic IC design improves the productivity of a designer. I am not really good with layouts but after this bootcamp, I could immediately draw and see my circuits after coding the floorplan in a few mins! This truly was a great experience. I will never forget this opportunity 🙂

Youngmin Oh

>As an analog circuit designer I had only a little experience about design automation and programming languages. It was a wonderful opportunity where I could learn more about different open-source and design automation tools.

Seonghyun Park

>This bootcamp is one step closer to open-source analog IC design. Although good open-source software has already been developed, the absence of documentation makes it hard for analog circuit designers to use them. In addition, it's more difficult to access them as the community is not active, unlike the software field. I have learned about different perspectives as well as approaches for research from bootcamp participants with different background and experience.

## Tutorials and notes

{% assign mosaicdocus = site.pages | where_exp: "item" , "item.path contains 'MOSAIC Bootcamp Documentation/notes'"%}
{% for page in mosaicdocus %}
   <h4><a href='{{page.url}}'> {{page.title}} </a></h4>
{% endfor %}
