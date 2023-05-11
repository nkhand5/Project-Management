## Sorority Alum Network
Aliya Gilley, Spring 2023

### Abstract
The goal of this report is to present a project proposal that is meant to help my technical science sorority members stay in touch after graduating, specifically to our chapter at University of Illinois but expanding into all other chapters throughout the United States and Canada.  As a response to this problem, we will be discussing the use of an open source communication and social network platform meant for our sorority alum to use to easily connect. Starting with an introduction, we will move through background research and current state, goals, and development/implementation to fulfill within this project to best cater to our audience.


### Introduction
Throughout college at University of Illinois, I have been fortunate to have been a part of a technical science sorority.  As a graduating senior, I have recently been introduced to steps to becoming an alum member -- which prompted the creation of this project.

For more information, being an alum member of a sorority is more than meets the eye -- the benefits are supposed to be for life. There are many networking opportunities, leadership opportunities, and an overall support system that comes with being an alum, and with graduating I would not trade those for anything. However, many alum do not have a way to easily seek those benefits and communicate with each other, and often feel ostracized or disconnected with other sorority alum.

As an active member, you are given so many occasions to interact with your fellow sisters and stay connected to each other, but alum do not have the same opportunities. Seeing what is available to me after I transition from active to alum status has inspired me to create a website and community network through working open techniques that would make it easier (and hopefully more enjoyable) to bridge the gap between our alum members and keep in touch.


### Background Research
Within project management, background research is most vital in the beginning stages of starting a project, especially as it helps to define the parameters of the project, the need for the project, and predicts the risks and challenges that arise. Within agile methodology, an approach focused on creating value while focusing on people, and eliminating waste has to involve research to make sure that the project is substantial and does or does not need adjustments. So--that is where I began.

First, I needed a bit more information defining the project as a whole, and its need as a product. Answering questions such as who is this project for, why do they need it, and when and where can they use it?  For who, we wanted this project to be for sorority alum that want to connect with the sorority–for what, well, it’s the website. Where would be accessible through our sorority national website, working with their technology and design chairs with permission and direct supervision from the national board.
For when, we would want to establish a project timeline (in agile, a completed cycle) that is reasonable (let’s say, two quarters, or six months) with multiple sprints that have achievable goals
As for why? Well, we determined that by talking to our prospective audience and will continue to use them as a sounding board to show our demos to in order to check if we are on the right track. I’ll talk about that a bit below.

Continuing to get into background research, I started by doing some basic analysis of what was already out there for A.O.E. sorority alum, or evaluating the current state of affairs. Moving through our sorority website, one can see some of the benefits that those with varying alum status are offered (Figure 1). Figure 1 was created via my own personal research as a recent alum myself. Alum have access to multiple newsletters, leadership roles, voting participation, and more, but there is not much more out there that actually allows the alum to participate themselves with the sorority openly (beyond acquiring a leadership position). Through their alum emails each month, we are told of special events that the alum association or national board is hosting, but the alum are not encouraged to promote their own social or professional networking events.

After looking through some of the resources myself, I decided to catch up with some of my favorite alum members from my chapter and ask them some questions about their experience. In total, I was able to discuss with four of them to deduct what they liked, did not like, and most wished for since becoming an alum. Some of the questions I asked were the following: “How has being an alum continued to impact you?” “How has becoming an alum been, so far?” “Do you still keep in touch with your sorority sisters?”

As a result, the interviewees expressed wishing for a way to reconnect with graduated members of their own chapter, but also wanted the opportunity to expand their social and professional network with other chapters within the nation and Canada.  They also admitted not keeping up with communication with the national chapter via emails, and not being as interested in sorority-sanctioned events. Overall, they were quite interested in the possibility of a social network where alumni themselves as members can have the ability to reconnect.


### Goals
With important background research out of the way, we can move to instate the goals we want to achieve for the project. The main goal of the site would be to help alum members keep in touch and make new connections within our alum network. With this goal, we would pursue actionable deliverables through features such as profiles for each alum member, groups that they can not only join but start based on hobbies, location, or any other reason, and the ability to be able to chat with each other.

Let’s summarize the features more eloquently, as follows:
- Profiles in which they can post
- Groups created for and by members, that they can post, comment, and share
- Chatrooms

### Development
After defining the audience and their needs, we begin to move on to the necessary steps within the development stage, which has multiple sections.


#### Planning
Now is planning within the development stage, which is going a bit further than the initial background required.  First, we want to define our website goals and needs to the rest of the team (two technology chairs and two design chairs). How do we want the site to look? Our design goals would be meant to create a pleasing layout that is suitable with the sorority’s current layout (there is a current website already, just not for alum that we would ideally want to follow. That is, on theme with our sorority colors, logos, and fonts that we use via the website and email signatures. A simple tone and look that allows for users to focus on what is most important is a great place to start. Content on the networking site would also prove to be very important, as we would want it to align with our sorority’s messages and values.

Next, how do we achieve our user-friendly goals? Making sure that the website is easy to navigate and provides a pleasant experience to users is key. So we would need to ensure that there is clear navigation, good loading speed, and more. Consulting with the technology chairs in terms of what kind of programming needs to be done, in terms of front-end development, back-end development, and database management.
- The front end is likely done in JavaScript to manage how it would look to the consumer.
- Back end is meant to manage user data, profiles, social groups, comments, and messaging, posts, and user authentication, and will be done in a language familiar to the group. 
- Database management required for our application to store information and posts through SQL.

Our platform that we will use will likely be wordpress, but we may consider changing down the line with design constraints.. Logistically, we will also plan on having weekly stand ups and managing our tasks or “issues” through JIRA/Trello, brainstorming and creating design prototypes with Figma, as managing the teams progress and any setbacks will help to ensure continuous improvement of the project, which is important in agile methodology.

Continuing with planning, it is important when starting the project to get some of the logistics out of the way, and two of those logistics are budgeting and permissions. In terms of permissions, with authorization from the sorority national board, we should not require any particular patents or licensing as our sorority owns their own brand and domain. The code we use for our site would be private, but we would use open source as a reference to help us in the development stage. In terms of budget, we would not require a significant amount of budget (think zero to minimal) as the team working on the site are appointed on a volunteer basis; if we had much budget, we would want to use it for evaluating the impact and success of our site or through purchasing more upgraded templates within the design and development stage.


#### Execution
After the planning stage, we would move on to the execution and launch stage. During this, we would take use of our planning stage to build out the website with our blueprints in design, website layout, and user interface goals. We would likely split the execution stage into multiple two-week sprints, such as the creation of the home page, profiles page, group page, 404 page, contact exec/standards page, reporting page, and more. After finishing our sprints, we would test the website by first creating and publishing our own initial website content and creating groups, but also by demoing to our user base that I interviewed in the background research stage. After passing those tests, we would have the official launch of our website and invite alum to join through alum weekly news emails and via word of mouth.


#### Ensuring Community Engagement
Community engagement is one of the most valuable pieces of this project within our course. It is not only vital to understand the community that we are building for, but also in helping the community want to engage with your product.  We want to give our audience and users the opportunities to create interesting and shareable content that is relevant and appealing -- helping to meet our main goal, to be a bridge to connect our sorority alum members from across the globe. 

That brings me to re-review our goals in the first place. Say that you or a loved one that happens to be an alum member through our sorority is moving to a new city where they have no connections via any friends or family. You would want yourself or them to have opportunities to meet others, correct? Imagine if an alum had a yoga group that promoted to our site and they were able to make great connections within their new city. That is one of the main scenarios that crossed my mind when coming up with this idea. So how do we ensure that users actually participate to fulfill a goal like this?

To do this, I believe that we need to encourage user-generated content as much as possible, provide incentives to participate (especially at our yearly conference!), and host events within the alum association that motivate future involvement from the rest of the sorority. I also think that it is very important to solicit feedback whenever possible, via surveys or through interviews in order to know which areas there are to improve in increasing overall engagement.


#### Utilizing Agile Methodology
In this course, utilizing agile methodology is one of the most crucial aspects of project management. Within this alum network, we especially want to use agile to make our project as successful as possible. The first thing that we want to pursue is making sure that we use visual methods to help break down our large project into smaller tasks; likely, we will use Kanban, JIRA, Trello, or maybe even Github issue boards to track progress and to make adjustments based on the team's needs.  This will also help in making sure that we operate to prioritize most urgent tasks, able to meet deadlines and fulfill our goals.

A second important method to utilize helps to emphasize continuous improvement and gives a space for the team to bring up successes and concerns, and that is the classic standup. Regular standup meetings allow for more seamless collaboration throughout the team, helping to identify problems and rectify them as soon as possible.


#### Monitoring/Maintenance
During the maintenance and monitoring phase, we would work to monitor the website as admin, performing regular updates within our content and security and providing upgrades when possible. Within monitoring, we would want to make sure that we do not run into any issues following the launch, and would be able to come up with any updates that allow the site to continuously improve, utilizing this aspect of agile methodology. There is also the possibility that we would also gather analytic data through Adobe Analytics, but also accessible for free connecting website to google analytics, powerbi, or more, in order to evaluate the performance of the site and make sure through finding quantitative results that it is developed according to the audience’s specifications.


#### Transfer of ownership
Transfer of ownership is a traditional last step in project management to make sure that our alum connection site is maintained and updated by the new owner properly. Making sure that any domain names, website databases and files, and “how-to’s” and directed towards one’s successors helps to ensure a smooth and secure transfer of ownership. Therefore, lastly, we would opt to transfer ownership to the next tech and design chairs once their terms are up (typically around a 6-month window), and celebrate our success.


### Project Expansions
WIthin making a social and professional networking website, it is always relevant to think about possible project expansions that mine or a future team could produce. This is especially true in utilizing agile methodology, as it is designed in planning for potential future expansions or additions to projects, and always encourages continuous improvement and collaboration. The biggest project expansion is the potential of moving beyond our chapter and involving others throughout the sorority (our first launch will be testing for the University of Illinois Urbana-Champaign chapter). This is definitely within the project plans -- but there might be a little more work to expand into other chapters, especially in making sure that the foundation of the site is strong enough to handle a significant increase in users.   In making these possible changes to the site, we would want to be sure that we have a strong foundation to the product that can support future updates and improvements to the website.

There is also a prospect of considering separating the network site into two sections, one being social, and the other being professional. Our sorority prides ourselves in being both a social and professional technical science sorority, helping to provide opportunities in friendship, leadership, and professionalism. Thinking about the possibility of having separate parts of the website (or, one could think of it more as two different sites) is a great way of representing our sorority in the future. 

Other expansions of the project include e-commerce functionality, where we would be able to give away merchandise to others or sell sorority-related items, or integration with other social media sites such as Facebook, LinkedIn, and more. 


### Conclusion
Being in a sorority can take a lot of time and effort, and we want to make being an alum member as enjoyable and easy as possible, giving opportunities beyond the college experience.  Utilizing project management techniques while moving through the steps from background research, to planning and development, we can help improve our alum’s overall experience. With the benefits from agile methodology and other project management techniques, we can bridge the gap in helping our alum feel more connected and uplifted. 


### Appendix
Figure 1

| Alum Status Benefits (Summarized) ||
| ----------- | ----------- |
| Voting participation for elections and proposals      |✔ |
| Eligible for nomination to leadership roles   |✔ |
| Website access (password protected)   | ✔ |
| Monthly newsletter   | ✔ |
| Member events   | ✔ |
