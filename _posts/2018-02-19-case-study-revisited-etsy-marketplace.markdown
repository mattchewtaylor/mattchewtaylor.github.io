---
layout: post
title: "Case study revisited: Etsy Marketplace"
img: ../assets/img/posts/01-introducing-my-blog/vol-1-hero.png
date: 2018-02-19
permalink: /writing/:title
excerpt_separator: <!--excerpt-->
---
<!--excerpt-->
Etsy provides a place for makers to sell their goods and reach a large audience. There are many talented individuals who are specially skilled in certain areas. Customers can search for the items they’re looking for, but sometimes they have a product in mind that they’d like created for them. My team created a concept that allows customers to post product requests and receive quotes from various artisans, as well as promote healthy collaboration between the two parties.
<br>
<br>
## <span style="color: black;">The mission</span>
As a global marketplace leader that specializes in handmade items, Etsy wants to broaden its customer base even further through custom services. Our team was given 2 weeks to design a feature set and accompanying UI that allows Etsy users to post custom order requests and receive quotes from suitable Etsy shop owners. The feature set should be able to seamlessly integrate with Etsy's current website and mobile app.
<br>
<br>
## <span style="color: black;">Considerations</span>
There are many important aspects our team needed to take into consideration before beginning our research, and even more afterwards.
* What sort of time constraints should be placed on requests
* How can we help customers brainstorm and ideate with the artisan
* How do we ensure quality hits and not promote spam
* How will this compete with existing services in the industry
<br>
<br>

## <span style="color: black;">My role</span>
* Preliminary discovery
* User research
* Wireframing
* Usability testing
<br>
<br>

## <span style="color: black;">Gathering data</span>
My team began the research phase by sending out a few surveys to Etsy customers and shop owners to get a better understanding of their needs and pain points. We then expanded our audience and started to poll people that have requested custom goods (or commissioned custom artwork) in the past, whether through an online service or a local shop.
<br>
<br>
## <span style="color: black;">User interviews</span>
After conducting the surveys, we wanted to get more qualitative data via user interviews. We sat down with a few of our respondents and talked through the current process of requesting custom orders. We also wanted to learn more about the collaboration efforts between buyer and seller. Whilst my team compiled all our user data, I went online to the official Etsy forums and opened up further discussions about the current state of custom ordering.

Some excerpts from our interviews:
> <span style="color: black; font-weight: 700;">Q:  Can you briefly describe your most recent experience with a custom order? </span>

> <span style="color: mid-gray;">*A:  "I wanted to get my wife a necklace with her grandmothers name engraved on it, along with her birthstone. I spent a consierable amount of time searching for an Etsy shop that specialized in custom jewelry and requested a custom order through them."* </span>

> <span style="color: black; font-weight: 700;">Q:  What aspects were frustrating about your ordering process? </span>

> <span style="color: mid-gray;">*A:  "Time was the big one for me.  Between searching for the right jeweler and going back and forth trying to get the perfect necklace... I just felt exhausted by the time it was finally finished."* </span>

> <span style="color: black; font-weight: 700;">Q:  How did you collaborate with the shop owner? Was there any brainstorming involved? </span>

> <span style="color: mid-gray;">*A:  "Mostly through email, I sent over some pictures of something similar and we just took it from there."* </span>

<br>
## <span style="color: black;">Telling the story</span>
We sorted our data from the research phase into two main archetypes; the buyer and the artisan. After identifying patterns in the responses we received we then used the two personas to craft user stories and flow diagrams.
<br>
<br>
#### <span style="color: black;">Buyer</span>
Sarah is a 23 year old elementary school teacher that is preparing to start a new school year. She wants to order custom name blocks for her class to help them with seating arrangements and with learning each other's names. Class starts next month so she needs to ensure the blocks will be error free and ready on a tight deadline.

#### <span style="color: black;">Artisan</span>
Tim is business analyst by day, but a talented woodworker by night. He's looking to grow his woodworking business in hopes that one day he can turn into a full time job. Tim is a busy guy so he needs to be able to communicate with his customers on the go. He's always on the hunt for new and exciting projects.
<br>
<br>
## <span style="color: black;">Designing the experience</span>
Once we felt confident in our user stories and flow diagrams, I lead the design effort by sketching out a few intial layouts for sending and receiving project requests. On the buyer side, we needed to develop a way to assist the users in figuring out exactly what they want, even without any prior knowledge of the creation process. To make matters even more complex, we had to figure out a way to match the product request with suitable artisans who could provide accurate quotes.
<br>
<br>
## <span style="color: black;">Wireframing</span>
After getting some ideas down on paper, we began the wireframing process with the product request. We needed to design a method that allows the buyer to describe what they want in full detail, or guide them through the process if they're not quite sure. We settled on a hybrid form that first asks a series of basic questions to help categorize the request (product type, budget, shipping location, etc), then proceeds into more open ended questions to allow the buyer to add their personal touch (who is this for, what is this for, etc).

Additionally, we also included a feature that allows the buyer to upload sources of inspiration, and even reference other Etsy products in an effort to expedite the brainstorming process.

Moving over to the artisan side of our flow, we elected to create a sort of "reverse auction" concept. After some intial testing, we found that simply matching buyers with artisans by the highest bidder methodology left too much room for spam, and favored the larger and more established Etsy shop owners. We devised a system that allows the artisan to actively seek new project requests, and choose the requests that interest them the most. When an artisan has expressed interest in a project, we'll go ahead and open up the lines of communication so both parties can negotiate price and clear up any unanswered questions (we'll cover this in just a bit!).

Ultimately, we wanted this system to put both the buyer and artisan on the same level to ensure quality matches and provide the best experience for both sides.
<br>
<br>
## <span style="color: black;">Promoting collaboration</span>
Communication plays an essential role in this process. We can attempt to automate as much as possible using technology but when it comes to communicating abstract ideas, there's no better way than human to human contact. The current tool is a simple email service connected with your Etsy account, but we wanted to implement something a little more robust. Together, we designed a real time messaging feature integrated alongside the project brief that provides a clear communication path and serves as a hub for important notifications.
<br>
<br>
## <span style="color: black;">Prototype & testing</span>
We created a quick prototype in InVision and conducted a few rounds of user testing. We focused on the navigational structure and general user engagement throughout both the buyer and artisan flows. We took diligent notes and carefully listened to the feedback, iterating after every round. We kept the prototype in a low-medium fidelity state to cut down on design time and eliminate any visual bias. [link]
<br>
<br>
## <span style="color: black;">Next steps</span>
Quite a bit actually. Our testing and feedback was positive throughout most stages of the feature set. We're headed in the right direction and have a solid MVP to begin scaling up to desktop size. Once the desktop versions have been tested and validated we can start to transition into higher fidelity comps and prototypes.

The messaging feature is only scratching the surface of effective communication. We're giving two parties the necessary tools to collaborate, but we're not changing behavior. To solve this, we want to implement a system of checks and balances that allow the buyer to request timely status updates of their project. Ideally these updates should be in picture format for the most accurate representation of the current status. We feel this solution is a much closer step towards actively promoting collaboration.
<br>
<br>
## <span style="color: black;">Challenges</span>
Overall, this project was pretty tough. We had a difficult time finding users that accurately represented our target market, especially when it came to requesting custom goods. As a result, a few parts of the design reflected our personal bias.
<br>
<br>
## <span style="color: black;">Retrospective</span>
I would have loved more time to find quality user groups that represented our target audience. I would travel and talk to as many local shop owners as I could to better understand their creative process. Ideally I would want to sit in on actual product requests to hear the dialogue between buyer and artisan.

Our team also spent too much time under the mobile constraint. We incorporated a lot of lean UX principles and had more than enough time to move into desktop design. We were so focused on getting the concept to work at the smallest possible size that we might have missed an otherwise obvious opportunity on a larger scale.
