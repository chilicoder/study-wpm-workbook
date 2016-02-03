# A Workbook of Iaroslav Popov for the Web Project Management course

##Notes for the book "Effective Project Management" of R. Wysocki

###Project Management Life Cycles

A **project management life cycle (PMLC)** is a sequence
of processes that includes:
* Scoping
* Planning
* Launching
* Monitoring and controlling
* Closing

![fig21][WysockiFig21]
[WysockiFig21]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-2-1.png "PML approaches"
We choose approach basing on level of goals clearness. 


> I'm still have a general questions,  How to describe Business values? How to make constrains? The business can say.. we want to get 10 or 100 or 1000 customers... let us make a project to do it. **How to separate groundless wishes from reasonable goals?**

> Or maybe better formulation of the question is: **How to separate business goals from project goals?**
Achieve business goals is a project? Or project is to get business value (make revenue generator) which helps to achieve business goal? 

The more uncertainty we get the less detailed planning for the whole project we need in the beginning. It doesn't mean that we need less planning, 

### PMLC model pie
At least 70 percent of all their projects are APM projects, 20 percent are TPM projects, and the remaining 10 percent is split between xPM and MPx projects
> This is very valuable numbers. I wish, I knew them at the start of my career. Too many projects I tried to do in TPM style. In our company we even have some training, but it was only about TPM. I always had a feeling that all my plans and WBS will become useless (and they were) and if any document about the project is more then 1-2 pages then it won't be useful. 
> I think in Web development the numbers are even less for the TPM. The reason is that creation of the software is not an analogue of the factory production, that is mistakenly taken. In software development the analogue of production is **compiling**. And this phase actually takes not much time comparing to the other phases of creation of software product. The right analogue to software development from the factory production is the process of designing of the product. Then the stage mapping can be something like this: 
> * Wrining technical requirements
> * Writing acceptance procedures (AP)
> * Creation prototypes and evaluating them against AP (in software development it's basically the same)
> * Producing experimental series (in software development puting the to the test environment)
> * Production (releasing final version of the product)

> [Link for Engineering design process in Wiki] (https://en.wikipedia.org/wiki/Engineering_design_process#Production_planning_and_tool_design)

###Traditional Project Management
20% of projects. Infrastructure projects. 
TPM projects are change-intolerant. RBS and WBS are relatively complete. High expenses for change.
Well-known technology. Skilled and well organised team. Well, known risks. 
> The examples of TPM projects:
> * Assemble a cabinet from IKEA using a scheme.
> * Digging 10 equal holes.
> * Paining a wall in your new apartment.
> * Cooking a cake with recipe.
> * Build a house using typical scheme.

_Linear PMLC model._ 
![fig22][WysockiFig22]
[WysockiFig22]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-2-2.png "Lenear PMLC Model"
There is no going back to improve deliverables.
> Example: Cooking a cake. 

_Incremental PMLC model._ 
 The complete solution is known at the outset
![fig23][WysockiFig23]
[WysockiFig23]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-2-3.png "Incremental PMLC Model"

Differences from Linear.
* Deliverables in the Incremental approach are released according to a schedule.
* Encourages change requests.
* Often extensive re-planning follows, significantly changing the release schedule.

> Example: Cooking 5 cakes.

###Agile Project Management
The vast majority of their projects are a closer fit to APM approaches than either TPM or xPM approaches
Examples:
* A Critical Problem without a Known Solution
* A Previously Untapped Business Opportunity

> I several times experienced with the situation when people think about problems without known solution in terms of TPM. Especially, this can be dramatically when this people are managers. One of the reason, why they try to put the project in TPM frames - uncertaincy. For them it decreases when they produce some plan. When it has some dates it looks like *real*. The confusion is that estimates doesn't make the solution real and level of uncertancy less. Only research, experiment, evaluation, rethinking and new research and experiments. But actually this is the point of Agile project Management.

APM projects are change-driven. APM are “lean” in terms of planning resources. They utilize just-in-time planning models.
The solution will be discovered only if the client and the development team meaningfully collaborate in an open and honest environment.

> I totally agree with this point. 

APM approaches do not scale well. To manage a 30+ project team, partition it into smaller teams, with each of these teams being responsible for part of the scope

> I think, the communicational aspect is very important. My idea is that in uncertain condition the whole team must share actual information about the project in realtime. People must understand what other are doing at the moment to act cohesively. All recently resolved or revealed problems must be exposed to all members. But even if you organize the communicational flow in your 30+ people team effectively and all will get all information immediately, the amount of information would be too big, your team members wouldn't be able to process all this information.

> In TPM project it is not so important. The main task for the members is to follow the plan. The role of communication increases only if somebody can't follow the plan.

APM approaches all have one thing in common — you cannot build a complete WBS without guessing. The choice
of which model to use depends somewhat on the initial degree of uncertainty you have about the solution.

_Iterative PLMC Model_
![fig24][WysockiFig24]
[WysockiFig24]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-2-4.png "Iterative PMLC Model"

Differs from the Incremental PMLC model in that change is expected. The development team usually takes client input and presents alternatives in the next version of the prototype.

> Example: Making a fancy haircut. 

> Example 2: Footbal team that plays match. 

> Building a landing page using well-known CMS.

_Adaptive PLMC Model_
the less you know about the solution, the more likely you will choose
an Adaptive PMLC model over an Iterative PMLC model.

![fig25][WysockiFig25]
[WysockiFig25]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-2-5.png "Adaptive PMLC Model"

###Extreme Project Management
Pure R & D, new product development, and process improvement projects
Example: Building a business-to-business (B2B) website with no further specification.

In most cases, there is no fixed budget or time line. Obviously, the client wants it completed ASAP for as little as possible.

__The xPM Project Is Very High Risk__

_We need to clarify the goal. For this we can use Probative Swim Lanes approach. Depending on available resources we probes can be performed concurrently or sequentially._

The goal is often not much more than a guess at a desired end state with the hope that a solution to achieve it can be found

> Here I describe a naive approach of doing a plan for such a project. I often saw it when people have only scrappy knowledges about project management and dwell in frames of TPM. 

> Let say we want to achieve a goal of 1000 new customers. And we have an idea, let's say some new marketing product for that. And of couse we want them quickly... so lets define the time constraints in one year. One year is a good, big and the most important defined constrains (Actually, if people estimate some task in one year is is a good sign that they completely don't know how to reach the goal).  So, we have pretty good defined goal of the project. It is specific (new customers), it is measurable (1000) and it is time-bound (one year) and also we know how (with new marketing product). 

> But it seems the task is too big. We need to devide it into pieces. Ok, lets create milestones:

> 1) After third month we will accuire 100 customers.
> 2) After six months we will accuire 300 customers.
> 3) After nine months we will accuire 600 customers.
> 4) In one year we will get 1000 customers. 

> Sounds reasonable. So, lets do it!

> Of cause, this plan won't work. After 3 month it will appear, that we accuired a few customers, far away from 100. Or even the product is still in designing phase. Some managers will start to blame the team of the project. And it will be natural, since the goal is very clear and the plan is very clear. 

> So, whats wrong? The key to the answer is partially in the concept of [SMART goals.](https://en.wikipedia.org/wiki/SMART_criteria#Other_definitions) Our goal is Specific, Measurable and Time-bound. And maybe it is even Relevant. But we have no evidences that it is Achievable. Why 1000? Why not 10000? Or maybe 100? or 10? Wishes are only wishes they can't substitute plans.

> In our case, it would be better to reformulate the goal to "In 3 months get the way how to accuire customers with the new marketing product" And the acceptance creteria is "Accuire 1-10 new customers."



Difference between APM and xPM PMLC. 
* In an APM project, scope is done once at the beginning of the project. In the xPM project, scope is adjusted at each phase.
* In many xPM projects, the client takes a leadership position instead of the collaborative position they took in
APM projects.

> The question is how to engage client to take leadership in such project. He can take the position "For what I pay my money? I want to pay money for the solutions. And you propose me to solve my problems by myself and also pay money for this. 

> Some strategies to change this position
> 1) Don't work with this client
> 2) Explain, that he pays for your experience and skills that will supplement his experience in effort to solve problem that was unsolved before.
> 3) ...


_Extreme PLMC Model_
“Fuzzy goals” or goals that cannot be defined because of the exploratory nature of the extreme project
Example: Drug research

![fig26][WysockiFig26]
[WysockiFig26]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-2-6.png "Extreme PMLC Model"

xPM requires the client to be more involved within and between phases.

> Since such projects involve two or more  companies with possibly different corporate culture and so on. Thus, we need to organize some team building activities and carefuly choose communication models. 

> Obviously, the profile of client as a company or person matters in eX projects, since he will play big part in main effort of the project. Conversaly, in TPM projects (and Incremental and Iterative) the profile of the client is not so important. 

###Emertxe Project Management 
The solution is known, but the goal is not. Type of R & D project but in reverse. You hope to find a business value for application of your solution. The scheme is similar to xPM

MPx characteristics
* A New Technology without a Known Application
* A Solution Out Looking for a Problem to Solve (New software system introduced and you try to find how it can be useful to your company)

> Interesting type. I should read more about it.

###Choosing a model 
![fig28][WysockiFig28]
[WysockiFig28]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-2-8.png "PMLC model choice process"

> The key point: Every project starts with writing Project Overview Statement. This document will be like light from lighthouse for all other documents. 

Other factors that can affect:
* Total Cost
* Duration
* Market Stability
* Technology
* Business climate
* Number of departments affected
* Organizational Environment
* Team Skills
TPM - "B" players (or even "C")
APM -  "B" players with supervision of "A" player often sufficient
The less you know about the solution, the more you are going to have to staff your project with “A” players

> I aggree with this point. At least, for web project management projects. The problem is that unexperienced players have small chances to contribute into solutions, to decrease level of uncertaincy. There are many arias of uncertaincy for them which are clear to experienced players. And they have to clarify this arias before start to produce additional value. 

> Supervision works only in TPM and APM projects. The reason is that "A" player with high level of confidence **must know the solution** of task for the guided players. In that case he can quickly review their solutions and identify weak points. 

> In eXPM projects this doesn't work because even experienced players doesn't know the solution. So, they can't guide effectively. I saw many times, when experienced developers spend much time trying to understand weak solutions of juniors and in the end just give up and write the solution by themselves. 

## Project Management Process Groups
* _Scoping Process Group_ (which PMI calls the Initiating Process Group)
“What business situation is being addressed?” and “What does the business
need to do?”
* _Planning Process Group_
* _Launching Process Group (which PMI calls the Executing Process Group)_
* _Monitoring and Controlling Process Group_
* _Closing Process Group_

### Knowledge Areas
Project Integration Management
Project Scope Management
Project Time Management
Project Cost Management
Project Quality Management
Project Human Resource Management
_Project Communications Management_
As many as **70 percent of the IS/IT project failures can be traced back to poor communications**

> Aggree. Communication for the team is like oil for engine. It will creaks and give no power without oil. And pretty soon it will brake. 

> Remember, that IS/IT projects usually are XPM or pretty close to them. And since that, influence of communicational aspect is high. We need to perform team building activities to organize a group of individuals into team. Reveal leaders, instantiate communication flows, resolve personal conflicts. 

> Sometimes, highly organized and motivated team is itself the result of the project. But if we want to increase chances of successfully achieving the goal, we should organize the team before or at the early stage of the project.

A good communications management process will have provisions in the process that answer the following questions:
* Who are the project stakeholders?
* What do they need to know about the project?
   Common questions of all stakeholders:
  * What input will I be required to provide the project team?
  * How can I make my needs known?
  * When will the project be done?
  * How will it affect me?
  * Will I be replaced?
  * How will I learn how to use the deliverables?
* How should their needs be met?

Project Risk Management
Project Procurement Management
_Project Stakeholder Management_
Stakeholder types:
* Sponsors
* Clients
* Customers
* Business process engineers
* Resource managers
* Project managers
* Business analysts

> Revealing stakeholders is also one of the initial activities in interaction design.

![tab33][WysockiTab33]
[WysockiTab33]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-tab-3-3.png "Mapping of the Ten Knowledge Areas to the Five Process Groups"

The Process Groups are the building blocks of project management methodologies. Similarly,
by selecting and adapting the processes within a Process Group, you can establish the specific processes that drive a PMLC. So the processes within a Process Group are the detailed building blocks of the phases of the PMLC.

> I experince a lack of examples here and can't understand the value of this matrix. Feels like 

###Ch4 Scoping in TPM
Managing Client Expectations
Wants versus Needs
__Wants and needs are closely linked to one another but are fundamentally
different__ Client wants tend to be associated with a solution
to a problem that they envision. Needs tend to be associated with the actual
problem. 

**Ask the client why they want what they want**

> This point is crucial. From my experience in majority of cases people don't tell their problem they tell their vision on how this problem can be solved. Often, due to the fact that they are experts in problem domain, but they are not experts in solution domain, this suggestions are hard to implement and they poorly solves the real underlying problem. 

> Identifying and articulating the real problem of the client is the main task on the stage of analysis. It will give more flexibility to solution experts and also provides better acceptance rules.


![fig44][WysockiFig44]
[WysockiFig44]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-4-4.png "The Stakeholder Interaction Model"


**Selected Methods for Eliciting Requirements from Business Needs**

| METHOD | STRENGTHS | RISKS |
|----| --------------------| -------------|
|Facilitated Group Sessions  | Excellent for cross-functional processes.Detailed requirements can be documented and verified immediately. Resolves issues with an impartial facilitator. | Use of untrained facilitators can lead to a negative response from users. The time and cost of the planning and/or executing session can be high.|
|Interviews |End-user participation. High-level descriptions of functions and processes are provided.  |Descriptions may differ from actual detailed activities. Without structure, stakeholders may not know what information to provide. Real needs may be ignored if the analyst is prejudiced.|
|Prototyping  |Innovative ideas can be generated. Users clarify what they want. Users identify requirements that may be missed.Client-focused. Early proof of concept.Stimulates thought processes. |Client may want to implement the prototype. Difficult to know when to stop. Specialized skills are required. Absence of documentation. |
|Requirements Workshop |Good way for first-time users. |May overwhelm customer. |

> I think smart combination of several approaches can increase efficiency. For example, make a Requirements workshop that will provide base for prototyping. And after presenting prototypes make and Interview. 

![tab42][WysockiTab42]
[WysockiTab42]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-tab-4-2.png "Mapping of the Ten Knowledge Areas to the Five Process Groups"

__Project Overview Statement (POS)__
The POS is a short document (ideally one page) that concisely states what is to be done in the project, why it is to be done, and what business value it will provide to the enterprise when completed.

The POS has the following five component parts:
* Problem or opportunity
* Project goal
   * __Specific__ Be specific in targeting an objective.
   * __Measurable__ Establish measurable indicators of progress.
   * __Assignable__ Make the object assignable to one person for completion.
   * __Realistic__ State what can realistically be done with available resources.
   * __Time-related__ State when the objective can be achieved - that is, the duration.
* Project objectives
* Success criteria
* Assumptions, risks, and obstacles

> I believe, this document have a great value. First of all it is short, so everybody can read it and get the gist of the project. Then POS clearly articulate the main goal of the project. Be a starting point to all other documents. 

##Planning in TPM
![fig51][WysockiFig51]
[WysockiFig51]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-5-1.png "Pain curves"

Project Evaluation and Review Technique (PERT) chart is a graphical tool
that displays the relationship between dependent tasks

As for project planning the list is very short: sticky notes, marking pens, and plenty of whiteboard space. The tools I just mentioned happen to be my choice for some incremental, most iterative, all adaptive, and all extreme projects. Just remember that if you create the plan using software tools, you have to maintain it using the software tools.

The following estimates of planning time are a good guide:
*  Very small projects Less than 1/2 day
*  Small projects Less than one day
*  Medium projects 2 days
*  Large projects 3 – 4 days
*  Very large projects 30 team members translates to a large project. The planning time can vary widely from 5 or more days to several months.

The objective of a Joint Project Planning Session (JPPS) is this: Develop a project plan that meets the COS as negotiated between the requester and the provider, and as described in the POS and RBS. (Conditions of Satisfaction (COS) and Project Overview Statement (POS))

Sample agenda for the project planning sessions:
* Session 1
  1. Negotiate the COS.
  2. Build the RBS.
* Session 2
  1. Write the POS.
* Session 3 (JPPS)
  1. The entire planning team creates the first-level WBS.
  2. Subject matter experts develop further decomposition, with the entire planning team observing and commenting.
  3. Estimate activity durations and resource requirements.
  4. Construct a project network diagram.
  5. Determine the critical path.
  6. Revise and approve the project completion date.
  7. Finalize the resource schedule.
  8. Gain consensus on the project plan.

> Interesting structure. But remember, that it relates to the TPM projects. For other types there is a big probability that all RBS and WBS... critical path would be useless after one or two iterations.


The __Work Breakdown Structure (WBS)__ is a hierarchical description of all work that must be done to complete the project as
defined in the current RBS

Six Criteria to Test for Completeness in the WBS
Activity must possess to be called a task are as follows:
* Status and completion are measurable.
* The activity is bounded.
* The activity has a deliverable.
* Time and cost are easily estimated.
* Activity duration is within acceptable limits.
* Work assignments are independent.

If the activity does not possess all six of these characteristics, decompose the activity and check it again at that next lower level of decomposition.

Approaches to Building the WBS
* Physical Decomposition
* Functional Decomposition
* Design-Build-Test-Implement
* Objectives
* Geographic
* Departmental
* Business Process
pick the one that seems to bring the most clarity to defining the project work.

> I know another way of decomposing big tasks. In discription we should focus on how we will verify that this task is successfully done. We write down criteria that become itself smaller tasks. We proceed untill all tasks will be devided into small, understandable pieces that can be estimated in terms of work. The resulting graph becomes an analogue of WBS plus we get the acceptance rules to all tasks.

![fig57][WysockiFig57]
[WysockiFig57]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-5-7.png "WBS for a waterfall systems development methodology"

Estimating.
It is important to understand the difference between labor time and duration time. They are not the same.

![fig58][WysockiFig58]
[WysockiFig58]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-5-8.png "Elapsed time versus work time"

> Important point. Especially in Web Development, since software engeneers must stay in so-called [State of Flow](https://www.rallydev.com/blog/agile/benefits-attaining-flow-state-agile-software-development) to be effective.
From the other hand we still need to facilitate broad channel of communication between team members. To the problem of finding right balance several works are dedicated. E.g. [Cone of silence ](http://alistair.cockburn.us/The+cone+of+silence+and+related+project+management+strategies) from Alistair Cockburn.

Six Methods for Estimating Task Duration
* Similarity to other tasks
* Historical data
* Expert advice
* Delphi technique
* Three-point technique
* Wide-band Delphi technique

Estimating Resource Requirements
Estimating Cost

Project Network Diagram
A project schedule can be built using either of the following:
* Gantt chart
* Network diagram


Contents of the Project Proposal:
* Executive Summary
* Background
* Objective
* Overview of the Approach to Be Taken
* Detailed Statement of the Work
* Time and Cost Summary
* Appendices

###Launch a TPM Project
Recruiting the Project Team.
Building effective teams is as much an art as it is
a science.

The project team has the following three separate components:
* Core team
* Client team
* Contract team

The Project Kick-Off Meeting is the formal announcement to the organization that this project has been planned and approved for execution.

> Although it is a formal procedure, but this action plays a role of a trigger for the project team. Also, it is a signal for other stakeholders who doesn't involved in project activities directly.

A sample Project Kick-off Meeting agenda:
* Introduce the sponsor to the project team
* Introduce the importance of the project by the sponsor
* Introduce the project (client)
* Introduce the project (project manager)
* Introduce the project team members to each other
* Write the PDS
* Establish the team operating rules
* Review the project plan
* Finalize the project schedule
* Write work package


Establishing Team Operating Rules.
Having these rules developed and agreed to by every team member is critical to project success. The rules of the engagement will help establish an environment for solving many project-related problems

> Important point. This rules clarifies the procedure of resolving conflicts. That decreases risks of failure, since people know how to act in unconvenient situations. Otherwise they could keep silence until at some point it becomes unresolvable. 

Situations that Require Team Operating Rules:
* Problem solving
* Decision making
  * _Directive._ the person with the authority (the project manager for the project and the task manager for the task) makes the decision for all team members
  * _Participative._ Everyone on the team contributes to the decision-making process.
  * _Consultative._ The person in authority makes the final decision, but this decision is made only after consulting with all members to get their input and ideas
* Conflict resolution
  * _Avoidant_ Some people will do anything to avoid a direct confrontation, but each person's input and opinion must be sought. A simple device is to ask all of the team members in turn what they think about the situation and what they suggest should be done about it.
  * _Combative_ The project manager must be able to identify these combative team members and act to mitigate the chances of these combative situations arising. Tip: to put potentially combative individuals in charge of forming a recommendation for the team to consider.
  * _Collaborative_ This approach encourages each team member to put his or her opinions on the table and not avoid any conflict that may result.
* Consensus building
* Brainstorming
* Team meetings

> Basically all key activities of the project with rich communication.

Team War Room
Ideally, all of the walls are covered with whiteboards. Depending on the size of the team, the team war room may be one large room that accommodates everyone or several smaller rooms that are adjacent to a larger community-type room for group meetings and presentations. These adjacent rooms can double as breakout rooms. Each team member has his or her own private workspace, but there is a minimum number of partitions. A line of sight between each team member is ideal. The project artifacts are displayed so everyone has immediate access.

> In one company we had a big blackboard wall in one meating room on which one could draw with a chalk. That was very convenient. Putting diagrams on walls also has positive effect.

> The class of such information charts and diagramms is called Information Radiators. [Definition](http://alistair.cockburn.us/Information+radiator) from "Crystal Clear" book of Alistair Cockburn. And [Images from google](https://www.google.de/search?q=information+radiators&biw=1184&bih=630&source=lnms&tbm=isch&sa=X&ei=wiqVVeaYEoG2sAHbjIDwCA&ved=0CAcQ_AUoAQ) also gives some points what it is.

Managing Scope Changes.
Change is a way of life in project management. You might as well confront it and be prepared to act accordingly. Think of it as a mini-JPPS.
![fig62][WysockiFig62]
[WysockiFig62]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-6-2.png "A typical change control process"

Managing Team Communications.
Technical people often simply aren't good communicators. However, for team members to be truly effective, they have to openly communicate with one another
> Cockburn names ["Personal Safety "](http://alistair.cockburn.us/Personal+organisation) as one of the properties of successful teams. If people feel safe they provide better critique during retrospective sessions, point out to the conflict on the early stages and report delays in delivery early. 

Effectively managing communications is a critical factor for successful project management.

About long documents. You would get more meaningful feedback by parceling out the document based on level of interest and involvement in the process, rather than asking everyone to read and comment on all 50 pages.

Managing Communications with the Sponsor.
Without sponsor involvement in all phases of the project, you will be in dire trouble. 
  1. The first action to take when you are about to start a project is to go to the sponsor and ask what they want to know and when they want to know it.
  2. A second consideration is to ensure that the sponsor gets information regularly. Status reports should be sent to the sponsor at least once a week

Assigning Resources.
Any organization that does not have a way of effectively handling these situations will find itself in a situation analogous to the fl ow through a funnel

![fig64][WysockiFig64]
[WysockiFig64]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-6-4.png "The resource scheduling problem"
Too many organisations believe that by simply adding more into the top of the funnel, more will come out of the bottom.

> Totally aggree. Not yet have much experience for German cultural features in that aspect, but in Russian corporate culture this point exists very often. That produces higher level of stress and burnout. 

The resource schedule needs to be leveled for the following two reasons: 
* To ensure that no resource is over-allocated. That is, you do not schedule a resource to more than 100 percent of its available time.
* You, as the project manager, want the number of resources (people, in most cases) to follow a logical pattern throughout the life of the project

> Also we must not forget about the factor of "Flow". Overlaying several tasks on one developer in one time will significantly decrease his productivity. 

Approaches to level project resources:
* Utilising available stack
* Shifting the project finish date
* Smoothing

Work Packages.
The __work package__ is a statement by each task manager as to how he or she plans
to complete the task within the scheduled start and finish dates.
![fig66][WysockiFig66]
[WysockiFig66]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-6-6.png "Work package assignment sheet"

> Never saw the value from such tables. 

###Monitor & Control a TPM Project
Here are some of the reporting tools:
* Current period reports
* Cumulative reports
* Exception reports
* Stoplight reports (stickers on the first page)
* Variance reports
* Gantt charts
![fig72][WysockiFig72]
[WysockiFig72]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-7-2.png "Gantt chart"
* Burn charts
![fig73][WysockiFig73]
[WysockiFig73]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-7-3.png 
"Burn chart"
* Milestone trend charts
![fig75][WysockiFig75]
[WysockiFig75]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-7-5.png 
"A change of more than three standard deviations"
* Earned value analysis (EVA)
![fig710][WysockiFig710]
[WysockiFig710]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/wisocki-fig-7-10.png 
"Baseline versus actual cost illustrating schedule variance"
* Integrated milestone trend charts and EVA
* Project status meetings
* Problem escalation strategies
For most projects, start gathering the information around noon on Friday. Let
people extrapolate to the end of the workday.

Establishing Your Progress Reporting System
A reporting system has the following characteristics:
* Provides timely, complete, and accurate status information
* Doesn't add so much overhead time as to be counterproductive
* Is readily acceptable to the project team and senior management
* Has an early warning system of pending problems
* Is easily understood by those who have a need to know

> I used JIRA in several places. It provides a big bunch of different reports and also very flexible. So almost any custom report can be created.

> The key point: You must explicitly teach your employees how to use the tool. Otherwise their input would be inconsistent and you won't get valuable reports. Also, if people won't see any value of their input efforts, they quickly stop providing it. People are lazy, they won't do usefulless things. 

Positive Variances problems.
Positive variances can result in rescheduling to bring the project to completion early, under budget, or both. Resources can be reallocated from ahead-of-schedule projects to behind-schedule projects. Positive variances also can result from schedule slippage! Consider budget. Being under budget means that not all dollars were expended, which may be the direct result of not having completed work that was scheduled for completion during the report period

Managing the Scope Bank.
Ten percent of the total labor days would be a reasonable deposit.

Building and Maintaining the Issues Log.
Contains the following information:
* ID number
* Date logged
* Description of the problem
* Impact if not resolved
* The problem owner
* Action to be taken
* Status and date
* Outcome
If a Risk Log is maintained, it is often integrated into the Issues Log

> There are many automation tools like JIRA, Redmine and so on.

Managing Project Status Meetings.
You hold a status meeting to get information to the whole team. The purpose of the meeting is to encourage the free flow of information, and that means ensuring that the people who need to have information to do their jobs get the information at the status meeting.

> There should be a balance, I think. Once a day for a small team (5-8). Once a week for a department (~30 people). Once a month for a company (~100-200) and once a year for enterprise. 

Status Meeting Format:
1. The project champion reports any changes that may have a bearing on the future of the project.
2. The client reports any changes that may have a bearing on the future of the project.
3. The project manager reports on the overall health of the project and the impact of earlier problems, changes, and corrective actions at the project level.
4. Activity managers report on the health of activities open or scheduled open for work since the last status meeting.
5. Activity managers of future activities report on any changes since the last meeting that might impact project status.
6. The project manager reviews the status of open problems from the last status meeting.
7. Attendees identify new problems and assign responsibility for their resolution (the only discussion allowed here is for clarification purposes).
8. The project champion, client, or project manager, as appropriate, offers closing comments.
9. The project manager announces the time and place of the next meeting and adjourns the meeting.

The 15-Minute Daily Status Meeting.
These short status meetings were originally introduced as a tool to monitor and control APM, xPM, and MPx projects. Problems and issues are not discussed in the daily status meeting except to add them to the Scope Bank and Issues Log

> Two points. 1) No issue discussions. Better make a semi-strict template for report. Only clarify points, but not discuss.

> 2) Doesn't suit for distributed teams. Better do it weekly.

Defining a Problem Escalation Strategy.
When the unplanned happens, the project manager needs to determine who owns the problem and the extent of the problem, and then take the appropriate corrective measures.
There are three levels of escalation strategy: 
* project team–based 
* resource manager–based
* client-based.

The Escalation Strategy Hierarchy
1. No action required (schedule slack will correct the problem)
2. Examine FS dependencies for schedule compression opportunities
3. Reassign resources from non–critical-path activities to correct the slippage.
4. Negotiate additional resources..
5. Negotiate multiple release strategies.
6. Request a schedule extension from the client.

Approval to Close the Project.
In most cases, the acceptance criteria are nothing more than a checklist that reflects the client requirements.

###Close a TPM Project
Closing a Project:
1. Getting client acceptance of deliverables
   The ATP checklist is written in such a fashion that compliance is either dem onstrated by the test or it is not demonstrated by the test. It must be written in such a way that no interpretation is needed to determine whether compliance has been demonstrated.
2. Ensuring that all deliverables are installed
   Methods to install deliverables:
   * Phased Approach
   * Cut-Over Approach
   * Parallel Approach
   * By-Business-Unit Approach
3. Ensuring that the documentation is in place
4. Getting client sign-off on the final report
5. Conducting the post-implementation audit
6. Celebrating the success

Documentation
Five reasons why you need to write documentation
* Reference for Future Changes in Deliverables
* Historical Record for Estimating Duration and Cost on Future Projects, Activities, and Tasks
* Training Resource for New Project Managers
* Input for Further Training and Development of the Project Team
* Input for Performance Evaluation by the Functional Managers of the Project Team Members

Example list:
* Project Overview Statement (POS)
* Project proposal and backup data
* Original and revised project schedules
* Minutes of all project team meetings
* Copies of all status reports
* Design documents
* Copies of all change notices
* Copies of all written communications
* Outstanding issues reports
* Final report
* Sample deliverables (if appropriate)
* Client acceptance documents
* Post-implementation audit report

> It depends on the level of how this documents will be reused. How quick they become obsolete, How much efforts needed to produce this documentation. I would say, POS, Design documents, Final report and Client acceptance documents have value. But I really don't remember that I ever read status reports of any closed projects.

Celebrating Success
There must be some recognition for the project team at the end of the project. This can be as simple as individual thank-you notes, a commemorative mug, a T-shirt, a pizza party, or tickets to a ball game; or it can be something more formal, such as bonuses
Even though the team may have started out as a “herd of cats,” the project they have just completed has honed them into a real team. This can be a very traumatic experience for them, and they deserve closure. That is what celebrating success is all about.

> This is important. While formal announcement switches on people and focuses them to the project. This procedure switches them off. All valuable reflections are done, they can concentrate on next project. Also the feeling "we did it" positively effects on motivation and confidence. 

###Complex Project Management
Understanding the Complexity/Uncertainty Domain of Projects
__Uncertainty__ is the result of changing market conditions that require high-speed and high-change responses to produce a solution in order to be competitive. __Complexity__ is the result of a solution that has eluded detection and will be difficult to find.

__Non-value-added__ work involves the consumption of resources (usually people or time) on activities that do not add business value to the final product or process.

Each quadrant of the project landscape has different profiles when it comes to risk, team, communications, client involvement, specification, change, business value, and documentation.

As less and less of the solution is known, the impact of non-value-added work on project success becomes more and more of a factor. Time has been wasted. APM models are better equipped than TPM models to handle this uncertainty and the complexity that results from it. __The models are built on the assumption that the solution has to be discovered__

APM processes expect and embrace change as a way to find a better solution and as a way to maximise business value within time and budget constraints. That means choosing and continually changing the PMLC model to increase the business value that will result from the project. Realise that to some extent __scope is a variable__ in the complex project management world.

Risk versus the Complexity/Uncertainty Domain.
the PMLC model becomes more flexible and lighter. At the same time, project risk increases. Risk increases
in relation to the extent to which the solution is not known. On balance, that means more effort should be placed on risk management as the project moves through APM and looks more like an xPM project. There will be less experience with these risks because they are specific to the product being developed. In xPM and MPx projects, risk is the highest because you are in an R & D environment. Process risk is almost nonexistent because the ultimate in flexibility has been reached in this quadrant but product risk is extremely high.

Team Cohesiveness 
The team becomes more self-organising, self-sufficient, and self-directing as the project moves across the quadrants. *It is highly recommended that APM, xPM, and MPx teams be co-located.*

> And it is hardly recommended that the team is formed and built. The more people know each other the less is the requirement of colocation. Of cause it is better to have all members sit together or nearby. But if it is not achievable, then we need to facilitate special team building activities. Invite people in one place; organise business trips between offices. People instantiate communication, trust and respect between each other much easier and faster then they physically do some activities together (especially if they succeed). 

> Moreover, if you team consist of people with different culture, your team building activities must be significally intended. The risk that people won't achieve effective communication and form team increases. 

> If you failed to organise your people as a team, it is better to divide tasks into separated. Otherwise, the probability of conflicts will be very high, increasing the probability of fail for the project.

Communications.
Top 10 reasons for project failure as reported in the Standish Group CHAOS 2010 Report:
__1. Lack of user input__
__2. Incomplete requirements and specification__
__3. Changing requirements and specification__
4. Lack of executive support
5. Technology incompetence
6. Lack of resources
7. Unrealistic expectations
8. Unclear objectives
9. Unrealistic time frames
10. New technology
The first three items on the list are related to people-to-people communications, either direct or indirect.

As uncertainty and complexity increase, one-way communication has to give way to two-way communication, so written communications give way to meetings and other forums for verbal communication.

Client Involvement.
Clients must now take a more active role in APM projects than was their role in TPM projects. For xPM projects, meaningful client involvement is essential. In fact, the client should take on a proactive role. The project goes nowhere without that level of commitment from the client.

In your effort to maintain client-focus and deliver business value, you are dealing with a business problem,
not a technology problem. You have to find a business solution. Who is better equipped to help than clients? After all, you are dealing with their part of the business ????????? _Business solution?_

Here is my suggestion to attain and sustain meaningful client involvement. Training, training, and more training.

Ownership by the Client _maybe this is the key for business solution?_
This ownership is so important that I have even postponed starting client engagements because clients can't send a qualified spokesperson to the planning meeting. When they do, you have to be careful that they don't send you a weak representative who just isn't busy at the time or who doesn't really understand the business context of the project.

Specification

Changes
The less you know about requirements, functionality, and features, the more you have to expect change.
When the client has the opportunity to examine and experiment with a partial solution, they will invariably come back to the developers with suggestions for other requirements, functionality, and features that should be part of the solution. These suggestions can be put into one of two categories:
either they are _wants_ or they are _needs_

Wants may be little more than the result of a steak appetite on a baloney budget. It is up to the project manager to help clients defend their wants as true needs and hence build the business case for integrating the changes into the solution. On the other hand, if a client demonstrates the true value of what they want, it can be transferred to a true need

Business Value

TPM projects potentially deliver the least business value and that business value increases as you move from TPM to APM to xPM. At the same time, risk also increases, which means that higher-valued projects are expected in order to be commissionable as you move across the quadrants. Remember that the expected business value of a project is the product of (1 – risk) and value.

The more uncertainty that is present in the development project, the more need
there is to be able to redirection as business conditions change

The focus on delivery of business value is apparent and up-front in all of the APM and xPM project management approaches.

###Agile Project Management

Twelve principles of Agile Software:

[Presentation about Agile Manifesto](https://www.dropbox.com/s/nkpzwmrqsriadiz/Agile%20Manifesto%20-%20Web%20Project%20Management.pdf?dl=0)

* Our highest priority is to satisfy the customer through early and continuous delivery of valuable software

* Welcome changing requirements, even late in  development. Agile processes harness change for  the customer's competitive advantage.

* Deliver working software frequently, from a couple of weeks to a couple of months, with a  preference to the shorter timescale.

* Business people and developers must work  together daily throughout the project.

* Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.

* The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.

* Working software is the primary measure of progress.

* Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.

* Continuous attention to technical excellence and good design enhances agility.

* Simplicity--the art of maximising the amount of work not done--is essential.

* The best architectures, requirements, and designs emerge from self-organising teams.

* At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behaviour accordingly.
 

## 23 Apr 2015 - Online Session Notes
###SCRUM
To my mind one of the the main threads in starting of scrum is the thread of falling to the Cargo cult, when a team start to do activities but doesn't understand what are this activities for

What are the prerequisites for SCRUM process in a company:
-Discipline
-Communication
-High quality of product management


###eXtreme PM

exploratory nature

high risk, high change

Heavy client involvement

no time constraints!
can add side business value.

high level documentation but massive communication

establish rules for change requests then quickly react on changes


weaknesses 
easy to head of the road

###IN SP I RE model


###Multiple Teams Projects
Several independent team (possible from outside)
MY: crucial task to organise communication channels and interfaces between teams

Project Office Structure
linear and incremental processes

Core Team Structure 
Core Team Manager is not a Project Manager
He is a Lead of Leads


## cards for [presentation] (https://docs.google.com/presentation/d/1aK-o-Ob9LlVDrNNGqGasahJMUzMtUIQa-QPyuNvSIfQ/edit?usp=sharing)
### Belonging
> Ill start with aspect

> Mythologies  

> shared histori es (real or imagined) that express values of the community. Communities use these stories to illustrate values and to inspire desired behaviour. They provide members with a moral compass in situations that are important to the community.

> In modern times, we still use mythologies to show members of a community what they should value. they can be used to help members of the network and community understand how to respond in particular kinds of situations and how to interact with others.

> So, what techniques we can use in order to build this aspect
> TECHNIQUES
create a “Share Stories Archive ”
To do this asked some of the leaders in the network to “seed” the discussion
possible topics for the stories might be about initial rituals in the community or some remarkable achievements
After that usually other members start to contribute their own stories

>  A last, individual members can also use the same storytelling technique to create a persona for themselves within a community.


> negative myths

>  negative myths serve to warn members against prohibited behaviours

> Another point is to get
 a “bard” who, like the medieval bards of old, has the responsibility of collecting the stories of the group.

> next aspect of Belonging is 
>  Protocols, routines, and Schemas 

> Protocols, routines, and schemas are ritualised behaviours that members of a community use in two ways: 
> (1) to identify and greet other members and 
> (2) to understand the correct behaviours to use in different social situations.

> Schemas are sets of preprogrammed procedures used in potentially difficult social situations to keep those situations from embarrassing us.

> Protocols are like schemas, but they’re not tacit.
> Their like rules of the road.

> Routines are also protocols; just protocols that are happening repeatedly. 
> Routines help ensure sustainability and minimise conflict.

> As and example of technique lets consider a group of very successful and very strong-willed professionals with which Tharon Howard worked

> This particular group was mostly male, and it was fairly big problem with resolving conflicts
> So called “Fight club rules” were introduced.

> The soap bar 
> became, a badge of shame that the person would have to keep until someone else on the team “earned” the soap bar.
several of the members stated bluntly that they thought it was a “stupid game” and stated that they would refuse to use the soap bar on their posts

> but once the protocol was in place, earning the soap bar and not using it showed a degree of contempt for the entire community that only few in the group were willing to risk.

> Brief defenition
> Why is it important
> Give example
> Further points

> CHECKLIST OF TECHNIQUES
1. Create and distribute a story of origin
2. Create an initiation ritual
3. Encourage your leaders and elders to share mythologies
 Use negative myths
4. Encourage members to share myths and stories about themselves
5. Create leveling up ceremonies
 Use podcasts
6. Establish routines and protocols
 “Fight Club” protocol
7. Establish symbols, colors, and visual identities
8. Use a membership application as an initiation ritual

> How to keep balance between exclusivity and popularity?
> What kind of vision should be shared by story in technique 1? 

test jenkins
