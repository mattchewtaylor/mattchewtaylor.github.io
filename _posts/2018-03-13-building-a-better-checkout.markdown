---
layout: post
title: "Building a better checkout"
img: ../assets/img/posts/04-building-a-better-checkout/placeholder.png
date: 2018-03-12
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
## <span style="color: black;">Note on terminology</span>
The “checkout” process – where users choose a plan and invest their money accordingly – is the final touchpoint before officially becoming an investor on the [company] platform. Internally, we try our hardest to refrain from calling it a “checkout” because it’s not technically (or even legally) correct – but it shares many similarities with the typical end-stage flow you would see with any normal ecommerce site. For brevity, I will still refer to this feature as a “checkout” throughout this case study.
<br>
<br>

# <span style="color: black;">Introduction</span>
## <span style="color: black;">Project overview</span>
The checkout flow was one of the few parts of the platform that suffered from the age old “if it ain’t broke don’t fix it” mindset. It was one of the longest standing set of pages to go untouched throughout the many different product pivots. It did its job of taking a motivated investor and guiding them through the process of setting up an account and investing their money. But, could we make it better?
<br>
<br>
At the time of this project, we were preparing to launch the goal based investment plans – a pivot that set the underlying skeleton for what would become [company] today. The design team was tasked to validate and address a few usability concerns (from stakeholders and users) with the old investor flow and bring it into the present day along with the rest of the product — making sure to incorporate the new goal-based plans.
<br>
<br>

## <span style="color: black;">Project goals</span>
The main objective was to redesign the checkout to incorporate the new goal-based investment plans and to improve the overall conversion from *user* to *investor*. This could be broken down into several smaller tasks such as:

1. Reduce the number of interactions taken from plan selection to checkout
2. Address any behavioral and usability issues on pages with higher abandonment rates
3. Remove legacy code
4. Test new technologies to expedite user input
5. Update the visual look and feel
6. Document new additions to the pattern library
<br>
<br>

## <span style="color: black;">My role</span>
* Metric analysis
* Ethnographic research
* Wireframing
* Prototyping & testing
* High-fidelity design
<br>
<br>

# <span style="color: black;">Research: Part I</span>
## <span style="color: black;">Audit</span>
An audit was performed on the current checkout flow, paying special attention to the length of the overall flow (amount of pages) and the unique interactions on each page. This was also the time to make note of any legacy elements that were being cut to pave the way for the new product.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/placeholder.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/placeholder.png" alt="" />
  </a>
</div>
<p class="tc f6">Placeholder</p>

## <span style="color: black;">Analytics</span>
Additionally, we turned to our Google Analytics and Mixpanel Segmentation to look for any patterns of concern, and to provide a bit more context behind potential user behavior in the checkout flow.
<br>
<br>
Some questions we were asking ourselves:
1. From where (what source) did they enter the checkout flow?
2. How long was the average time to completion (invest)?
3. How long were people spending on each page?
4. Which pages had the highest abandonment rate?
5. At what point did people reach out for help? Why?
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-analytics-2017-24hrs.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-analytics-2017-24hrs.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Typical conversion rate for a 24 hour period under the old checkout flow.</p>

### <span style="color: black;">Key takeaways</span>
We noticed an extremely high abandonment rate on the first step of checkout (choosing citizenship and country of residence) and the Payment step (connecting a bank account). Additionally, we saw fairly high view times on the Acknowledgements step and Account Details step, as well as an average completion time of about 8 minutes.

We can make a lot of different assumptions using the analytics but I wanted to check for any correlation between our data and the customer support cases that came through our feedback channels. Doing this helped our team dig into the *why* behind the *what* and helped us set the stage for a few user interviews.
<br>
<br>

## <span style="color: black;">User interviews</span>
Going through our support tickets gave us a potential route into more in-depth qualitative feedback sessions. We often found that the “customers” motivated enough to enter the checkout flow *and* contact us with questions/feedback were more than willing to discuss their concerns in a formal follow up through email or phone. This gave us more clarity around some of the problems that couldn’t readily be answered by analytical data alone.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/placeholder.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/placeholder.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Placeholder</p>

# <span style="color: black;">Analysis</span>
## <span style="color: black;">Synthesizing the data</span>
After about a week of research and interviews with potential investors, the big ticket problem areas started to reveal themselves. We distilled the research and feedback sessions into the following:
<br>

### <span style="color: black; font-weight: 600;">Length... was long</span>
Coming in at 7 pages – the checkout flow was long when compared to most other ecommerce sites (not a great comparison, but it’s what people are used to). When you add the fact that each page has an average of 6 interactions, it felt even longer.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-old-flow-1-highlight.jpg">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-old-flow-1-highlight.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">7 step progress bar can be intimidating for some.</p>

### <span style="color: black; font-weight: 600;">Acknowledgements were tedious</span>
For legal reasons, we have numerous different terms and acknowledgements the investor must agree to before investing. However, the old method of a *billion* separate checkboxes followed by a digital signature prompt at the end (think DocuSign) wasn’t doing us any favors.
<br>
<div class="fluidbox-container w-100 w-third-ns fl ph1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-old-flow-2-highlight.jpg" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-old-flow-2-highlight.jpg" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-third-ns fl ph1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-old-flow-3-highlight.jpg" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-old-flow-3-highlight.jpg" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-third-ns fl ph1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-old-flow-4-highlight.jpg" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-old-flow-4-highlight.jpg" alt="" title="" />
  </a>
</div>
<div class="cf"></div>
<p class="tc f6 pb3">An average of 13 acknowledgements + signature for a typical investment.</p>

### <span style="color: black; font-weight: 600;">Connecting a bank wasn’t easy easy as it should be</span>
Our legacy “Payment” step required the investor to add their bank account manually via a routing and account number. Not to mention we required an unnecessary confirmation on the account number, forcing the user to input the same information twice.
<br>
<div class="fluidbox-container w-100 w-50-ns fl pr0 pr2-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-old-flow-5-highlight.jpg">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-old-flow-5-highlight.jpg" alt="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pl0 pl2-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-old-flow-6-highlight.jpg">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-old-flow-6-highlight.jpg" alt="" />
  </a>
</div>
<div class="cf"></div>
<p class="tc f6 pb3">No one wants to find their checkbook or log in to their account for these numbers. Manually typing and re-typing is also frustrating and unnecessary.</p>

### <span style="color: black; font-weight: 600;">Editing the initial contribution was a hassle</span>
Because the amount to invest (we call that an “initial contribution”) was chosen beforehand in an earlier screen that is NOT part of the checkout flow – there wasn’t an easy way to edit and change the values without exiting and restarting the process. Annoying for sure.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-old-flow-7-highlight.jpg">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-old-flow-7-highlight.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Restarting the whole process just to change the contribution led to higher abandonment rates.</p>

### <span style="color: black; font-weight: 600;">Emotions ran wild</span>
Parting with your hard earned money is never easy, and investing on our platform was no different. To make matters worse, this wasn’t just some purchase that could be returned and refunded within a few days if you weren’t satisfied. This was a rather illiquid (5+ years) investment – with penalties on your capital for early withdrawal. Didn't exactly inspire confidence.
<br>
<br>

# <span style="color: black;">Research: Part II</span>
## <span style="color: black;">Competitor survey</span>
With some time to spare, I took to the internet to perform a quick analysis on a few direct and indirect competitors in the fintech space. I focused on heuristics such as:
1. How easy / how much time did it take to accomplish my goal (of investing)?
2. Did the checkout process keep me motivated and excited to continue?
2. Was the navigation and page layout consistent and easy to understand?
3. Were there feedback channels? Were they discoverable? Useful?
4. What was the primary tone and voice throughout my interactions? How did I feel?
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-comp-analysis-overview.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-comp-analysis-overview.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Competitor survey with direct (green) and indirect (blue) competitors.</p>

# <span style="color: black;">Analysis</span>
## <span style="color: black;">Synthesizing the data</span>
There were a lot of things each competitor did well and... not so well. Throughout each experience, however, a few things remained fairly consistent across the board:
<br>

### <span style="color: black; font-weight: 600;">Security was front and center</span>
Great care was taken to ensure the user felt comfortable and in control. Through the use of voice, tone, and visual iconography, the UI's were able to communicate safety and security during sensitive input steps. A must for any financial service.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-comp-analysis-security.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-comp-analysis-security.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">256 bit encryption and "bank level" security were plastered everywhere.</p>

### <span style="color: black; font-weight: 600;">A little personality went a long way</span>
Great care was taken to ensure the user felt comfortable and in control. Through the use of voice, tone, and visual iconography, the UI's were able to communicate safety and security during sensitive input steps. A must for any financial service.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-comp-analysis-personality.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-comp-analysis-personality.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Placeholder</p>

### <span style="color: black; font-weight: 600;">Forms are still a necessary evil</span>
Those pesky input forms. We all love to hate them. Many financial services are plagued with long forms requiring sensitive information. It's just the way it works when dealing with money and no one has appeared to make any significant stride in solving it.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/placeholder.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/placeholder.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Placeholder</p>

### <span style="color: black; font-weight: 600;">Not being afraid of the big asks</span>
Many institutions required a connected bank account in < 3 pages. Some even lead with the ability to connect your bank account using a third party API. Much earlier than I would have expected. This got the team thinking about various different integrations.
<br>
<br>

## <span style="color: black;">Creating a user flow</span>
We concluded our research phase with an updated user flow to serve as base for future wireframing and prototyping. The main goal here was to reduce the number of pages and interactions on each page. This flow was expected to evolve over time as we received feedback on the prototype.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-checkout-flow-1.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-checkout-flow-1.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Final iteration of the new user flow.</p>

# <span style="color: black;">Designing the experience</span>
## <span style="color: black;">Creating the MVP</span>
These initial wireframes were used as a way to establish a general direction for the UI layout and gain buy-in from stakeholders to explore the proposed features – such as a third party service to help users connect their bank accounts using their login credentials (reducing friction). Or a service that provides a live chat for immediate assistance throughout the flow (comforting the user). I’ve found that I have more productive conversations and a greater chance at buy-in when these conversations have a rough visual concept attached to them. By the end, the MVP looked something like this:
* 5 or 6 screens max
* Automatic bank account connection (manual option as back-up)
* Live chat
* Auto fill input with cookies and/or Plaid
* Editable investment amount from inside the flow
* Updated voice, tone, and visual identity
<br>
<br>

## <span style="color: black;">Planning</span>
With the green light from engineering and product on an MVP direction, I established a timeline and sprint schedule before iterating on any further deliverables. The goal was to have a validated prototype ready for testing by the end of week two. This timeline was a little tight (especially considering we had more research to do surrounding future API integrations), but doable.
<br>
<br>

## <span style="color: black;">Whiteboarding</span>
At this point I had a lot of different ideas on potential features and needed to get a few down on paper to clear my head. I organized a quick design studio with a few other designers and together, we sketched out different layouts and feature ideas that addressed the research and analysis. After a quick round of feedback we were able to narrow it down to a few different versions that would serve as a base for low-fi wireframes.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-whiteboarding.jpg">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-whiteboarding.jpg" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Placeholder</p>

## <span style="color: black;">Sketching</span>
I sketched down a few of the main takeaways from the design studio on paper to use as a reference. Because our whiteboarding session was fairly robust, I didn't want to spend too much time regurgitating the details that were already covered. Once I felt I had what I needed, I moved into digital.
<br>
<br>

## <span style="color: black;">Wireframing</span>
Armed with a validated user flow and a lot of doodles, I started on a round of digital wireframes. This is where I started to map out the core MVP features in depth – exploring things like Plaid and automatically connecting a bank account, where and how to choose an initial contribution, and the placement of a live chat instance. I gathered feedback on a rolling basis and was able to iterate through different versions relatively quickly.
<br>
<div class="fluidbox-container w-100 w-50-ns fl pr1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-wf-1.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-wf-1.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pl1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-wf-2.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-wf-2.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pr1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-wf-3.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-wf-3.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pl1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-wf-4.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-wf-4.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pr1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-wf-5.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-wf-5.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pl1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-wf-5-modal.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-wf-5-modal.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 fl pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-wf-7.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-wf-7.png" alt="" title="" />
  </a>
</div>
<div class="cf"></div>
<p class="tc f6 pb3">The old checkout flow.</p>

## <span style="color: black;">Prototyping</span>
Opting for speed and simplicity, the initial prototypes were built from the wireframes using Sketch and InVision. InVision was the perfect tool for the job here as it allowed us to pass the prototype around the office and to friends and family for quick, asynchronous feedback. We were mainly validating the condensed flow (when compared to the old version) and testing for any glaring usability issues.
<br>
<br>

## <span style="color: black;">High fidelity design</span>
This prototyping cycle went through a couple rounds of iterations before leading up to the final sprint, where we jumped into high fidelity. At this point, most of the high level usability concerns had been addressed, and the engineering groundwork had been laid out in preparation for the overhaul. I made sure to utilize as many components from our already-built pattern library as much as I could, as well as documenting all potential new additions to be discussed and approved out of band.
<br>
<div class="fluidbox-container w-100 w-50-ns fl pr1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-hf-1.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-hf-1.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pl1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-hf-2.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-hf-2.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 fl pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-hf-3.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-hf-3.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 fl pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-hf-4.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-hf-4.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pr1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-hf-5.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-hf-5.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 w-50-ns fl pl1 pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-hf-5-modal.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-hf-5-modal.png" alt="" title="" />
  </a>
</div>
<div class="fluidbox-container w-100 fl pb1 pb0-ns">
  <a href="../assets/img/posts/04-building-a-better-checkout/placeholder.png" title="">
    <img src="../assets/img/posts/04-building-a-better-checkout/placeholder.png" alt="" title="" />
  </a>
</div>
<div class="cf"></div>
<p class="tc f6 pb3">Placeholder</p>

## <span style="color: black;">Screen first</span>
About 80% of our investor conversion happens on a desktop device, so designing for larger screens was the priority during this initiative. However, by utilizing our component-based library, being cognizant of our breakpoints, and keeping the flow contained to two columns — we were able to create a clean experience on all screen sizes straight out of the box.
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/04-responsive-breakpoints.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/04-responsive-breakpoints.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Placeholder</p>

### <span style="color: black; font-weight: 600;">Plaid bank grid</span>
Plaid bank grid
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/placeholder.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/placeholder.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Placeholder</p>

### <span style="color: black; font-weight: 600;">Initial contribution</span>
Initial contribution
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/placeholder.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/placeholder.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Placeholder</p>

### <span style="color: black; font-weight: 600;">Live chat</span>
Live chat
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/placeholder.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/placeholder.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Placeholder</p>

### <span style="color: black; font-weight: 600;">Smarter inputs</span>
An updated user flow was created to serve as base for wireframing and prototyping. The main goal here was to reduce the number of pages and interactions on each page. This flow was expected to evolve over time as we received feedback on the prototype.
<br>
<br>

## <span style="color: black;">Speccing for development</span>
Once the team felt comfortable with the direction, I drafted up some (minimal) spec documents to be passed off to front-end. I only had to document a few new additions, as most of the flow was designed using pre-existing components.
<br>
<div class="fluidbox-container w-100">
  <a href="../assets/img/posts/04-building-a-better-checkout/placeholder.png">
    <img src="../assets/img/posts/04-building-a-better-checkout/placeholder.png" alt="" />
  </a>
</div>
<p class="tc f6 pb3">Placeholder</p>

## <span style="color: black;">Testing</span>
The original plan was to set up a staging server for user testing when development started nearing the end stages – but due to the sensitive nature of the information required during checkout (social security, date of birth, bank account login, etc), we opted for a smaller series of gradual releases in our production environment. As of writing this case study, the checkout is still being tested with roughly 10% of our user base.
<br>
<br>

## <span style="color: black;">Results</span>
Challenges
<br>
<br>

## <span style="color: black;">Next steps</span>
Next steps
<br>
<br>

## <span style="color: black;">Retrospective</span>
Retro
<br>
<br>

<!-- ### <span style="color: black; font-weight: 600;">Plaid</span>
One of the API integrations being considered was a service called Plaid. Plaid provides a technology layer that allows users to connect their bank accounts through their online login credentials. They also provide additional services centered around auto-filling input fields (such as name and address) based on information on file with the connected account. Many of the financial services I looked at during the competitive analysis used Plaid or a similar service to expedite the payment step and I found the experience to be quite enjoyable. I knew this would be a significant engineering effort, but it was something I definitely wanted to explore for this project.
<br>

### <span style="color: black; font-weight: 600;">Olark</span>
Live chat was another requested feature on the table. The last few steps leading up to investment are where we normally see the most pressing questions and highest abandonment rates. Offering immediate assistance to address any critical concerns makes total sense.
<br>
<br>
-->
