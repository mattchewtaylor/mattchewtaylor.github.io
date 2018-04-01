---
layout: post
title: "Case study redux: Etsy Marketplace"
img: ../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-hero.png
date: 2018-02-19
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
  *This is an older case study that I completed during my time at General Assembly's UX Design Immersive. Having been in product design for some time now, I thought it would be a fun and useful exercise to look back and revisit my process to see what could have been improved. This is the original, unabridged case study from two years ago – any text in pink are my present day reflections and insight.* 🖍
</span>
<br>
<br>

# <span style="color: black;">Introduction</span>
## <span style="color: black;">Project overview</span>
Etsy provides a place for makers to sell their goods and reach a large audience. There are many talented individuals who are specially skilled in certain areas. Customers can search for the items they’re looking for, but sometimes they have a product in mind that they’d like created for them. My team created a concept that allows customers to post product requests and receive quotes from various artisans, as well as promote healthy collaboration between the two parties.
<br>
<br>

## <span style="color: black;">The mission</span>
As a global marketplace leader that specializes in handmade items, Etsy wants to broaden its customer base even further through custom services. Our team was given 2 weeks to design a feature set and accompanying UI that allows Etsy users to post custom order requests and receive quotes from suitable Etsy shop owners. The feature set should be able to seamlessly integrate with Etsy's current website and mobile app.
<br>
<br>

<span style="color: #FA6695;">
  *Already a pretty lofty goal, the Etsy website and mobile app have vastly different navigational structures, layouts, and cater to different user needs.* 🖍
</span>
<br>
<br>

## <span style="color: black;">Considerations</span>
There are many important aspects our team needed to take into consideration before beginning our research, and even more afterwards.
1. What sort of time constraints should be placed on requests
2. How can we help customers brainstorm and ideate with the artisan
3. How do we ensure quality hits and not promote spam
4. How will this compete with existing services in the industry
<br>
<br>

## <span style="color: black;">My role</span>
* Preliminary discovery
* User research
* Wireframing
* Usability testing
<br>
<br>

# <span style="color: black;">Research</span>
## <span style="color: black;">Gathering data</span>
My team began the research phase by sending out a few surveys to Etsy customers and shop owners to get a better understanding of their needs and pain points. We then expanded our audience and started to poll people that have requested custom goods (or commissioned custom artwork) in the past, whether through an online service or a local shop.
<br>
<br>
## <span style="color: black;">User interviews</span>
After conducting the surveys, we wanted to get more qualitative data via user interviews. We sat down with a few of our respondents and talked through the current process of requesting custom orders. We also wanted to learn more about the collaboration efforts between buyer and seller. Whilst my team compiled all our user data, I went online to the official Etsy forums and opened up further discussions about the current state of custom ordering.

Some excerpts from our interviews:
### <span style="color: black; font-weight: 600;">Q:  Can you briefly describe your most recent experience with a custom order?</span>
*A:  "I wanted to get my wife a necklace with her grandmothers name engraved on it, along with her birthstone. I spent a consierable amount of time searching for an Etsy shop that specialized in custom jewelry and requested a custom order through them."*

### <span style="color: black; font-weight: 600;">Q:  What aspects were frustrating about your ordering process?</span>
*A:  "Time was the big one for me.  Between searching for the right jeweler and going back and forth trying to get the perfect necklace... I just felt exhausted by the time it was finally finished."*

### <span style="color: black; font-weight: 600;">Q:  How did you collaborate with the shop owner? Was there any brainstorming involved?</span>
*A:  "Mostly through email, I sent over some pictures of something similar and we just took it from there."*
<br>
<br>

# <span style="color: black;">Telling the story</span>
## <span style="color: black;">User personas</span>
We sorted our data from the research phase into two main archetypes; the buyer and the artisan. After identifying patterns in the responses we received, we then used the two personas to craft a pair of user stories.
<br>
<div class="fluidbox-container w-100 w-50-ns fl pr0 pr2-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-persona-sarah.png" title="Persona">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-persona-sarah.png" alt="" title="Persona" />
  </a>
  <p class="tc f6 mt2 pb3">The buyer persona, Sarah.</p>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pl0 pl2-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-persona-tim.png" title="Persona">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-persona-tim.png" alt="" title="Persona" />
  </a>
  <p class="tc f6 mt2 pb3">The artisan persona, Tim.</p>
</div>

### <span style="color: #99CCFF;">Buyer</span>
Sarah is a 23 year old elementary school teacher that is preparing to start a new school year. She wants to order custom name blocks for her class to help them with seating arrangements and with learning each other's names. Class starts next month so she needs to ensure the blocks will be error free and ready on a tight deadline.

### <span style="color: #CC6666;">Artisan</span>
Tim is business analyst by day, but a talented woodworker by night. He's looking to grow his woodworking business in hopes that one day he can turn into a full time job. Tim is a busy guy so he needs to be able to communicate with his customers on the go. He's always on the hunt for new and exciting projects.
<br>
<br>

<span style="color: #FA6695;">
  *Overall, I think these were successful personas. We didn't really have enough research for fully developed, bias free archetypes — but they address two categories of people that have significantly different motivations and needs when using the product.* 🖍
</span>
<br>
<br>

## <span style="color: black;">User flows</span>
Using the personas and user stories, we created a set of flow diagrams to illustrate the optimal "happy" path for each archetype. These diagrams served as a base for our wireframes, and allowed us to start thinking about any edge cases that we would need to design for.
<br>
<div class="fluidbox-container w-100 w-50-ns fl pr0 pr3-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-buy-flow.png" title="Buyer user flow">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-buy-flow.png" alt="" title="Buyer user flow" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pl0 pl3-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-sell-flow.png" title="Artisan user flow">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-sell-flow.png" alt="" title="Artisan user flow" />
  </a>
</div>
<div class="cf"></div>
<p class="tc f6">Left; the buyer flow. Right; the artisan flow.</p>
<br>
<span style="color: #FA6695;">
  *These user flows were a bit premature in my opinion. We should have spent more time analyzing both Etsy's website and mobile app before creating an optimal journey. The IA and navigation are quite different in both experiences and probably warrant additional flow diagrams that take this into consideration.* 🖍
</span>
<br>
<br>

# <span style="color: black;">Designing the experience</span>
## <span style="color: black;">Sketching</span>
Once we felt confident in our user stories and flow diagrams, I lead the design effort by sketching out a few initial layouts for sending and receiving project requests. On the buyer side, we needed to develop a way to assist the users in figuring out exactly what they want, even without any prior knowledge of the creation process. To make matters even more complex, we had to figure out a way to match the product request with suitable artisans who could provide accurate quotes.
<br>
<div class="fluidbox-container w-100 w-50-ns fl ph0 pr1-ns pb1 pb0-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-sketch-1.png" title="Sketch">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-sketch-1.png" alt="Sketch" title="Sketch" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl ph0 ph0 pl1-ns pb1 pb0-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-sketch-2.png" title="Sketch">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-sketch-2.png" alt="Sketch" title="Sketch" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl ph0 pr1-ns pb1 pb0-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-sketch-3.png" title="Sketch">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-sketch-3.png" alt="Sketch" title="Sketch" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl ph0 pl1-ns pb1 pb0-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-sketch-4.png" title="Sketch">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-sketch-4.png" alt="Sketch" title="Sketch" />
  </a>
</div>
<div class="cf"></div>
<p class="tc f6 pb3">Initial layout iterations for project listings and request screens.</p>

## <span style="color: black;">Wireframing</span>
After getting some ideas down on paper, we began the wireframing process with the product request. We needed to design a method that allows the buyer to describe what they want in full detail, or guide them through the process if they're not quite sure. We settled on a hybrid form that first asks a series of basic questions to help categorize the request (product type, budget, shipping location, etc), then proceeds into more open ended questions to allow the buyer to add their personal touch (who is this for, what is this for, etc).
<br>
<div class="fluidbox-container w-100 w-third-ns fl ph1 pb1 pb0-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-wireframe-annotated-1.png" title="Wireframe">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-wireframe-annotated-1.png" alt="" title="Wireframe" />
  </a>
</div>
<div class="fluidbox-container w-100 w-third-ns fl ph1 pb1 pb0-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-wireframe-annotated-2.png" title="Wireframe">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-wireframe-annotated-2.png" alt="" title="Wireframe" />
  </a>
</div>
<div class="fluidbox-container w-100 w-third-ns fl ph1 pb1 pb0-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-wireframe-annotated-3.png" title="Wireframe">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-wireframe-annotated-3.png" alt="" title="Wireframe" />
  </a>
</div>
<div class="cf"></div>

### <span style="color: black;">Reverse auction</span>
With the artisan flow, we elected to create a sort of "reverse auction" concept. After some initial testing, we found that simply matching buyers with artisans by the highest bidder methodology left too much room for spam, and favored the larger and more established Etsy shop owners.

We devised a system that allows the artisan to actively seek new project requests, and choose the requests that interest them the most. When an artisan has expressed interest in a project, we'll go ahead and open up the lines of communication so both parties can negotiate price and clear up any unanswered questions (we'll cover this in just a bit!).

Ultimately, we wanted this system to put both the buyer and artisan on the same level to ensure quality matches and provide the best experience for both sides.
<br>
<div class="fluidbox-container w-100 w-25-ns fl ph0 pr1-ns pb1 pb0-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-find-request-1.png" title="Wireframe">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-find-request-1.png" alt="Wireframe" title="Wireframe" />
  </a>
</div>
<div class="fluidbox-container w-100 w-25-ns fl ph0 ph0 pl1-ns pb1 pb0-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-request-listing-2.png" title="Wireframe">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-request-listing-2.png" alt="Wireframe" title="Wireframe" />
  </a>
</div>
<div class="fluidbox-container w-100 w-25-ns fl ph0 pr1-ns pb1 pb0-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-brief-overview-3.png" title="Wireframe">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-brief-overview-3.png" alt="Wireframe" title="Wireframe" />
  </a>
</div>
<div class="fluidbox-container w-100 w-25-ns fl ph0 pl1-ns pb1 pb0-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-project-accept-4.png" title="Wireframe">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-project-accept-4.png" alt="Wireframe" title="Wireframe" />
  </a>
</div>
<div class="cf"></div>
<p class="tc f6">Project overview/search > Project listing > Project brief > Confirmation.</p>
<br>
<span style="color: #FA6695;">
  *I stand by this design even today, but I've come to realize that this solution could still favor larger shop owners. Some of the more popular creators have multiple employees and a greater capacity to handle multiple orders. The reverse auction system does nothing to safeguard against this scenario, so I would want to test this hypothesis in depth and respond accordingly.* 🖍
</span>
<br>
<br>

## <span style="color: black;">Promoting collaboration</span>
Communication plays an essential role in this process. We can attempt to automate as much as possible using technology but when it comes to communicating abstract ideas, there's no better way than human to human contact. The current tool is a simple email service connected with your Etsy account, but we wanted to implement something a little more robust. Together, we designed a real time messaging feature integrated alongside the project brief that provides a clear communication path and serves as a hub for important notifications.
<br>
<div class="fluidbox-container w-100 w-50-ns fl pr0 pr2-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-message-1.png" title="Messaging screen">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-message-1.png" alt="" title="Messaging screen" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pl0 pl2-ns">
  <a href="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-message-2.png" title="Messaging screen">
    <img src="../assets/img/posts/03-case-study-revisited-etsy-marketplace/03-message-2.png" alt="" title="Messaging screen" />
  </a>
</div>
<div class="cf"></div>
<p class="tc f6 pb3">Messaging + quote notification.</p>

## <span style="color: black;">Prototype & testing</span>
We created a quick prototype in InVision and conducted a few rounds of user testing. We focused on the navigational structure and general user engagement throughout both the buyer and artisan flows. We took diligent notes and carefully listened to the feedback, iterating after every round. We kept the prototype in a low-medium fidelity state to cut down on design time and eliminate any visual bias. [View the prototype](https://invis.io/GN84O5HVB#/164678223_Find_Projects)
<br>
<br>

# <span style="color: black;">Conclusion</span>
## <span style="color: black;">Next steps</span>
Quite a bit actually. Our testing and feedback was positive throughout most stages of the feature set. We're headed in the right direction and have a solid MVP to begin scaling up to desktop size. Once the desktop versions have been tested and validated we can start to transition into higher fidelity comps and prototypes.
<br>
<br>

<span style="color: #FA6695;">
  *This theory makes sense on paper, but I think we failed to recognize just how different the mobile app and website experiences were (at the time). It wouldn't just be a matter of progressively enhancing the mobile prototype — but designing an entirely different structure altogether.* 🖍
</span>
<br>
<br>

The messaging feature is only scratching the surface of effective communication. We're giving two parties the necessary tools to collaborate, but we're not changing behavior. To solve this, we want to implement a system of checks and balances that allow the buyer to request timely status updates of their project. Ideally these updates should be in picture format for the most accurate representation of the current status. We feel this solution is a much closer step towards actively promoting collaboration.
<br>
<br>

<span style="color: #FA6695;">
  *Preach it.* 🖍
</span>
<br>
<br>

## <span style="color: #FA6695;">*Retrospective*</span>
<span style="color: #FA6695;">
  *More time and effort into researching the audience and establishing effective personas would have worked wonders for this project. I think talking to as many local shop owners as possible and sitting in on actual requests and making note of the dialogue between parties would have been eye opening.*
  <br>
  <br>
  *Our team also spent too much time under the mobile constraint. We incorporated a lot of lean UX principles and had more than enough time to move into desktop design. We were so focused on getting the concept to work at the smallest possible size that we might have missed an otherwise obvious opportunity on a larger scale.* 🖍
  </span>
