---
layout: post
title: "SettleIn App"
img: ../assets/img/posts/07-settlein-app/07-settlein-hero.png
date: 2018-11-20
category: Case study
permalink: /writing/:title
excerpt_separator: <!--excerpt-->
custom-css:
  - post
  - fluidbox.min
custom-js:
  - jquery.fluidbox.min
---
<!--excerpt-->
# <span style="color: black;">Introduction</span>
## <span style="color: black;">Project overview</span>
Despite the urgency of the matter, the refugee resettlement process often consists of months and months of waiting, hours of preparation, bottomless stacks of forms and materials, and countless interviews and appointments.

The *International Rescue Committee (IRC)* came to ISL looking for a digital solution that would bridge the gap between pre-departure and post-arrival refugee resettlement experiences, and increase comprehension around core cultural transition information. The result was [SettleIn](https://settlein.app/).
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-keynote-1.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-keynote-1.jpg" alt="" />
  </a>
</div>
<p class="tc f6">The chapter selection screen.</p>

## <span style="color: black;">The problem</span>
A key tenet of IRC’s cultural orientation (CO) program for refugees is self-sufficiency—but given the stress, complexities, and information overload that go along with the resettlement process, that vital information can be difficult to process and retain over time.

The refugee resettlement program lacks a digital orientation resource that would help refugee families acclimate to their new environment and access relevant CO materials any time on their preferred mobile device in order to accelerate their path to self-reliance.
<br>
<br>

## <span style="color: black;">The goal</span>
Effectively communicate and increase refugee comprehension around critical pre- and post-arrival resettlement information. My role during the project was to support the Sr. UX Strategist and interactive design team through all phases of discovery, research, design, and testing heading into future sprints.
<br>
<br>
<span class="mb4 f2 tc mid-gray db nt3">. . .</span>

# <span style="color: black;">Research</span>
## <span style="color: black;">Kick-off</span>
In order to thoughtfully approach the challenge at hand, we embarked on a comprehensive discovery phase that included interviewing and surveying stakeholders around the globe, comparative analyses, familiarizing ourselves with cultural orientation curriculum, and lots of research.
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-card-sort.jpeg">
    <img src="../assets/img/posts/07-settlein-app/07-card-sort.jpeg" alt="" />
  </a>
</div>
<p class="tc f6">A short brainstorming exercise that helped both teams prioritize orientation content and determine milestones for the project.</p>

## <span style="color: black;">Interviews & surveys</span>
We began with stakeholder interviews and CO surveys to define our research objectives and build consensus about what problems we’re focused on solving. This was the time for us to evaluate any assumptions around the project goals and for the team to gain insight into the efficacy and impact of the cultural orientation process and how it contributes to refugee’s ability to acclimate in their new environment.

This was a tag-team effort from both the ISL and IRC team so we needed to create a script that could be used asynchronously by multiple different people. [Here's an example](/assets/img/posts/07-settlein-app/07-stakeholder-script.pdf) of a script used during this process.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-cultural-survey.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-cultural-survey.jpg" alt="" />
  </a>
</div>
<p class="tc f6">Summary of a CO survey to help determine who spends the most time with refugees at various points in the resettlement process.</p>

### <span style="color: black;">Key takeaways</span>
We learned that an **internet connection could not be relied upon** and that many refugees **do not have access to a personal device**. We needed to ensure that the experience was available offline and that the app could track individual learning progress across multiple profiles.

Additionally, given the current social climate—we needed to be careful about **storing any personally identifiable information**.
<br>
<br>

## <span style="color: black;">Comparative analysis</span>
We carried out a comparative analysis to get a sense of the current landscape of digital products & services focused on cultural orientation and crisis relief. We needed to understand what other services were doing, how they were doing it, and who they were doing it for. When it came to the products themselves, we took stock of everything—supported languages, device platforms, geo-location services, security protocols, any personalization or gamification elements, and much more.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-comp-analysis.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-comp-analysis.jpg" alt="" />
  </a>
</div>
<p class="tc f6">Summary of a comparative analysis that looked at 8 different digital products associated with resettlement or crisis relief.</p>

### <span style="color: black;">Key takeaways</span>
Many apps needed to support a multitude of different languages and that was no different for us. Safeguarding against any translation mishaps and ensuring that content is **clear, concise, and communicated effectively across languages** became a priority.
<br>
<br>

## <span style="color: black;">Provisional personas</span>
We moved into a series of personas to build consensus around our intended audiences and their respective wants, needs, and frustrations. This was less of a design tool and more so an exercise that helped us summarize our findings from our stakeholder interviews and surveys. Our three main archetypes were refugees, CO trainers overseas, and case workers in the US.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-personas.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-personas.jpg" alt="" />
  </a>
</div>
<p class="tc f6">Some rough personas to help summarize our findings and build consensus.</p>

## <span style="color: black;">Synthesizing our findings</span>
Upon completion of the initial discovery phase, we arrived at a set of strategic insights that ultimately defined our UX and design direction for the entire product:
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-observations.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-observations.jpg" alt="" />
  </a>
</div>
<span class="mb4 f2 tc mid-gray db nt3">. . .</span>

# <span style="color: black;">Designing the experience</span>
## <span style="color: black;">Choosing a model</span>
One of first hurdles we needed to overcome was creating a framework for providing CO content to refugees and ensure knowledge was being retained and applied to real world scenarios encountered during the acclimation period. We used some the current methods employed by CO trainers and case workers in resettlement agencies as a jumping off point, but later [hit the books](https://www.amazon.com/Instructional-Design-Theories-Models-Overview/dp/0898592755/ref=asc_df_0898592755/?tag=hyprod-20&linkCode=df0&hvadid=312154648235&hvpos=1o2&hvnetw=g&hvrand=15249990192646968884&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9061285&hvtargid=pla-492656950516&psc=1) and took to the internet to research effective teaching/learning models.


After a bit of hallway testing, we implemented the [Tell, Show, Do, Apply](https://elearningindustry.com/tell-show-do-apply-the-anatomy-of-good-instruction) learning model as a lesson framework for its proven ability to facilitate repetition and help users retain information over time. The sheer simplicity and efficacy of the Tell, Show, Do, Apply model naturally lends itself to mobile app design. This framework served as our North Star when deciding how to approach content for our lessons.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-framework.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-framework.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">The Instruct and Assess framework helped us determine where to place instructional content and when to follow up with quizzes and real world application.</p>

## <span style="color: black;">Giving control the user</span>
To many, refugee resettlement is a sensitive, controversial process—especially from a privacy standpoint. Due to user confidentiality precautions, it was too risky to store personal information in the application. Instead, we made it easy for users to skip around to lessons that interest them or pick up where they left without having to log in.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-user-flow.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-user-flow.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">A user flow showcasing the intent to allow users to start, stop, and skip chapters at will but still maintain a sense of progress.</p>

## <span style="color: black;">Wireframes</span>
*Some stuff about wireframes*
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-wireframes.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-wireframes.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">🚀🌖</p>

## <span style="color: black;">Beauty and accessibility</span>
*Some stuff about high-fidelity*
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-design-system.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-design-system.jpg" alt="" />
  </a>
</div>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-design-system-2.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-design-system-2.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">🚀🌖</p>

## <span style="color: black;">Supporting multiple languages</span>
*Some stuff about languages*
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-rtl.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-rtl.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">🚀🌖</p>

## <span style="color: black;">Bi-directional design</span>
*Some stuff about RTL orientation*
<iframe src="https://player.vimeo.com/video/274367353" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<br>

## <span style="color: black;">Ensuring content delivery</span>
*Some stuff about the CMS*
<br>
<br>

# <span style="color: black;">Phase 2</span>
## <span style="color: black;">Additional languages & dialects</span>
*Some stuff about adding languages*
<br>
<br>

## <span style="color: black;">Usability testing</span>
*Some stuff about testing*
<br>
<br>

## <span style="color: black;">UI refinements</span>
*More screens*
<br>
<br>
