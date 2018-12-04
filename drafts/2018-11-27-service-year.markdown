---
layout: post
title: "Expanding service years for young Americans"
img: ../assets/img/posts/08-service-year/08-sy-hero.jpg
date: 2018-11-27
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
## <span style="color: #FA6695;">*Before we begin*</span>
<span style="color: #FA6695;">
  *The full case study will be upon us soon! In the meantime, enjoy this brief showcase of a few things I've been apart of during my time on the Service Year Exchange project. Expect updates early 2019.* 🖍
</span>
<br>
<br>
# <span style="color: black;">Introduction</span>
## <span style="color: black;">Project overview</span>
[Service Year Exchange](https://serviceyear.org/) is a platform which serves as a marketplace to connect motivated young people looking to develop real-world skills with non-profit organizations offering hands-on service opportunities. Complete with organization and corps member profiles, robust search capabilities, and custom dashboard interfaces, our interdisciplinary team continues to build new features and optimize the platform in partnership with our hands-on client team.

The platform currently features and serves over 45,000 service opportunities, over 100,000 corps members, and hundreds of non-profit organizations across the country.
<br>
<div class="fluidbox-container w-100">
  <a href="https://media.giphy.com/media/18U2ZCtNEB5gijHLJx/giphy.gif">
    <img src="https://media.giphy.com/media/18U2ZCtNEB5gijHLJx/giphy.gif" alt="" width="624px" />
  </a>
</div>
<p class="tc f6">The chapter selection screen.</p>

## <span style="color: black;">My role</span>
Since I've joined ISL—I've been the lead UX designer on a few different key initiatives for the Service Year platform:

1. A feature that matches different audience members with specialized service year opportunities in the appropriate context
2. Rebuilding the information architecture to promote member conversion and satisfy growing stakeholder concerns
3. Update and maintain a living design system and style guide to facilitate a more efficient workflow
<br>
<br>
<span class="mb4 f2 tc mid-gray db nt3">. . .</span>

# <span style="color: black;">Matching members with service</span>
## <span style="color: black;">Discovery</span>
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
Multiple rounds of wireframes soon followed. With the basic app flow already planned, most of our time was spent iterating on the learning modules, trying to strike the right balance between "inform" & "assess" content—and any key interactions needed to convey our ideas. This was an arduous process that eventually resulted in six templates that could be combined and used interchangeably with different types of content. For example:

### <span style="color: black;">Inform</span>
The three templates for all informative content:
* Rotating carousel for imagery and written content
* Video/animation module with transcribed written content
* Long-form scrolling view for written content only.
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-inform.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-inform.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">The Instruct and Assess framework helped us determine where to place instructional content and when to follow up with quizzes and real world application.</p>

### <span style="color: black;">Assess</span>
The three templates for all assessment content:
* Single answer presented in a boolean format (true or false)
* Single answer presented in a multiple choice format
* Multiple answer option in a drag & drop format
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-assess.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-assess.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">The Instruct and Assess framework helped us determine where to place instructional content and when to follow up with quizzes and real world application.</p>

## <span style="color: black;">Building a CMS</span>
Running in tandem with our design efforts, the dev team was hard at work at building a Wordpress based CMS—enabling IRC to update and add new orientation content to the app over time. The system needed to be flexible enough to allow for multiple user groups with varying knowledge and permission levels, but provide enough rigidity and parameters to ensure content is always in it's "most ideal" form before being pushed to the app.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-cms.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-cms.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Creating an assessment question through the CMS.</p>

## <span style="color: black;">Beauty and accessibility</span>
We began by branding and naming the application, landing on Settle In – a reminder to the user that the app is meant to be a comforting mechanism to own and understand your resettlement process. From there we designed a universal iconography set, which mimicked airport way-finding, and an accessible color scheme, devoid of colors representative of any particular nation.
<br>
<div class="fluidbox-container w-100 w-50-ns fl pr1-ns pb1 pb0-ns">
  <a href="../assets/img/posts/07-settlein-app/07-color.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-color.jpg" alt="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pl1-ns pb1 pb0-ns">
  <a href="../assets/img/posts/07-settlein-app/07-design-system.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-design-system.jpg" alt="" />
  </a>
</div>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-design-system-2.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-design-system-2.jpg" alt="" />
  </a>
</div>
<div class="cf"></div>
<p class="tc f6 pb3">As the app scales and more chapters are added—our system of shapes and colors could be combined in hundreds of different ways to create a unique identity.</p>

## <span style="color: black;">Supporting multiple languages</span>
SettleIn needed to support multiple languages (and even multiple dialects) spanning across the Arabic and Latin alphabets. We needed to ensure that our translated content was rendered correctly and easily legible—especially for elderly refugees and refugees with disabilities. [Google has been hard at work](https://design.google/library/modernizing-arabic-typography-type-design/) at digitizing the Arabic alphabet and bringing it into the modern age, so, naturally, we pulled a ton of inspiration from them before settling on [Noto Sans](https://fonts.google.com/specimen/Noto+Sans) as our type of choice.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-rtl.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-rtl.jpg" alt="" />
  </a>
</div>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/07-settlein-app/07-multiple-languages.jpg">
    <img src="../assets/img/posts/07-settlein-app/07-multiple-languages.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">The final iteration of the language selection process—part of the onboarding flow.</p>

## <span style="color: black;">Bi-directional design</span>
Rendering the alphabet was only half of the equation. To fully account for all English & Arabic speakers, we needed to create a design system that enabled both left-to-right and right-to-left reading across the app and integrated curriculum.

We worked closely with IRC to develop a set of rules governing line-length, font size, and when to use formal vs. informal translations. We also integrated animated tool tips that added contextual hints as a fallback, prompting users using motion (rather than language) to access Settle In’s features.
<iframe src="https://player.vimeo.com/video/274367353" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<br>

# <span style="color: black;">Phase 2</span>
## <span style="color: black;">Next steps</span>
We just wrapped up a ton of usability testing and are gearing up for Phase 2! We're making a lot of UI refinements, adding more languages, and breaking into the desktop space with a SettleIn web app! Stay tuned for updates in early 2019.
<br>
<br>
