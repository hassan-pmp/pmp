# Things I Learning
---
# 28.06.2024 GenAI in Project Management: Planning: Lesson_3
- **Schedule Compression**
	- Fast tracking: A schedule compression technique in which activities or phases normally done in sequence are performed in parallel for at least a portion of their duration
	- Crashing: A technique used to shorten the schedule duration for the least incremental cost by adding resources

- **If you are behind schedule, follow the steps below**:
	- Check risks and re estimate
	- Fast track the project
	- Crash the project
	- Reduce scope
	- ~Cut quality~
- **Learning curve**: The 100 th room painted will take less time than the first room because of improved efficiency.
- **Type of Costs**:
	- Variable Costs: Costs rise directly with the size and scope of the project.
	- Fixed Costs: Costs do not change; non-recurring (e.g. project setup costs).
	- Direct: Are costs that can be directly related to producing the products and services of the project
	- Indirect: Are overheated items or costs that are not directly related to the products or services of the project.
		- Are indirectly related to performing the project and incurred for the benefit of more than one project.
- **Value Analysis/Engineering (VE)**: Finding less costly way of the same work.
-





# 28.06.2024 GenAI in Project Management: Intro: Lesson_2
- How to use data and GenAI in Project Management?
- 1. Automation
- 2. Assistance
- 3. Augmentation
- Sculpt your role as project manager in the data landscape and claim your space as an AL enabaler in our organization.

**Step 1:**

	- What is the business problem I want to solve?
 
	- Can/should my problem be solved using GenAI?
 
	- What are the risks, both business risks inherent to the project, and the risks of the deployed model’s existence?
 
	- What are the main deliverable?
 
	- What are the success metrics and KPIs?
  
**Step 2:**

	- Who should be on my data governance team?
	  
	- What are our data governance policies?
	  
	- Which policies already exist around data usage, accessibility , and quality that align with organizational goals and regulatory requirements?
  
- **Ask your expert:**
  
	- What are the top-of-mind concerns you have about this project and why?
   
	- What have we done in the past that similar?
   
	- What do I need to know that I’m not asking about?


**Step 3:**
  
	- **Project Manager must know**:
  
		- Data source
	   
		- Data format
	
	 	- Frequency of data updates
	- **Questions:**
		- What data do I have access to?
	   
		- What additional data do I need?
	
	 	- What data do I have?
	
	  	- What GenAI model would best suit that data?


**Step 4:**

	- **Project Manager must know**:
 
		- Accurate data

		- Clean data
  
		- Ethically-sourced data 
	- **Questions**:
		- How suitable is the data?
		  
		- How clean is the data?
		
		- What data governance areas must be considered?

**Step 5:**

	- What milestone are we working towards?
 
	- How can we safeguard the data?


**Step 6:**

	- Which model or customization methods math the problem and the data?
 
	- What cost should we consider of those that match?

 	- Which of the models are specifically best suited?
	
 	- Which trained models perform best?  
	
 	- How does the model perform against the metrics and KPIs I set in the beginning?
	
 	- What are model implications in regard to governance, fairness, bias, et?
	
 	- Is the model bias?
	
 	- Does it give a marginalized group a disadvantage? 
	
 	- Does the model predict something private?
	
 	- Can the model be revers engineered from input output pairs such that tge output might risk exposing sensitive data?
  
	- Relationship between Problem, Data and Model’s performance 

 	- Benefits could be in terms of efficiency, accuracy, speed, or the ability to perform tasks that human can’t do as effectively.

  
**Step 7:**

	- How can we stay on track and iterate?
 
	- Which metrics will be most effective in understanding the model performance? 
 
**Recommendation:**
	- Think about documentation things such as performance tracking and running A/B tests.

 	- Select a number of metrics to get a comprehensive understanding of your selected model’s performance.
	
 	- Assess Metrics can be: response time, accuracy, fairness and bias, robustness, resource efficiency, resource efficiency, generalization ability and more. 


**Step 8:**

	- How can we celebrate current wins?

# 26.06.2024 GenAI in Project Management: Intro: Lesson_1
- How AI can alter how we do our jobs?
	- Efficiency and speed comes first.
	- Risk management
	- The third one is decision making
 - AI brings speed, efficiency, and data-driven decision making to the table, making it a game changer in project management.
 -  To leverage that, you need to focus on how your role will be redefined and it will be in four dimensions. Adaptability, soft skills, application of AI, and our capacity to unlearn. in breifly: 
	 - Dimension is adaptability
	 - Dimension is soft skills
	 - The use of AI tools will give you superpowers
	 - Learning to unlearn
 -  








# 23.06.2024 Project Management: Planning: Lesson_6
- Plan schedule management --> Schedule Management Plan contenet --->
	- How to define Activity Diagram?
	- How to define the sequences?
	- What are the Units for measurements?
	- What are the Tools? How to develop our schedule?
	- How many day? what are the formats reports?
	- What are the procedures link?
	- How to control the project?
- What is the main tools to Define Activity?
	- Decompose/decouple then reach to the activity. And then reach out to the **Activties**
 -  Inside the actvity, therer is "**Activity Attributes**" that is containing **details about the activity**.
 -  Then we move on the Sequence Activity ---> Network Diagram between Activities.
 -  Predecessor and Successor
 -  Every activity except the first and last should be connected to at least one predecessor and at least one successor.
 - Precedence Diagramming Method (PDM): is a technique used for constructing a schedule model Activities are represented by nodes The most common method to draw network diagrams.
-  Finish-to-Start (FS): Definition: The successor activity cannot start until the predecessor activity has finished.
- Example:
	- Activity A: Complete requirements gathering.
	- Activity B: Start designing the system.
	- Explanation: You must finish gathering all the requirements before you can start designing the system.
- Finish-to-Finish (FF) Definition: The successor activity cannot finish until the predecessor activity has finished.
- Example:
	- Activity A: Develop the backend API.
	- Activity B: Complete the integration testing.
	- Explanation: Integration testing cannot be completed until the development of the backend API is finished.
Start-to-Start (SS) Definition: The successor activity cannot start until the predecessor activity has started.
- Example:
	- Activity A: Start developing the frontend interface.
	- Activity B: Start developing the backend API.
	- Explanation: You can start developing the backend API as soon as the development of the frontend interface begins.
- Start-to-Finish (SF) Definition: The successor activity cannot finish until the predecessor activity has started.
- Example:
	- Activity A: Start deploying the new software version.
	- Activity B: Finish the old version’s support.
	- Explanation: The support for the old version cannot finish until the deployment of the new software version has started.

| Dependency Type | Example Activities|
| --- | --- |
| **Finish-to-Start (FS)** | A: Complete requirements gathering \n B: Start designing the system |
| **Finish-to-Finish (FF)**	| A: Develop the backend API \n B: Complete integration testing |
| **Start-to-Start (SS)** | A: Start developing the frontend interface \n B: Start developing the backend API |
| **Finish-to-Finish (SF)**	| A: Start deploying the new software version \n B: Finish the old version’s support |

- Examples of **Mandatory Dependencies** and **Discretionary Dependencies**
- **Mandatory Dependencies**: Definition: These are dependencies that are legally or contractually required or inherent in the nature of the work. They are often referred to as "hard logic" dependencies.
- **Discretionary Dependencies**: Definition: These are dependencies defined by the project team based on best practices, previous experiences, or preference. They are often referred to as "soft logic" dependencies.

| Dependency Type | Example Activities|
| --- | --- |
| Mandatory Dependencies | **Coding Before Testing**: Write the code for a feature -> Test the written code |
| | **Database Setup Before Application Deployment**: Set up the database schema -> Deploy the application |
| | **Requirements Gathering Before Design**: Complete requirements gathering -> Start designing the system |
| Discretionary Dependencies | **Frontend Development Before Backend Development**: Start developing the frontend interface -> Start developing the backend API |
| | **User Training Before Final System Deployment**: Conduct user training sessions -> Deploy the final system |
| | **Prototype Review Before Detailed Design**: Review the prototype with stakeholders -> Develop the detailed design |

| Dependency Type | Example Activities|
| --- | --- |
| External Dependencies | **Third-Party API Integration**: Implement feature using a third-party API -> Availability and reliability of the third-party API |
| | **Compliance Approval**: Release the software -> Approval from regulatory bodies |
| | **Vendor Deliveries**: Install new hardware for the development environment -> Delivery of hardware by an external vendor |
| Internal Dependencies | **Feature Development Sequence**: Develop core authentication module -> Develop user profile management module |
| | **Code Review Process**: Write new feature code -> Conduct code review |
| | **Unit Testing and Integration Testing**: Complete unit testing for a module -> Start integration testing |

- A **Lead** is the amount of time a successor activity can be advanced with respect to a predecessor activity.
- A **Lag** is the amount of time a successor activity will be delayed with respect to a predecessor activity.
- **Law of ِDiminishing Returns** In a production process, as one input variable is increased, there will be a point at which the marginal per unit output will start to decrease.
- **Contingency Reserve**: Known - Unknown
- **Management Reserve**: Unknown- Unknown (Unforeseen Work)
- **What if scenario analysis** Process of evaluating scenarios in order to predict their effect, positive or negative,
on project objectives.
- This is an analysis of the question, What if the situation represented by scenario X happens?



# 14.06.2024 Project Management: Planning : Lesson_5
"Project Plan" is a comprehensive document that outlines how a project will be executed, monitored, and controlled. It serves as a roadmap for the project team, providing a detailed description of the objectives, scope, deliverables, timelines, resources, budget, and methodologies involved in the project. Here are the key components typically included in a project plan:
- Project Objectives and Goals: Clear statements defining what the project aims to achieve.
- Scope Statement: Detailed description of the project’s deliverables, boundaries, and inclusions/exclusions
- Project Schedule: Timeline with key milestones, deadlines, and phases of the project.
- Resource Plan: Identification and allocation of resources such as team members, equipment, and materials.
- Budget Plan: Estimation of costs, including a detailed budget breakdown.
- Risk Management Plan: Identification of potential risks, along with mitigation strategies and contingency plans.
- Stakeholder Management Plan: Identification of stakeholders and strategies for effective communication and engagement.
- Quality Management Plan: Standards and criteria to ensure the project deliverables meet the required quality.
- Communication Plan: Protocols and methods for internal and external communication throughout the project.
- Change Management Plan: Procedures for managing changes to the project scope, schedule, or budget.
- Procurement Plan: Strategies for acquiring necessary services and products from external suppliers.
- Project Controls: Mechanisms for monitoring, tracking, and reporting project progress and performance.

Breifly, The project plan is a dynamic document that can evolve as the project progresses and more information becomes available. It serves as a critical tool for project managers to ensure that all aspects of the project are aligned and that the team is working toward common objectives.

# 04.06.2024 Project Management: People : Lesson_4
- SF: A logical relationship in which a successor activity cannot finish until a predecessor activity has started. Start of the new shift of the security guard signal the finish shift of the current security guard.
- FS: A logical relationship in which a successor activity cannot start until a predecessor activity has finished. Drying the car not start until Car is washed.
- SS: A logical relationship in which a successor activity cannot start until a predecessor activity has started. Concentrate flooring can not be started until you start mixing concentrate.
- FF: A logical relationship in which a successor activity cannot finish until a predecessor activity has finished. Broadcasting of a match cannot finish until the match is finished
- A **Lead** is the amount of time a successor activity can be advanced with respect to a predecessor activity.
- A **Lag** is the amount of time a successor activity will be delayed with respect to a predecessor activity.
- **PDM** is graphical representation of the logical relationships, also referred to as dependencies, among the project schedule activities.
- Activities that have multiple predecessor activities indicate a path convergence.
- Activities that have multiple successor activities indicate a path divergence.
- **Law of diminishing returns**: In a production process, as one input variable is increased, there will be a point at which the marginal per unit output will start to decrease.
- Contingency Reserve --> Known Unknown
- Management Reserve --> Unknown Unknown (Unforeseen)
- **Critical Path Method (CPM)**: is a Tools and Technique to reach out to Schedule Baseline.
- Schedule Network Diagram is an output from Sequence Activity.
- Sequence of activities that represents the longest path through a project, which determines the shortest possible project duration.
- The longest path has the least total float usually Zero.
- Sequence of activities that represents the longest path through a project, which determines the shortest possible project duration.
- The longest path has the least total float—usually Zero.
- There can be more than one critical path
- The critical path can change
- The critical path has Zero float
- A path with negative float means you are behind schedule
- **Total float**: the amount of time that a schedule activity can be delayed or extended from its early start date without delaying the project finish date Float=LS-ES , Float=LF-EF
- **Free Float**: the amount of time that a schedule activity can be delayed without delaying the early start date of any successor or violating a schedule constraint.
- There can be more than one critical path
- The critical path can change
- The critical path has Zero float
- A path with negative float means you are behind schedule . As the project manager, your job is to compress the schedule and eliminate negative float. Negative total float is caused when a constraint on the late dates is violated by duration and logic.

- **Resource Leveling**:
	- Can be used when shared or critically required resources are over allocated,
	- Can often cause the original critical path to change.
-  **Resource smoothing**: This is about balancing the use of resources throughout the project. Do not use 8 forces one day and 2 forces one day. Move the activities in such a way that the use of energy is almost the same in all days.
-  **What if scenario analysis**: Process of evaluating scenarios in order to predict their effect, positive or negative, on project objectives. This is an analysis of the question, "Whatif the situation represented by scenario X happens?"
# 30.05.2024 Project Management: People : Lesson_3
- **Plan Scope Management**
- The process of creating a scope management plan that documents how the project scope will be defined validated and controlled.
- The key benefit: providing guidance and direction on how scope will be managed throughout the project.
- The components of a scope management plan include:
	- Process for preparing a **Project Scope Statement** (PSS),
	- Process that enables the creation of the **WBS** from the detailed project scope statement,
	- Process that establishes how the **Scope Baseline** will be approved and maintained
	- Process that specifies how **formal acceptance** of the completed project deliverables will be obtained
- **Requirements Management Plan**
- Components of the Requirements Management Plan can include but are not limited to:
	 - How requirements activities will be **planned**, **tracked** and **reported**,
	 - Configuration management activities such as how **changes** will be initiated how **impacts** will be analyzed how they will be **traced**, **tracked** and **reported** as well as the authorization levels required to approve these changes.
	- Requirements **prioritization** process,
	- Metrics that will be used and the rationale for using them,
	- Traceability structure that reflects the requirement attributes captured on the **traceability matrix**.
- Collect Requirements is The process of determining, documenting, and managing stakeholder needs and requirements to meet project objectives
- The key benefit of this process is that it provides the basis for defining the product scope and project scope This process is performed once or at predefined points in the project.
- Collect requirements
	- Facilitation:
		- Manufacturing industry, quality function deployment (QFD) is another example of a facilitated workshop technique that helps determine critical characteristics for new product development
		- QFD starts by collecting customer needs , also known as voice of the customer (VOC).
		- Needs are then objectively sorted and prioritized, and goals are set for achieving them
- **Scope Basline** = **Project Scope Statement** + **WBS** + **Work Package** + **Planning Package** + **WBS Dictionary**
- Work Package: A work package can be used to group the activities where work is scheduled and estimated , monitored , and controlled
- Decomposition is a technique used for dividing and subdividing the project scope and project deliverables into smaller, more manageable parts
- Work packages consists of nouns ” instead of actions.
- WBS is created with the help of the team (Team Buy in)
- Each level of the WBS is smaller piece of the level above.
- Some levels will be broken down to further than others.
- WBS includes only deliverables that are really needed.

- Rough order of magnitude (ROM) estimate in **initiating** and in the range of 25% to 75%.
- **Budget** estimating, at beginning of **planning**, 10% to 25%.
- Later in the project, as more information is known, definitive estimates could narrow the range of accuracy to 5% to 10%.

- The accuracy of a project estimate will increase as the project progresses through the project life cycle.
- Accuracy refers to the correctness
- Precision refers to the degree of exactness For example, an estimate of 2 days is more precise than sometime this week.

- **Schedule**
	- Predictive:
		- Step 1. Decompose the project scope into specific activities
		- Step 2. Sequence related activities
		- Step 3. Estimate the effort, duration, people, and physical resources
		- Step 4. Allocate people and resources to the activities based on availability
		- Step 5. Adjust the sequence, estimates, and resources until an agreed-upon schedule
-  **Sequence Activities** is the process of identifying and documenting relationships among the project activities.
-  The key benefit : Defines the logical sequence of work to obtain the greatest efficiency given all project constraints.
- Every activity except the first and last should be connected to at least one predecessor and at least one successor.
- **Precedence Diagramming Method (PDM)**
- PDM is a technique used for constructing a schedule model Activities are represented by nodes
- The most common method to draw network diagrams.
- A **predecessor** is an activity that logically comes before a dependent activity in a schedule.
- A **successor** is a dependent activity that logically comes after another activity in a schedule.
# 28.05.2024 Project Management: People : Lesson_2
- Prioritization schema are methods used to prioritize portfolio, program, or projectcomponents, as well as requirements, risks, features, or other product information. Examplesinclude a multi criteria weighted analysis and the **MoSCoW**(must have, should have, could have, and won’t have) method. 
- **PLANNING VARIABLES**:
- **Delivery**
   
 	- Planning begins with understanding the business case , stakeholder requirements , and the project and product scope.
   	- **_Product scope_** is the features and functions that characterize a product , service, or result.
       
  - **_Project scope_** is the work performed to deliver a product, service, or result with the specified features and functions.

# PLANNING VARIABLES 1 .Delivery:
| Project Scope | Product Scope |
| --- | --- |
| The work needed to create product of the project | Features and functions of the product of the project |
| Completion of a project is measured against the plan | Completion of product scope is measured against the requirements |	

- **Estimating**
- **Schedules**
- **Budget** 
# 27.05.2024 Project Management: People : Lesson_1
- **Sources of Conflict**:
	- Schedules
	- Project priorities
	- Resources
	- Technical opinions
	- Administrative
	- procedures
	- Cost
	- Personality
 -  Listening ctively involves acknowledging, clarifying and confirming, understanding, and removing barriers that adversely affect comprehension.

 - The project manager also needs to be aware of Student-Syndrome—or procrastination—when eople start to apply themselves only at the last possible moment before the deadline, and Parkinson’s Law where work expands to fill the time available for its completion.

- **Affinity grouping** involves classifyingitems intosimilarcategoriesor collections on the basis of their likeness. Common affinity groupings include T-shirtsizing and Fibonaccinumbers.
- A **function point** is an estimateof the amountof business functionality in an informationsystem. Function points are used to calculatea functional size measurement (FSM) of a softwaresystem
- **Wideband Delphi** is a variation of the Delphi estimating method where SMEscomplete multipleroundsof producing estimatesindividually, with a project team discussion after each round, until a consensusis achieved. For Wideband Delphi, those who created the highestand lowestestimates explaintheir rationale, following which everyonereestimates. The process repeats until convergenceis achieved. Planningpokeris a variation of Wideband Delphi.
- **Estimating**
  
	▶ Analogous Estimation:

	▶ Parametric Estimation:

	▶ Bottom-up Estimation:

	▶ Three Point Estimation:

- **Triangular distribution** is used when there is insufficient historical data or when using judgmental data.
- Three-Point Estimating
	- Most likely (tM)
	- Optimistic (tO)
	- Pessimistic (tP)
- Triangular Distribution
  
▶ (O + M + P) / 3

- Beta Distribution (PERT)
  
▶ (O + 4M + P ) / 6

- **Conflict Model**
  
▶1- Confronting problem solving: 

- Incorporating multiple viewpoints and insights from differing perspectives; requires a cooperative attitude and open dialogue that typically leads to consensus and commitment.
- This approach can result in a win-win situation.

▶Collaborating: 

▶2- Compromising/reconcile: 

- Searching for solutions that bring some degree of satisfaction to all parties in order to temporarily or partially resolve the conflict.
- This approach occasionally results in a lose lose situation

▶3- Smoothing accommodating: 

- Emphasizing areas of agreement rather than areas of difference.

▶4- Withdrawal avoiding: 

- postponing the issue to be better prepared or to be resolved by others.

▶5- Forcing/ direct:

- Pushing one's viewpoint at the expense of others; offering only win lose solutions, usually enforced through a power position to resolve an emergency.
- This approach often results to a win lose situation.

- **Powers of Project Manager**
	- Formal / Legitimate: This power is based on your position.
	- Reward: This power stems from giving rewards.
	- Penalty / Coercive: This power comes from the ability to penalize team members.
	- Expert:
		- People on the team defer to you or seek solutions from you because of your
		expertise.
		- Expert power is always earned and never assigned.
	- Referent: This power addresses the charisma, personality, and leadership qualities of the project manager.
# 09.05.2024 Project Management: Conflict Managemnet: Lesson_1
- **Causes of Conflict**
- Conflict occurs when actions and expectations differ. Actions result from a combination of:
	- Ingrained assumptions about life—group and individual
	- Espoused values reflect our ideals—group and individual
	- Immediate situation—perceived uniquely by each individual
- How well you manage conflict depends on **Your Skill** + **The Situation** + **Your Preferences**.
- **Principles of Conflict Management in Projects**
- The following nine principles demonstrate the influence conflict management can have on a project.
	- Unmanaged conflict can cause your project to fail.
	- Handling unmanaged conflict can use up all your time and energy.
	- Unmanaged conflict can destroy business relationships, so that future projects are also doomed.
	- Conflict is inevitable in the project environment.
	- Managed conflicts, however, can introduce better methods and products.
	- Effective project managers proactively manage conflicts.
	- There are many methods for resolving conflict.
	- Collaboration has the most potential for improving products, processes, and business relations.
	- Managing conflicts requires a vision, planning, implementation, and closeout—the standard PM process.
- **Conflict Management Balance**
- Managing conflict in projects requires maintaining a balance between the project's commitment and its environment.
	- Forming and executing the project's commitments:
		- Budgets—funds allocation and release
		- Deadlines—deliverables and milestones
		- Resources—assignment and fulfillment
		- Quality—features and value (“good enough”)
	- Recognizing the project environment:
		- Interactions—how people/groups communicate
		- Culture—what groups value and how they behave
		- Trust—the quality of personal/group relationships
		- Expectations—what people/groups believe they deserve.
- **The Conflict Management Process**
	- Prepare for Conflict: The first step in preparing for conflict is to identify the key players in the project whose expectations or concerns may differ from those of other key players. The next step is to identify the catalysts and depth of their differing expectations and concerns. Every issue uncovered that could have consequential effects on the project must be researched and understood.

	- Mitigate Hostilities: Ultimately, if a conflict is inevitable, the time and place for resolving it must be agreed upon mutually. The earlier a conflict is addressed, the less likely it is to grow to a level of damaging hostility. Throughout this process, the overall goals of the project may need to be continually reconfirmed.

	- Select Conflict Resolution Methods: There are five different modes of conflict resolution, as described later in this lesson. Choosing the appropriate mode should not be one-sided. All the key participants need to the involved in recognizing their automatic response to conflict and selecting the resolution method that will benefit the project and the participants' relationships most.

	- Follow Through: Like any other project management practice, planning and preparation are not enough. Successful conflict management requires the full participation of all the key players. Everyone involved must be motivated to share the responsibility for managing their conflicts. The actions needed for ongoing conflict management must be monitored and evaluated. The outcomes and shortcomings of the conflict resolution process must also be assessed.

	- Be Flixable: The complexity and long-range effects of project conflicts mean that conflict rarely can be rigidly controlled. Although planning for managing conflict is crucial, it must be flexible enough to adjust to changing perceptions and relationships throughout the conflict's life cycle.

- **Modes of Conflict Resolution**
- Thomas-Kilmann's Modes of Conflict Resolution model was designed to increase understanding of how an individual responds to a conflict. The model was developed in the mid-1970s and is still used today to generate an appropriate response to conflict. The five modes are competing, accommodating, compromising, collaborating, and avoiding. Each involves a level of assertiveness-interest in satisfying one's desires-and an independent level of cooperativeness-interest in satisfying the desires of others.

- **Competing = win/lose (high assertiveness, low cooperativeness)**
- Competing is used when quick action is required or when unpopular decisions involving vital issues require clear resolution. Aggression by the other party may also warrant a competitive response. However, competing is often viewed as a non-cooperative approach that can undermine the other party's trust.

- **Accommodating = lose/win (low assertiveness, high cooperativeness)**
- Accommodating is used to create goodwill and keep the peace, especially when dealing with a new and unfamiliar area of conflict. Like competing and avoiding, accommodating may be used for conflicts of low importance to save time. However, accommodating is often interpreted as a retreat rather than an overt strategy.

- **Avoiding = lose/lose (low assertiveness, low cooperativeness)**
- Avoiding allows time for tensions to ease and buys time for preparing a better strategy. Like competing and accommodating, avoiding may be used for conflicts of low importance to save time, especially for handling bigger issues. However, avoiding is often perceived as arrogance or fear, i.e., either the party does not think the conflict is worth their time and trouble or wants to avoid an inevitable loss. Avoiding conflict resolution does not mean that you always avoid responsibility. In fact, you may end up with excessive responsibility and no authority.

- **Compromising = moderate lose/moderate lose (medium assertiveness, medium cooperativeness)**
Compromising is used when the conflict is important enough to spend the time needed to reach an agreement through negotiation. If the parties are not evenly matched in power and skill, compromising can revert to competing and accommodating. Most compromised solutions are temporary, unlike collaborative solutions. However, compromising typically requires less time than collaborating.

- **Collaborating = win/win (high assertiveness, high cooperativeness)**
Collaborating is used to resolve important conflicts, especially those affecting relationships between groups. The predominant activities in collaborating are integrating solutions, matching perspectives, gaining commitments, and learning more about the other parties and the conflict itself.

- If used inappropriately, any of these modes will eventually cause increased conflict. No matter what mode you end up using, be sure to summarize the agreements reached and check with everyone before separating. 

- **The major tasks for collaboration to succeed are**:
	- Getting participation from the right representatives for all affected parties
	- Establishing a set of desirable outcomes and long-term intermediation
	- Reaffirming the power inherent in working together in good relationships
	- Reaffirming the potential benefits of conflicts as catalysts to develop better products and achieve higher performance
	- Neutralizing attempts at avoidance, accommodation, or competition
	- Focusing on commitments to action and follow-through, rather than dwelling on past injuries
- Although project managers are in the best position to facilitate successful collaboration, several barriers often prevent them from succeeding:
	- Reticence in the face of conflict is common in managers coming from occupations with low communication requirements.
	- Affiliation of the project manager with their primary group can bias the project manager's approach and alienate other parties.
	- Playing a more unbiased role and entertaining the views of others can make the project manager appear to betray their primary group.
	- The threat of being out-maneuvered by better negotiators, or those with higher authority, can discourage the project manager.
	- A fixation on revenge by any party may outweigh their interest in a continuing relationship.
	- The widespread effect of any culture change can put an unwelcome spotlight on the project manager.
- To be able to overcome these barriers, the project manager can use any or all of the following aids:
	- Training and practice in conflict resolution and mediation methods
	- The assistance of a trained mediator or facilitator
	- Support of a sponsor at a level higher than that of the participants
	- A visible set of conflict resolution rules to which all participants agree and comply in every encounter
	- A project progress chart of conflicts encountered, the outcomes of the resolution, and group improvement

# 08.05.2024 Project Management: Conflict Managemnet: Lesson_1
- “Conflict is any situation where your concerns or desires differ from another person's" according to Thomas and Kilmann (1974).
# Terms and Description:
| Terms | Description |
| --- | --- |
| Problem | Any threat to disrupt the project's performance |
| Risk | Problem that might occur |	
| Conflict | Problem that represents differing expectations |	
| Dispute | Specific facet of a conflict, symptom of conflict |	
| Issue | Specific question about a problem or conflict |
| Opportunity | Problem that benefits project |

# Conflict
| Command | Description | Schedule |  Requirements
| --- | --- | --- | --- |
| Problem | resource unavailability | work behind schedule | inaccurate requirements |
| Risk | future resource unavailability | future work slippage | future requirements disputes |
| Conflict | limited, shared functional resources | late deliverables | customers' disagreement |
| Dispute | unavailable design engineer	| delay of a dependent task | disagreement on pavement depth |
| Issue | resource request | rebaseline request | pavement standards clarification |
| Opportunity | resource replacement | task elimination | reduced requirements |
# 05.05.2024 Project Management: Leadership Skills: Lesson_3
- Leadership Styles changed based on below factored:
	- Leader characteristics (attitudes, moods, needs, values,
	- Team member characteristics (attitudes, moods, needs, values,
	- Organizational characteristics (its purpose, structure, and type of work performed);
	- Environmental characteristics (social situation, economic state, and political elements).
 - Hersey-Blanchard Situational Leadership Theory the mid 1970s
	 - Supportive: High, Directive High --- > Selling ---> Coaching
	 - Supportive: Low, Directive High --- > Participating ---> Supporting
	 - Supportive: High, Directive Low --- > Telling ---> Directing 
	 - Supportive: Low,  Directive Low --- > Delegating
- OSCAR Model
	- Outcome : identifies the long term goals of an individual.
	- Situation: current skills, abilities, and knowledge level of the project team member
	- Choices consequences: identify all the potential avenues for attaining the desired outcome and the consequences of each choice
	- Actions: An action commits to specific improvements by focusing on immediate and attainable targets.
	- Review: Holding meetings to ensure that individuals remain motivated and on track.
   
- **Leadership Styles: the primary styles**
	- **Laissez faire** (e.g., allowing the team to make their own decisions and establish their own goals, also referred to as taking a hands off style);
	- **Transactional** (e.g., focus on goals, feedback, and accomplishment to determine rewards; management by exception);
	- **Servant leader**(e.g., demonstrates commitment to serve and put other people first; focuses on other people s growth, learning, development, autonomy, and well being; concentrates on relationships, community and
	- **Transformational** (e.g., empowering followers through idealized attributes and behaviors, inspirational motivation, encouragement for innovation and creativity, and individual consideration);
	- **Charismatic** (e.g., able to inspire; is high energy, enthusiastic, self confident; holds strong convictions); and
	- **Interactional** (e.g., a combination of transactional, transformational, and charismatic)
- **Seven Forms of Waste**:
	- Transport
	- Inventories
	- Motion
	- Waiting
	- Overproduction
	- Over-Processing
	- Defects 
- **Principle of Lean Thinking** - Lean 7 Core Concepts
	- Eliminate Waste
	- Amplify Learning
	- Decide as late as possible
	- Deliver as fast as possible
 	- Empower the team
  	- Build integrity in
  	- Optimize the whole
- S word and aligning on Project Goals ---> **Strategic**
- **Techniques for Managing Dispersed Teams**
- Here is a brief overview of some of the key considerations necessary to ensure collaborative work environments when a team is geographically distributed.
  
- When team members are dispersed, without some means of bridging the gap, there is a greater chance of miscommunication, perception-driven conflicts, information siloes, and other issues that result when we lose the benefits of seeing body language and hearing the tone of communication. Time zone differences can further create challenges as team members might have to resort to e-mailing documents back and forth.

- There are several technology tools, communication techniques, and virtual workspaces that can help teams bridge the virtual gap. Video conferences and shared collaboration tools can help address the first challenge of lack of body language and tone. Online information repositories (e.g. **Wikis**) and persistent chat platforms (e.g. **Slack**, **MS Teams**) can overcome the challenge of working asynchronously.

- One thing that can positively contribute to a virtual workspace is a “**fishbowl window**,” which is a persistent video link between dispersed and distributed team members. Unlike a traditional video conference, which is used for timeboxed meetings, a fishbowl window provides an opportunity for remote team members to participate informally in discussions throughout the day, which increases the opportunity for osmotic learning.
- **Fishbowl Window**: A type of virtual workspace where videoconferencing services are made available at every location where virtual team members reside. Team members log in at the beginning of the day and use the virtual workspace to enhance communications among the team.
- 
- **Remote pairing** is also a technique that can influence a virtual workspace in a positive manner. Remote pairing is a type of non-solo work (e.g. pair programming) that is enabled using 1:1 collaboration tools. To maximize effectiveness, there should be a collaborative platform such as a shared whiteboard or document combined with real-time audio/video. Ideally, both participants are within near time zones so that neither party is inconvenienced by having to work too early or too late in the day.
- **Remote pairing** also involves videoconferencing and team members logging in at the beginning of the day. Remote pairing goes one step further and includes screen sharing, video links, and voice communication


- **A fool with a tool is just a more efficient fool**. Providing collaboration tools to teams but not training them on their usage or helping them define appropriate rules for their usage is a recipe for disaster.

- Today's teams are formed around a fundamental understanding: Change happens through projects. Organizations are undergoing a paradigm shift in which projects are no longer adjacent to operations but instead the driving force behind how work is done. The project portfolio drives disruption, innovation and expansion. And those projects are led by teams comprised of people with a variety of titles, tapping into a variety of approaches to deliver financial and societal value.
- This is The Project Economy—and it's the next generation of teams that will determine how well organizations perform.
- “When you're dealing with big corporations with rigid structures, the challenge is how to scale small, dynamic agile teams up into the mainstream,” says David Marsh, PhD, director, UK Ministry of Defence, London, England.

- According to the 12th annual State of Agile survey published by CollabNet VersionOne, 41 percent of organizations cite a lack of skills or experience with agile approaches as a major barrier. It's up to project managers to determine how to bridge the gap for teams that are agile-deficient or agile-resistant. Whether these gaps are caused by a lack of knowledge, an indifference to new approaches or a philosophical opposition, getting team members up to speed on agile approaches takes proactive and persistent engagement from start to finish.

- “Resistance stems from two things: One is a general resistance to change; the other is people's doubts about the benefits of agile when the methodologies they already follow work for them,” Mr. Gunatilaka says.

- Agile Obstacles
- The top challenges organizations cite for adopting and scaling agile:
	- 53% Organizational culture at odds with agile values
	- 46% General organization resistant to change
	- 42% Inadequate management support and sponsorship
	- 41% Lack of skills or experience with agile methods
	- 35% Insufficient training and education
	- 34% Inconsistent processes and practices across teams
	- 31% Lack of availability of business, customer or product owner
	- 30% Pervasiveness of traditional development methods
	- 24% Fragmented tooling and project-related data or measurements
	- 21% Minimal collaboration and knowledge sharing
		- Source: State of Agile, CollabNet VersionOne, 2018
  
- Project managers can do a lot to further their teams' agile progress—but it helps to have enterprise-wide support. Here are three ways organizations can encourage a culture of agile maturity:
- 1 Executive Support If C-suite executives attend an agile seminar, they're better poised to become agile advocates for the entire organization, says Rebecca West, PMI-ACP, leader, agile project management office, ShopperTrak, Chicago, Illinois, USA. “The first thing any organization adopting agile needs to do is make sure that upper management understands its benefits,” she says. “Without that top-level support, it's a struggle.”

- 2 Build a Network Organizations can establish communities that accelerate and sustain an agile culture across the enterprise. For example, developing online discussion boards or blogs can help celebrate agile achievements and promote growth. “That creates momentum around agile,” says Giorgio Lippolis, PMI-ACP, PMP, development team lead, Gallagher, London, England.

- 3 Require Leadership Organizations can help develop agile leaders—and encourage them to groom the next generation of internal agile champions. At Vauban IT Romania, the human resources department makes agile mentorship a necessary step for job progression, says Daniela Chiricioaia, PMI-ACP, PMP, senior project manager at the software development company. “That motivates project managers because they know that in order to advance, they have to share their knowledge of agile with others,” she says.

- IMPLEMENTING A CAMPAIGN
	- Here are tips I recommend for other organizations looking to get employee innovation campaigns started:
		- 1. Kick off with an emphasis on a safe and encouraging workplace. An environment that embraces failure will also encourage valuable ideas. People need to know that they have a team behind them to support the experimentation.
		- 2. Provide a portal for submitting ideas and for giving timely recognition and updates.
		- 3. Create a form or checklist with open-ended questions to help innovators think outside the box.
		- 4. Have a review board or program office to provide feedback and positive reinforcement.
		- 5. Appoint a committee or a mentor to assist in the initial idea presentation to senior management.
		- 6. Assign a project manager if the idea needs resources, funding or organizational communication.
		- 7. Track up-to-date KPIs on the program to report successes or issues.

# 24.04.2024 Project Management: Leadership Skills: Lesson_2
- **Dreyfus Model**
	- Situational Leadership
 		- **Novice**: at this skill level, the team members have a very shallow understanding and need very close supervision They need clear and unambiguous instructions that they follow almost mechanically.
   		- **Advanced beginner**: at this skill level, the understanding of the steps involved such that they can apply the same steps in similar context. The team members are able to complete simple tasks without supervision, but struggle where complex troubleshooting is required.
  		- **Competent**: at this skill level the team members have attained good understanding of the steps involved and are able to complete their tasks properly without supervision. They use conceptual models to solve and troubleshoot problems, make decisions and accept responsibility.
  		- **Proficient** : at this skill level, team members have gathered sufficient practice, experience and deep understanding of the subject. They see actions holistically big picture ’’) and routinely achieves high standards of Performance.
    
  		- **Expert**: this is the highest skill level. With lots of knowledge amassed, the team members achieve excellence and go beyond existing interpretations, rules and guidelines. They use their analytical capabilities and intuitions more often to identify and solve problems.

# 23,04.2024 Project Management: Acceptance Criteria: Lesson_1
- Length
- Conditions
- Entities & Variables
# 23,04.2024 Project Management: Estimation: Lesson_1
- Complexity
- Skillsets
- Clarity
- Dependencies
# 23,04.2024 Project Management: SPIDR Approches: Lesson_1
- My story is larg. Hoe to Split?
	- Spikes
	- Paths
	- Interfaces
	- Data
	- Rules 
- Focus on minimal valuable scope, then iterate & grow!
  
# 19.04.2024 Project Management: Development Team: Lesson_1
- Development Team Models:
	-  Drexler/Sibbet Team Performance model
 		- Step 1 : Orientation : why, team learns purpose and mission for the project, occurs at kickoff meeting or business case , or project charter
		- Step 2 : Trust building: who, who is on the project team, skills , abilities , key stakeholders
		- Step 3 : Goal clarification: what, team Elaborates high level project information , stakeholder expectations , requirements , acceptance criteria
		- Step 4 : Commitment: how, team define plans , include milestone ,release plans, high level budgets, resource needs
		- Step 5 : Implementation: detail plans , detailed schedule or backlog, team starts working together to produce deliverables
		- Step 6 : High performance : After team has worked together , they reach a high level of performance, and don t need much oversight. Synergies
		- Step 7 : Renewal: The deliverables , stakeholders, environment, project team leadership, or team membership may change.
		- If the past behavior and actions are still sufficient , or if needs to go back to a previous stage to reset the expectations and ways of working together. 
- Dr.Bruce Tuckman (Tuckman Ladder)
	-  **Forming**: This phase is where the team members meet and learn about the project and their formal roles and responsibilities. Team members tend to be independent and not as open in this phase.
 		- Excitement
   		- Anticipation
     		- Anxiety
       		- Optimism     
 	- **Storming**: During this phase, the team begins to address the project work, technical decisions, and the project management approach. If team members are not collaborative or open to differing ideas and perspectives, the environment can become counterproductive.
		  - Realitysetsim
		  - Frustration
		  - Dissatisfaction
		  - Adhustmwnt anexiety  
  	- **Norming**: In this phase, team members begin to work together and adjust their work habits and behaviors to support the team. The team members learn to trust each other.
		  - Shared Goals
		  - Team Cohension
		  - Coping
		  - Acceptance
	- **Performing**: Teams that reach the performing stage function as a well organized unit. They are interdependent and work through issues smoothly and effectively.
	  	- Teamwork
	  	- Cohensiveness
	  	- Leadership
	  	- Performance
  	- **Adjourming**: In this phase, the team completes the work and moves on from the project. This typically occurs when staff is released from the project as deliverables are completed or as part of the Close
Project or Phase process
	  	- Separtation Anxiety
	  	- Crisis
	  	- Dissatisfaction
	  	- Negativity
  	- **Next Step**
	  	- Options Explored
	  	- Skilled
	  	- Anticipation
	  	- Excitement
- **Leadership Skills**:
	 ▶ **1- Establishing and Maintaining Vision**
  
		 - Short and precise
		 - Bold and ambitious – but grounded in reality
		 - Simple language
  
	 ▶ **2- Critical Thinking**
		 - includes disciplined, rational, logical, evidence based thinking
  
	 ▶ **3- Motivation**
	- **1- Intrinsic versus Extrinsic Motivation**
		- Extrinsic rewards, such as salary
		- Intrinsic motivators are far longer lasting and more effective
		- 3 types of intrinsic motivators
			- Autonomy: flexible work hours, working from home, and work on self selecting and self managing
			- Mastery : being able to improve and excel
			- Purpose : Knowing the project vision allows people to feel like they are making a difference.
	- **2- Theory X, Y, Z**
		▶ Theory X: The assumption that employees dislike work, are lazy, dislike responsibility, and must be coerced to perform.
		
		▶ Theory Y: The assumption that employees like work, are creative, seek responsibility, and can be excercise self-direction.
		
		▶ Theory Z. individuals are motivated by self realization, values, and a higher calling

	- **3- Maslow s Hierarchy of Needs**
		- Physiological: food, breathing, water, sex, sleep,homeostasis, excretion
		- Safety: Security of body, employment, resources,moturity, the family, health, property
		- Love/Belonging: friendship, family, sexual intimacy
		- Esteem; self-esteem, confidence, achievement, respect of others, respect by others
		- Self-actualization: morality, creativity, spontaneity, problem solving, lack of prejudice, acceptance of facts
	- **4- Theory of Needs**
		- **David McClellan's** model states that all people are driven by needs of achievement, power, and affiliation
		- **Achievement**. People who are motivated by reaching a goal , are motivated by activities that is challenging , but reasonable.
		- **Power**. People who are motivated by power , are motivated by increased responsibility
		- **Affiliation**. People who are motivated by affiliation , are motivated by being part of a team.
	- **5 Hygiene and Motivational Factors**
		- Herzberg also identified hygiene factors related to the work, such as company policies , salary , and the physical
		environment
		- If hygiene factors are insufficient , they cause dissatisfaction
		- However, even if they are sufficient , they do not lead to satisfaction

  	▶ - **4- Interpersonal Skills**
		- A. Emotional intelligence
		  - Self-Awareness
			  - How do you affect the team?
			  - How does the team affect you?
		  - Self-Management
			  - Think before act
			  - Build Trust
		  - Social Awareness
			  - Be Empatheic 
			  - Employ active listening
		  - Social Skill
			  - Establish rapport
			  - Build effective teams
			  - Manage Attitude
		- B. Decision making
			- **B1 Unilaterally Decisions**
	  			**advantage** = being fast
	  			**disadvantage** = is prone to error, demotivate people
			- **B2 Group based decision making**
				**advantage** = Use of broad knowledge base of a group, increases buy in, increases commitment 
				**disadvantage** = time required, interruption to teamwork
			- **B3 diverge/converge pattern**
				- first individually to avoid the effect of senior or charismatic stakeholders
				- Then , when alternatives have been generated , the project team converges on a preferred solution
				- Roman voting , wideband Delphi estimating, and fist of five voting
			- **B4 For those decisions that are beyond the authority** team can analyze alternative , and escalate. This process aligns with don t bring me problems, bring me solutions,
		- C. Conflict management.
			- Keep communications open and respectful
			- Focus on the issues, not the people
			- Focus on the present and future, not the past
			- Search for alternatives together
# 13.04.2024 Project Management: Stakeholder : Lesson_2
- **Stakeholder Cube**:
	- It provides a model with multiple dimensions that improves the depiction of the stakeholder community as a
multidimensional entity and assists with the development of communication strategies.
- **Salience Model**: Describes classes of stakeholders based on assessments of their power (level of authority or ability to influence the outcomes of the project), urgency (need for immediate attention), and legitimacy (their involvement is appropriate).
- **Directions of influence**:
	- Upward: (senior management of the performing organization or customer organization, sponsor, and steering committee),
	- Downward: (the team or specialists contributing knowledge or skills in a temporarycapacity),
	- Outward: (stakeholder groups and their representatives outside the project team,such as suppliers,government departments, the public, endusers, and regulators), or
	- Sideward: (the peers of the project manager, such as other project managers or middle managers who are in competition for scarce project resources or who collaborate with the project manager in sharing resources or information).
- Stakeholder Register:
	- Identification information.Name, organizational position
	- Assessment information. Major requirements, expectations,
	- Stakeholder classification. Internal/external, impact/influence/power/
 - Asuumption and constrain ---> Assumption log
 - **Stakeholder Engagement Assessment Matrix**:
- **Unaware**: Unaware of the project and potential impacts
- **Resistant**: Aware of the project and potential impacts but resistant to any changes that may occur as a result of the work or outcomes of the project These stakeholders will be  unsupportive of the work or outcomes of the project.
- **Neutral**: Aware of the project, but neither supportive nor unsupportive
- **Supportive**: Aware of the project and potential impacts and supportive of the work and its outcomes.
- **Leading**: Aware of the project and potential impacts and actively engaged in
ensuring that the project is a success.
- C represents the current engagement level of each stakeholder and D indicates the level that the project team has assessed as essential to ensure project success ( Desired).
- The gap between current and desired for each stakeholder will direct the level of communications necessary to effectively engage the stakeholder
- The closing of this gap between current and desired is an essential element of monitoring stakeholder engagement
- Stakeholder engagement plan may include but is not limited to specific strategies or approaches for engaging with individuals or groups of stakeholders
	- introduce the project
	 - elicit their requirements
	 - manage expectations
	 - resolve issues
	 - Prioritize
	 - make decisions
	 - soft skills
	 - leadership skills
	 - Problem Solve
	 - Communication
- Work Performance Data (Input) ---> Work Performance Information (Output)


 
# 14.04.2024 Project Management: Conflict Mnagement : Lesson_1
- There are five general techniques for resolving conflict, each with a best time and place for use:
	- 1. Withdraw/Avoid: In this scenario, the project managers avoid or postpone the issue until they are better prepared to address it or let it be resolved by others. This technique is best for low-stakes, non-pressing situations.
	- 2. Smooth/Accommodate: If the number one goal is to maintain the harmony or relationship of the team, this approach might be best. One party concedes their position and instead emphasizes areas where differing parties actually agree. “Project leaders do not always have direct authority over conflicting parties, so instead of demanding an agreement, they’ll need to use people skills, such as emotional intelligence, leadership, and influence, to nudge the parties toward a resolution,” Mr. Clemens says.
	- 3. Compromise/Reconcile: This approach involves searching for solutions that bring some degree of satisfaction to all parties in order to at least temporarily or partially resolve the conflict. But beware that this technique occasionally results in a lose-lose situation.
	- 4. Force/Direct: In this approach, one party pushes their viewpoint at the expense of others, offering only win-lose solutions. This option is often enforced from a position of power to resolve an emergency. “For example, when dealing with a potentially dangerous work situation involving the proper processes for protecting individuals from falling off a building on a construction site, the approach may be directive and, if necessary, dictatorial,” Mr. Clemens says.
	- 5. Collaborate/Problem-Solve: This approach seeks to incorporate multiple viewpoints and insights from differing perspectives. To reach a consensus, all parties must have a cooperative attitude and open dialogue. While this technique typically requires more effort, it can result in a win-win situation. “If the issue is over providing funds for the next project phase or arranging teamwork priorities, a more collaborative approach may work better,” Mr. Clemens says.
- It’s up to project leaders to determine which resolution technique is right for the conflict at hand. “Project managers may play a number of roles, from facilitators to decision-makers,” Mr. Clemens says. “The specific role depends on the individuals involved, the team dynamics, and the specific conflict.”
- For example, project leaders should take into account the intensity of the conflict, the time pressure for resolving it, the relative power of the people involved, and the importance of maintaining good relationships.
- But no matter how a conflict is handled, it’s important to keep in mind the ultimate goal: project success. Because humans execute projects, “our perceptions, risk tolerance and emotions come into play, causing the need to adjust agreements to reach common goals and objectives,” Mr. Clemens says. “It is in the establishment of these objectives that we, as humans, negotiate to meet our individual needs within the understood common goals.”   

# 13.04.2024 Project Management: Stakeholder : Lesson_1
- The name of the process starts with the **Plan**. Ex: **Plan Stakeholder Engagement**
- **Plan** is answer to "**How To...**"
- The name of the document or artefact, the word Plan is moved to the end of the name. ex: **Stakeholder Engagement Plan**
- More details / Planning for more details ---> Progressive Elaboration
- Data Representation approches
	-  Power/Interest Grid, Power/Influence Grid, Or Impact/Influence Grid.
 	- Stakeholder Cube
  	- Salience Model
  	- Directions of Influence
  	- Prioritization
# 07.04.2024 Project Management: Agile : Lesson_6
- Stakeholder Performance Domain - 1.Identify
	- Input
 		- Project Charter
   		- Business documents
     			- Business case
       			- Benefits Management Plan
       		- Project Management Plan
         		- Comm mng plan
           		- Stakeholder Engagement Plan
                - Project Documents
             		- Change Log
                	- Issue Log
                 - Requirments documentation
                 - Agreements
                 - Enterprise Environmental Factor
                 - Organizationaö Process Assets        
 	- Tools & Techniques
  		- Expert Jug´dgment
    		- Data Gathering
      			- Questionnaires and Surveys
         		- Brainstorming
           	- Data Analysis
           		- Stakeholders Analysis
           	 	- Document Analysis
          	- Data Representation
          		- Stakeholder Mapping/Representation
  		- Meetings           
  	- Outputs
  		- Stakeholder Register
  	 	- Change Request
  	  	- Project mng Plan
  	  	- Reuirements Management Plan
  	  	- Comm Mng Plan
  	  	- Risk Mng Plan
  	  	- Stakeholder Mng Plan
  	  	- Project Documents Updates
  	  		- Assumption Log
  	  	 	- Issue Log
  	  	  	- Risk Register       
# 24.03.2024 Project Management: Agile : Lesson_5
- **Tips**:
	- **Business Case**: it is including the "Why this project is selected" and "How much is the net present **value** and **payback period**".
 	- **Refactoring**: in software engineering refers to the process of restructuring existing code without changing its external behavior. The main goal of refactoring is to improve the internal structure of the codebase, making it easier to understand, maintain, and extend while preserving its functionality.
  	- **Spike**: In software engineering, a "spike" refers to a time-boxed exploration or investigation aimed at gathering information, reducing uncertainty, or evaluating a specific technology or approach. Spikes are often used when there is a need to make an informed decision or gain a better understanding of a problem before proceeding with development.
	- **Cross-Funtional Team Member**: A cross-functional team member is an individual who possesses skills and expertise in multiple areas relevant to the goals and objectives of a team. In a cross-functional team, members come from diverse backgrounds, disciplines, and specialties, enabling the team to tackle complex problems or projects that require a range of skills and perspectives.
	- a business case is a document that provides justification for initiating a project. It outlines the reasons why a project is necessary, identifies its objectives, and evaluates its potential benefits and costs. A well-developed business case helps stakeholders understand the purpose and value of the project and serves as a basis for decision-making throughout the project lifecycle. Here are the key components typically included in a business case:
		- Executive Summary,
		- Introduction,
		- Project Objectives,
		- Scope,
		- Benefits,
		- Costs,
		- Return on Investment (ROI),
		- Risks and Mitigation Strategies,
		- Alternatives Analysis,
		- Recommendations,
		- Implementation Plan,
		- Governance and Approval 
- **Belbin Team Role Inventory**: The Belbin Test, or the Belbin Team Role Inventory, is a widely used psychometric assessment tool designed to measure individuals' preferred roles within a team. The Belbin Test aims to help individuals understand their strengths and weaknesses in a team context and facilitate better teamwork and collaboration.
- Here's how the Belbin Test typically works:
	- **Questionnaire**: Participants are asked to complete a questionnaire, often online, consisting of a series of statements or scenarios related to team behaviors and preferences. These statements may ask individuals to indicate how they would typically behave or react in certain team situations.
	- **Team Roles**: The Belbin Test identifies nine different team roles, each associated with specific behaviors, strengths, and weaknesses. These roles are:
		- Coordinator: Acts as a leader and facilitates team communication and decision-making.
		- Shaper: Provides direction and drive, challenges the team to improve, and overcomes obstacles.
		- Plant: Generates creative ideas and solutions, often thinking outside the box.
		- Monitor Evaluator: Provides critical analysis, evaluates options, and makes balanced decisions.
		- Specialist: Possesses specialized knowledge or skills critical to the team's success.
		- Implementer: Turns ideas into practical actions and plans, ensures tasks are completed efficiently.
		- Completer Finisher: Pays attention to detail, ensures high-quality work, and meets deadlines.
		- Team Worker: Promotes team cohesion, supports others, and resolves conflicts diplomatically.
		- Resource Investigator: Seeks opportunities, makes contacts, and explores external possibilities.
	- **Scoring and Feedback**: After completing the questionnaire, individuals receive a report or feedback indicating their preferred team roles based on their responses. The report typically highlights individuals' strengths and potential weaknesses in each role and provides insights into how they can contribute effectively to a team.
	- **Team Building and Development**: The Belbin Test is often used in team-building exercises, training programs, and organizational development initiatives. By understanding their preferred roles and those of their teammates, individuals can better leverage their strengths, collaborate more effectively, and address any potential gaps or conflicts within the team.

# 22.03.2024 Project Management: Agile : Lesson_4
- Ohno Taiichi who is a Japanese industrial engineer and businessman. He is considered to be the father of the Toyota Production System, which inspired Lean Manufacturing in the U.S.
- **Seven Forms of Waste**:
	- Transport
	- Inventiories
	- Motion
	- Waiting
	- Overproduction
	- Over-Processing
	- Defects
-  **Principle of Lean Thinking**:
	- Eliminate Waste
	- Amplify Learning
	- Decide as late possible
	- Deliver as fast as possible
	- Empower the team
	- Build integrity
	- Optimize the whole
- **Test-Driven Development (TDD)**: XP follows the practice of writing unit test cases before the code is produced.    
- The benefit of following TDD is that the programmer is forced to write only that amount of code that passes the test, nothing more than that, since it is wasteful.
- **Feature Driven Development (FDD)**: is a lightweight Agile methodology that aims to build a software in increments of features or functionalities In terms of practical application,
- These features directly represent value added functionality that a user wants to use
- FDD is a flexible and customer centric approach to software development that can help teams deliver high quality software features quickly and efficiently
- **Delivery Cadence**: Refers to the timing and frequency of project deliverables. Projects can have a single delivery, multiple deliveries, or periodic deliveries.
- **Single Delivery**: Deliver at the end of the project
- **Multiple Deliveries**: Multiple components that are delivered at different times. New drug (sequential)= 1. preclinical submissions, 2. Phase 1 trial results, 3. Phase 2 trial results, 4. Phase 3 trial results, 5. registration, and then 6. launch. Update building security (separate delivery)= physical barriers to entry, new badges, new key code pads.
- **Periodic Deliveries**: **Like multiple** deliveries but **fixed delivery schedule**. A new software application have internal deliveries every two weeks, and then periodically release the deliveries into the market.
- **Continuous delivery**: delivering feature increments immediately to customers emphasis is on delivering benefits and value. Example; digital products and DevOps
- Project team that are stable.
- Remember, that of all documents that Agile teams look to produce, the charter is the first and also a must-have.
- Charters for Agile projects are no longer than a page or two in length.
- What, Why, Who, When, Where, How (W5H) acronym for the contents of a project charter.
- **Agile Contracting**:
- **Fixed Price**, but with Provision for Change in Scope in Future Iterations.
	- In this type of contract, the scope of the contract is reviewed before every iteration.
	- Since Agile teams do not permit changes during the middle of the iteration, the scope can be considered fixed during an iteration making it suitable for a fixed-price, fixed-scope delivery in the timeboxed iteration.
	- This concept works well provided that the customer (buyer) works in close collaboration with the seller for every iteration.
 - Cost Plus-reamburseible 
 - Time & Material
 - **Contract with Premature Closure Clause**:
	 - Since Agile projects are value driven, it is quite possible that the customer or user realizes that there is no value or ROI in continuing further with the project as outlined in the contract initially.
	 - At that point, the choice might be made to discontinue the project and not carry out the rest of the iterations.
	 - Any of the features that did not make it to the implementation stage yet are basically those that were considered
	unnecessary or of less priority.
	- Premature closure of a contract can cause hardships to the seller.
	- A clause could be included in the contract to pay a small fraction (say 15-20%) of the remaining contract in lieu of early termination to cover for its operational costs and maintaining healthy relationships for the longer term.
- **Fixed Fee and Not to Exceed Clauses**:
	- In case of premature closures of reduction in scope, the sellers may be adversely affected. To protect their interests, contracts could have a fixed-fee clause, which basically means that no matter what, the seller will get a fixed fee to cover their operational costs.
	- Similarly, if the project goes slower than the estimated schedule, the actual pay-out from the buyer could shoot up.
	- The not-to-exceed clause helps to protect the buyer by limiting the maximum amount that the buyer has to give to the seller.
- **Fixed Price per Story Point**:
	- Story points are unit of estimates for user stories. Once the definition of story points are formalized and agreed between the seller and the buyer, the seller could enter into a contract that uses a fixed rate per story point. So while the backlog of requirements could vary, the seller gets paid based on the number of story points it completes.
- **Multi Stage Contracts**:
	 - In the first stage the chosen vendor is asked to work on a T&M contract, collaborating with the buyer for a period of 3-4 weeks. The goal is to hash out an overall plan and gain enough knowledge to proceed with the next stage.
	 - In the second stage, the chosen vendor is asked work in a fixed-price contract to produce a proof of concept to establish their learning about the project. Based on the satisfaction of the buyer on the outcome of the proof of concept, the contract can either be terminated or proceed to the next stage.
	 - In the third stage the bulk of the Agile development happens. The buyer does not go beyond specifying a high-level objective of the project and anticipates rapid changes. The buyer and the seller enter into another T&M contract, with the buyer retaining authority to prioritize and deliver through a series of iterations closely collaborating with the vendor resource(s). The goal of this stage is to deliver the working software into production.
	 - In the fourth and final stage, the buyer could negotiate a fixed-price contract with the seller to provide warranty and fix any postproduction defects, if any.
- **Contract Extension and Payment Based on Delivery and Acceptance**:
	- Another variation of the contract is where, after each incremental delivery, the buyer pays out to the seller only when the acceptance test cases have been satisfactorily passed. If the delivery satisfies the buyer and the business value is obtained, the buyer (sponsor) can decide to renew or extend the contract for the next iteration. If the delivery does not deliver the desired result, they can choose to stop or modify the terms and conditions on the contract for the next iteration.
- **Story gathering Techniques**:
	- Persona: Identify a persona which is an imaginary representation of a user role The persona could have attributes like a name, address, age, a short description of his/her profile, his/her likes and dislikes, occupation, income level, a hypothetical photo and pretty much anything that is useful to represent the context and demographics (like colour, race, religion, etc that the user is representative of.
- **Fist of Five Voting**: Means the voter has serious objections and will block the proposal.
	- 0 fingers (closed fist): Means the voter has serious objections and will block the proposal.
	- 1 finger: Means the voter has strong reservations and wants to discuss issues and suggest changes that should be made.
	- 2 finger: Means the voter is moderately comfortable but has minor issues that may 2 fingers not need discussion.
	- 3 finger: Means the voter has a neutral standpoint because he likes some of it, but not all. 4 fingers – means that the voter is supportive of the proposal.
	- All 5 fingers (showof the full palm): Means the voter is in complete agreement with the proposal and will also promote it.
- **Expert in Earshot**: To exploit the benefits of osmotic communication and encourage building and retention
of tactic knowledge in the team, another technique used is expert in earshot which is putting junior team member in line of sight and within hearing distance of more experienced team members.
- **Swarming**: Agile swarming is when the entire team swarms around a single feature or a story, much the same way bees swarm around a flowering plant producing nectar. In other words,everyone works on the same story at the same time.
- **Shu Ha Ri Model**: The term Shu Ha Ri has its origin from a martial art called Aikido in Japan.
	- Shu (learn, follow the rule)
	- Ha (detach, break the rule)
	- Ri (transcend, be the rule)
- **Spikes**:
	- Spikes are used by Agile teams to conduct a brief experiment , test a hypothesis , perform option analysis and come to a conclusion.
	- After the experiment, the learnings and findings remain, but the spike code itself could be useless and in most cases is thrown away.
 - **Outcome of Spike**:
	 - Mitigate risks with uncertain technologies or domain
	 - Make better quality of estimates that can stand ground amid uncertainties
	 - Check feasibility of architecture or design options
	 - Help the team fail-fast
	 - Ascertain worthiness of the investment
# 21.03.2024 Project Management: Agile : Lesson_3
- Glossary
	- **Adaption**: Changing practices to fix processes that are not helping the work advance toward a goal.
 	- **Agile**: A term used to represent all the lightweight frameworks that shared the goals listed in the Agile Manifesto.
  	- **Inspection**: Close, continuous reviews of work being done to ensure that a project is moving toward the projected goal.
  	- **Product Owner**: The sole accountable party for the product the development team is building.
  	- **Scrum**:  A simple framework that is focused on doing just enough preparation in just enough time for development work to begin.
  	- **Scrum Master**: An individual that manages the Scrum process.
  	- **Scrum Team**: Consists of the product owner, Scrum master, and the development team.
  	- **Sprint**: A period of time in which the development team is expected to produce a potentially shippable product increment.
  	- **Transparency**: The idea that all aspects of a process must be visible to the people doing it.
  	- **Velocity**: The past performance of the development team. In other words, it is a measure of how much a team can accomplish during an iteration.
- **Story Mapping**: that takes a user centric perspective for generating a set of user stories. The basic idea is to decompose high level user activity into a workflow that can be further decomposed into a set of detailed tasks. It is computed as the sum of the story points (units of estimates) that a team can deliver in an iteration.
- **Good Product Backlog Characteristics**: DEEP
	- Detailed appropriately
 	- Emergent
  	- Estimated
  	- Prioritized
- **PBI Estiimation Units**:
	- Ideal days
	- Story Points   
- **Relative Size Estimation**:
- Absolut Vs Relative size estimation.
- **0, ?, infinity and pi interpretation in Planning Poker **
	- 0: Typically represents tasks that are considered effortless or trivial. Tasks that are straightforward and require minimal effort or complexity are assigned a value of 0. This indicates that the task is expected to be completed very quickly, often within the scope of a single iteration or sprint.
	- ? (Question Mark): Represents uncertainty or lack of information. When team members are unsure about the complexity of a task, they may use a question mark to indicate that they need more information or clarification before providing an estimate. This could be due to incomplete requirements, unclear objectives, or other factors that make it difficult to estimate accurately.
	- Infinity (∞): Represents tasks that are considered too complex or impossible to estimate within the current understanding. Tasks with an infinite estimate typically involve significant unknowns, dependencies, or uncertainties that make it impossible to predict the effort required accurately. These tasks may need to be broken down further or addressed through research or exploration before they can be properly estimated.
	- Pi (π): Some teams use "Pi" (3.14) to indicate that a task is relatively large or complex but not impossible to estimate. It falls between a finite value and infinity, suggesting that while the task is challenging, it can still be tackled with reasonable effort. It's essentially a placeholder for tasks that are larger or more complex than typical but not so extreme that they're considered infinite. 
- **Burn Down Charts**:  A Burn Down Chart is a visual representation used in project management, particularly in Agile methodologies such as Scrum, to track the progress of work completed against the work planned for a specific period, typically a sprint or iteration. The chart displays the remaining effort (or work) over time, allowing teams to visualize whether they are on track to complete the work within the allocated time frame.
- The Burn Down Chart typically consists of **two** axes:
- **Time axis** (usually horizontal): This represents the duration of the project or sprint, divided into time increments (e.g., days, weeks).
- **Work axis** (usually vertical): This represents the amount of work remaining to be completed, often measured in story points, tasks, or other relevant units of work.
- **Technical Debt** Or **Design Debt** Or **Code Debt**: In Agile development, technical debt refers to the implied cost of additional work that arises when code is developed or implemented in a way that sacrifices long-term quality and maintainability for short-term gains. It's a metaphor coined by Ward Cunningham, likening it to financial debt: just as financial debt accrues interest over time, technical debt accrues additional work that must be done in the future to correct or address issues introduced by taking shortcuts or making compromises during development.
- Consequences of technical debt
	-  Unpredictable tipping point
 	-  Increased time to delivery
	-  Rising development and support costs
 	-  Product atrophy
  	-  Decreased predictability
  	-  Underperformance
  	-  Universal frustration
  	-  Decreased customer satisfaction
 - Agile and the Kanban Method are as subsets of lean This is because they are named instances of lean thinking that share lean concepts such as
	- Focus on value,
	- Small batch sizes,
	- Respect for People
  	- Minimizing Waste
   	- Being Transparent
   	- Adapting to Change
   	- Continuously Improvement
- **Value Stream mapping**: SIPOC
	- Supplier
	- Inputs
	- Processing
	- Outputs
	- Customer  
- # 20.03.2024 Project Management: Agile : Lesson_2
- Artifacts:
	- Product Backlog
 	- Sprint Backlog
  	- Increment
  	- Product Vision Statement
  	- Product Roadmap
  	- Release Plan
-  Product Vision Statement
-  Product Roadmap
-  Product Release Plan
-  Iteration
- Produck Backlog Items
	- **Features**
 	- **Change to an existing feature**
	- **Defects**
 	- **Technical Improvement**: 
  	- **Knowledge acquisition work**:
  	- **Other work the PO deems valuable**
- **User Stories Attribute** ---> INVEST
	- Independent
	- Negotiable
	- Valuable
	- Estimable
	- Small
	- Testablt
- Team Agreements - **Definition of Done**
- **DO**
	- Take it in
- **DEVELOPMENT**
	- When I stop working on it I put it on READY (back to DO).
	- Initial tests are done internally by the developer before assigning to the clients.
	- Ask in the Daily who wants to test the User Story/assign already who is working on it & who is testing it - decide in the planning
- **TESTING**
	- The work has passed the testing criteria
- **Who is the Tester**:
	- Any of team member will be the tester and s/he should prepare a Test Scenario and test it and share the results with the team.
- **IN PROGRESS**: Developer is working on the ticket(s) and share progress in daily meeting.
- **ON HOLD**: Team needs clarification/response from other team(s)/Client(s)/3rd parties. There are Two options in ON HOLD status: 
	- On HOLD: Pending inside the team 
	- External Implementation : Pending for 3th party's response/feedback
- **RESOLVED**: Ticket(s) move to the Resolve status if test passed successfully OR client(s) provide the green light.  
- **CLOSED is DONE**
- In the Review session, team will check the Resolved ticket and share a general info about the US and sub-tickets then move to the CLOSE or DONE status.
	- All works specified in the Story has been done,
	- Hit the Acceptance Criteria
	- Have enough test coverage
	- QA approved
	- Acceptable in the target environment(s)
	- Presented in Review session
- Team Agreements - **Definition of Ready**
- User Story - **Refinement meeting** (bi-weekly) - everything needs to be reviewed and we can develop if team agree on the US and tasks/tickets.  Tickets should have some characteristics such as:
	- Clear Title,
	- Good enough description(s)/details that the team has no more immediate questions
	- Mention enough Test Scenario, if needed.
	- Refine done and assigned Story Point,
	- Work item MUST be estimated,
	- Sub-task(s), if needed.
	- Priority Set,
	- Sprint (start in which Sprint),
	- Work item MUST be small enough to be done in one iteration,
	- Documentation/attachments - depending on the situation, tables.
- **Maintenance Tasks: it is Ad-hoc task(s)**:
	- Clear Title,
	- Good enough description(s),
	- Priority Set,
	- Documentation/attachments - depending on the situation, tables.
 - **Agile Manifesto**:
- We are uncovering better ways of developing software by doing it and helping others do it.  Through this work we have come to value:
- **Individuals and interactions** over processes and tools 
- **Working software** over comprehensive documentation
- **Customer collaboration** over contract negotiation **Responding to change** over following a plan
- That is, while there is value in the items on the right, we value the items on the left more.
- **Sprint Planning Guide**
- **Attendees**: Scrum Team, including shared resources
- **Duration**: 2–8 hours, based on the Sprint length Frequency: Once per Sprint; first day of the Sprint
- **Inputs for Successful Planning**
	- Ordered (Prioritized) Product Backlog
	- What was completed in the last Sprint/Product Increment
	- Past performance of the Development Team (Velocity)
	- Development Team capacity for the Sprint Topics for Planning Discussion
	- What will be done in this Sprint?
- Product Backlog Items (PBIs) to select from the Product Backlog to create a Product Increment.This is solely the decision of the Development Team.
- The selected PBIs influences the Scrum Team in defining the Sprint Goal.
	- How to do the selected work to get it done?
- Knowing the Goal, the Development Team decides how to build the functionality  into a “Done” Product Increment.
- The Development Team defines the tasks it needs to complete the Product  Increment; tasks are decomposed into small pieces of a day or less.
- **Outcomes of Successful Planning**
	- Sprint Goal and what will be completed (PBIs)
	- How the work will be done (Plan)
	- Sprint Backlog
- **Daily Scrum Guide**
- **Attendees**: The Scrum Team, including shared resources and any interested parties: however, only Scrum Team members provide updates
- **Duration**: 15 minutes
- **Frequency**: Every day of the Sprint
- **Objective**: Inspect and Adapt to further progress toward the Sprint Goal
- **Structure**:
- **Each Development Team member will answer each question every day**:
	- What did I do yesterday to help meet the Sprint Goal?
	- What will I do today to help meet the Sprint Goal?
	- What impediments do I have that are blocking me (or the Development Team) from meeting the Sprint Goal?
- After the time-boxed Scrum, Team members can continue detailed discussions to answer  questions, solve problems, refine the design, or adapt the remaining Sprint work. 
- **Backlog Refinement Guide**
- **Attendees**: The Scrum Team, including shared resources and Subject Matter Experts if needed
- **Duration**: 1–4 hours, depending on the Sprint length
- **Frequency**: Once per Sprint, usually after the midpoint of the Sprint
- **Objective**: Inspect and Adapt the Product Backlog and PBIs to ensure targeted PBIs are ready for the next Sprint
- **Topics covered**:
	- PO presents the ordered backlog and identifies PBIs they’d like in the next Sprint.
	- Development Team asks questions and requests additional details if needed.
	- Any PBI that has enough information is sized by the Development Team in the session.
	- Create & Refining (Adding details to) PBIs
 	- Estimating PBIs
  	- Prioritizing PBIs   
- **Output**:
	- List of PBIs for clarification and the questions that need to be answered
- The Scrum Master ensures the event takes place and is well-facilitated. Scrum Master also  ensures the timebox is adhered 
- **Sprint Review Guide**
- **Attendees**: The Scrum Team, including shared resources, and Stakeholders
- **Duration**:  1–4 hours, depending on Sprint length
- **Frequency**: Once per Sprint, usually on the last day of the Sprint; it’s the next-to-last event  in the Sprint
- **Objective**: Collaboratively inspect the Product Increment and adapt the Product Backlog
- **Structure**:
- The Sprint Review is meant to be an informal collaboration on the current Product Increment and  to collectively update the Product Backlog with information from the Stakeholders that may influence  the Backlog contents.
- **Topics covered**:
	- PO provides an overview of the Sprint Goal and the PBIs that were selected.
	- Development Team demonstrates the Product Increment and answers questions.
	- PO shares the Product Backlog and the projection of completion based on current progress.
	- PO facilitates open discussion with the Stakeholders, capturing feedback and outside information that may help the Scrum Team.
	- PO adds appropriate feedback into the Backlog.
- The Scrum Master ensures the event takes place and is well-facilitated. Scrum Master also  ensures the timebox is adhered to.
- **Sprint Retrospective Guide**
- **Attendees**: The Scrum Team, including shared resources if they’ve been working on the  Team in the Sprint
- **Duration**: 1–3 hours, depending on Sprint length
- **Frequency**: Once per Sprint, this is the last event in the Sprint
- **Objective**: Inspect and Adapt the Team’s processes; select items for focused improvement
- **Topics covered**:
	- Inspect how the last Sprint went in regard to people, relationships, collaboration, processes, and tools.
	- Create an ordered list of major items that went well and those that could be improved.
	- Create a plan for implementing selected improvements to how the team works.
- The Scrum Master ensures the event takes place and is well-facilitated. Scrum Master also ensures the timebox is adhered to. As the process owner, the Scrum Master is an active participant in the event.
# 19.03.2024 Project Management: Agile : Lesson_1
- **Complexity**:
	- Complexity refers to the state of being intricate, diverse, and composed of many interconnected elements or parts.
	- In complex systems, there are often numerous interactions and interdependencies among the components, which can lead to emergent behaviors that are not easily predictable from the individual parts.
	- Complexity is often associated with dynamic systems, such as ecosystems, economies, or social networks, where changes in one part can have ripple effects throughout the system.
- **Complication**:
	- Complication, on the other hand, generally refers to the state of being difficult to understand or deal with due to being overly involved, convoluted, or having unnecessary intricacies.
	- While complexity can arise naturally from the interactions within a system, complication often arises from artificial or unnecessary additions, redundancies, or inefficiencies.
	- Complication can be seen as a form of complexity, but it typically implies a negative connotation, suggesting that the added intricacies make the system more difficult to manage, understand, or navigate.
- In summary, complexity refers to the inherent intricacy and interconnectedness of a system, while complication refers to additional difficulties or intricacies that have been introduced, often unnecessarily, making the system more convoluted or challenging to deal with.
- **The Agile Manifesto consists of four key values**
	- Individuals and interactions over processes and tools.
	- Working software over comprehensive documentation.
	- Customer collaboration over contract negotiation.
	- Responding to change over following a plan.
 - **Scrum Pillars**
	 - Transparancy
	 - Inspection
	 - Adaption 
# 13.03.2024 Project Management: Framework : Lesson_3
- **Project management**: The application of **knowledge**, **skills**, **tools and techniques** to project activities to meet project **requirements**. Project management refers to guiding the project work to deliver the intended outcomes. Project teams can achieve the outcomes using a broad range of approaches (e.g., predictive, hybrid, and adaptive).
- Project management is a combination of art and science.
- **Project manager**: The person assigned by the performing organization to lead the project team that is responsible for achieving the project objectives. Project managers perform a variety of functions, such as facilitating the project team work to achieve the outcomes and managing the processes to deliver intended outcomes.
- Interpersonal (Soft) Skills
	- Leadership
 	- Team Building
  	- Motivation
  	- Networking
  	- Communication
  	- Influencing
  	- Decision Making
  	- Political and Cultural awareness
  	- Negotioan
  	- Trust Building
  	- Conflict Management
  	- Coaching
  	- Teamwork
  	- Sociable and great team players
  	- Multitask
  	- Curiosity
  	- Empathy
  	- Analysis skill
  	- Foresight skill
  	- Problem solver skill
  	- Being flexible,
  	- Adapt to different people, cultures, environments, and situations
  	- Team leader, co-worker, and supervisor at the same time
- **Competence Triangle**: Ways of Working, Power Skills, Business Acumen.
- **Project Sponsor**: A sponsor is the person or group who provides resources and support for the project and is accountable for enabling success.
- Decision leadership that is outside of the authority
- Links the project team with the strategy and big picture
- Maintaining alignment with the organization s strategy
- Facilitates engagement and decision making and ensures that the skills and resources needed are available
- **Business partners**: Business partners are external organizations that have a special relationship
- **Organizational groups**: Organizational groups are internal stakeholders who are affected by the activities of the project team
- **Functional managers**: Functional managers are key individuals who play a management role within an administrative or functional area of the business
- **Project Phase**: A project phase is a collection of logically related project activities that culminates in the completion of one or more deliverables.
- **Milestone**. A significant point or event in a project, program, or portfolio.
- **Milestone Schedule**. A type of schedule that presents milestones with planned dates.
- PDCA Cycle (PlanDo Check Act) = Mr. Deming's cycle model = Kaizen Model = Continuous Improvement
- laissez-faire leader Example: 
	- Queen Victoria
 	- President Herbert Hoover (US)
	- Steve Jobs (Apple CEO)
	- Andrew Mellon (an American businessman- Father's Bank)
	- Warren Buffet (Berkshire Hathaway CEO)
# 12.03.2024 Project Management: Framework : Lesson_2
- **Strategy**: The overreaching that guide the direction of the organization.
- **Objectivea**: The process of decomposing strategic goals into strategic initiatives.
- **Initiatives**: The portfilios, programs, and projects, created to deliver a strategic goal.
- **Outputs**: The expected deliverable of a portfilio, program, or project.
- **Outcomes**: An end result or consequence of a process or project. Outcomes can include outputs and artifacts, but have a broader intent by focusing on the benefits and value that the project was undertaken to deliver.
- **Benefits**: A gain realized by the organization and beneficiaries through portfolio, program, or project outputs and resulting outcomes.
	- **Intangible Benefits**: A benefit that can not be directly measured objectively and instead relies on a proxy or representative, measure, or evaluation.
 	- **Tangible Benefits**: A benefit that can be measured objectively based upon evidence.
  	- **Benefit Owner**: the indivisual or group accountable for direction, related decisions, realization, and sustainment of benefits throughout the organization's benefits realization management life cycle.
  	- **Benefit Realization**: the intended beneficiarie's integration of gains resulting from the use of outputs of portfolios programs and projects.
  	- **Benefit Realization Management (BRM)**: The day-to-day organization and management of the effort to achieve and sustain potential benefits arising from the investment in portfolios, programs and projects
- **Value**:  The net result of realized benefits less the cost of achieving the benefits. The **value** may be tangible or intangible.
  	- **Customers** can define value as the **Ability to use** specefic **features** or functions of a product.
  	- **Organizations** can focus on **business value** as determined with **financial metrics** such as the benefits less the cost of achieving those benefits.
  	- **Societal value** can include the **contribution** to groups of **people**, **communities** or the **environment**. 
- **System for Value Delivery**: A collection of Strategic business activities aimed at building, sustaining, and/or advancing an organization.
	- Portfolios, programs, projects and operatiuons can all be part of an organization's system for value delivery.
- **Business Case**: is a document that including some item such as "Why we want do this Project?" . In other words, "it is result of feasibility study". 
	- Business Needs,
	- Analysis of the situation,
	- Recommendation,
	- Evaluation
 - **Project Benefits Management Plan**: How do you want to benefit from its benefits? In other words, the way to achieve this profit is mentioned in the Project benefit Management Plan. 
 	- Target benefits
	- Strategic alignment
	- Timeframe for realizing benefits
	- Benefits Owner
	- Metrics
	- Assumptions
	- Risks
 - Project Charter: it documents the high-level infomation on the project and on the product, service or result the project is intended to satisfy such as:
	 - Project Purpose
	 - Measurable project objectives abd related success criteria
	 - High-level requirments
	 - High-Level project description, boundries, and key deliverable
	 - Overal project risk,
	 - Summary milestone schedule,
	 - Preapproved financial resources
	 - Key stakeholders list
	 - project approval requirments
	 - project exit criteria
	 - assigned project manager. responsibility, and authority level, and
	 - Name and authority of the sponsor or other person(s) authorizing the project charter.
-  **Creating value**: Various components such as **portfolios**, **programs**, **projects**, **products**, and **operations** can create value.
-  **Organizational Governance Systems**:
	-  Works alongside the value delivery system to enable smooth workflows, manage issues, and support decision making.
	-  A governance framework can include elements of oversight, control, value assessment, integration among components, and decision making capabilities.
-  **Influences**
	- Enterprise Environmental Factors (EEFs)
		- External
		- Internal
 	- Internal Organizational Process Assets (OPAs)
		  - Processes, Policies, and Procedures
		  - Corporate Knowledge Base
- **Tailoring**
	- This guide and The Standard for Project Management are recommended references for tailoring because these standard documents identify the subset of the project management body of knowledge that is generally recognized as good practice.
 - 
# 11.03.2024 Project Management: Framework : Lesson_1
- Uncertainty is higher than Operation.
- Operation
	- Ongoing
	- Repetitave
	- Functional Manager
	- Projects Outputs
- **Project**: A **temporary endeavor** undertaken to create a **unique product**, **service**, or **result**. The temporary nature of projects indicates a beginning and an end to the project work or a phase of the project work. Projects can stand alone or be part of a program or portfolio. **Projects drive change**, **Projects enable business value creation**, **Project Initiation Context**.
	- A **Product** that can be either a component of another item
 	- A **Service** or capability (Business Function that support production)
  	- An **Improvement** in existing product or services line (Six Sigma)
  	- A **Result** as an outcome or document.
- **Why is the project defined?**
	- Meet Regulartory, Legal, or Social Requirments.
 	- Satisfy Stakeholder Requests or Needs.
  	- Implement or Change Business or Technological Strategies.
  	- Create, Improve, or Fix Product, Processes, or Services.
- **Projects & Strategic Planning**
	- As a result of Market Demand ---> EV
 	- As a result of strategic opportunity/buniness need --> Training Center
  	- As a result of Social need ---> Eliminate famine and hunger in the world, Access to safe drinking water
  	- As a result of Legal requirments ---> Recycle
  	- As a result of Technologies advan ---> High Tech companies, iPhone 15
  	- As a result of Customer request ---> New feature, ...
  	- As a result of Environemntal consideration ---> Enviroenmental Friendly
- **Product**: is an Artifact that is produced, is quantifiable, and can be either an end item in itself or components.
- **Product Management**: is the integration of people, data, processes, and business system to create, maintain, and evolve a product or service through its life cycle. 
- **Product life cycle phases** is a series of phases that represents the Evaluation of a product, from concept through delivery, grwoth, maturity and to retirement. In other words, it is consist of **Introduction**, **Growth**, **Maturity**, **Decline/Retirement**.
- **Impact on project delivery practices**: 
	- Markets shift from a single project delivery model to an ongoing delivery model
	- It led to an increase interest in product management life cycles for value delivery
- A Project Management Office (PMO) is an organizational structure that standardizes the project related governance processes and facilitates the sharing of resources methodologies, tools, and techniques
-  PMO has 3 types: **Supporting**, **Controlling**, **Directive**.
-  **Directive**
	-  Manages all Projects throughout organization
	-  Has the highest level of control over the projects
- **Supporting**
	- Recommends common terminology, templates and reporting and other procedures to be used on projects throughout the organization to promote consistency and streamline effort
- **Controlling**
	- Coordinates all projects within the organization
	- Prioritizes projects  
- **Diliverable**:
	-   Any unique and verified product, **result**, or capability to perform a service that is required to be produced to complete a **Process**, **phase**, or **project**.
- **Product**:
 	- An Artifact that is produced, is quantifiable, and can be either an End item in itself or a component item. Additional words for products are material and goods.
- **Program**: **Related projects**, subsidiary programs, and program activities that are managed in a coordinated manner to obtain benefits not available from managing them individually.
- **Portfolio**: Projects, programs, subsidiary portfolios, and operations managed as a group to achieve strategic objectives.
- Portfollio management is defined as the centralized management of one or more portfolios to achieve strategic objectives. The programs or projects of the portfolio may not necessary be interdependent or directly related.
- Purpose of Portfolio are "**Maximum Investment**", and "**Mitigate Risks**".
- Predictive (Plan-Driven)
	- Scope defined in detail early in the project Detailed plan are created. Waterfall - Classic
- Agile (Change-Driven)
	- Scope cannot be defined up front Smaller increments. 
- Hybird
	- Uses aspects of both predictive and agile
- **Product**: An artifact that is produced, is quantifiable, and can be either an end item in itself or a component item.
- **Project team** : A set of individuals performing the work of the project to achieve its objectives.
- **System for value delivery**: A collection of strategic business activities aimed at building, sustaining, and/or advancing an organization. Portfolios, programs, projects, products, and operations can all be part of an organization’s system for value delivery.
- **Value**: The worth, importance, or usefulness of something. Different stakeholders perceive value in different ways. Customers can define value as the ability to use specific features or functions of a product. Organizations can focus on business value as determined with financial metrics, such as the benefits less the cost of achieving those benefits. Societal value can include the contribution to groups of people, communities, or the environment.

# 06.03.2024 Introduction to Generative AI: Generative Applications : Lesson_4

# 06.03.2024 Introduction to Generative AI: Gen AI Models Types : Lesson_3

# 06.03.2024 Introduction to Generative AI: How Gen AI Works : Lesson_2

# 06.03.2024 Introduction to Generative AI: Define Gen AI : Lesson_1
- Gen AI has become a buzzword but what is it? It is a type of AI technology that can produce various types of content- including text, imagery, audio and synthetic data.
- Two very common questions asked are:
	- What is AI? AI is a discipline, like how physics is a discipline of science. AI is a branch of computer Science that deals with the creation of intelligent agents, and are systems that can reason, learn and act autonomously. Essentially, AI has to do with the theory and methods to build machines that think and act like humans. 
 	- What is the difference between AI and ML?  
# 23.08.2023 How to Lunch a Career in Project Management: Hard skills : Lesson_3
- You should be familiar with at least some of the popular project management methodologies like Waterfall, Agile, and Iterative.
- Project management software: Microsoft Project Tools, Primavera, Jira, monday.com
- Project Planning: Planning means figuring out how you're going to get the project done whether you plan everything upfront in traditional PM or plan as you go in an Agile approach.
# 23.08.2023 How to Lunch a Career in Project Management: Soft skills : Lesson_2
- Leadership
- Delegation
- Meetings
- Time Management
- Being Organized
- Problem Solving
- Negotiation: Negotiating and focusing on win-win outcomes is a crucial skill and one that, by the way, can help in all aspects of your life.
-  Strategic View
# 23.08.2023 How to Lunch a Career in Project Management: Quality: Lesson_1
- Personality
	- To be a natural organizer.
 	- To have an eye for detail.
  	- To be part optimist and part pessimist.
- Shock: Mismatch between expectation and reality.
- Denial: Holding onto old job behavior.
- Incompetence: Feeling of powerlessness.
- Acceptance: Letting go of past comforts.
- Testing: New behaviors and approaches.
- Learning: Rapid moral increase.
- Conscious Competence: Aware of using “New”.
- Integration: New behaviors and attitudes are internalized.
- Your job in the project is to bring the team together and encourage them to list the tasks, get them to estimate the times and the costs, and ask them to work out the running order and get 'em to think about how we can reduce the risks, get them to report on progress and to adjust the plan to get around any problems that have come up.
# 22.08.2023 PMP Interview: How to Approach: Lesson_1
- **Tell me about Time when your team had a challanging deadline to meet**.
	- With this one, an interviewer is really trying to understand how you've acted in the past. They want to hear a story, but they're really trying **to understand your thought process**.
 	- The best way to answer this question is to use the **STAR-L approach**.
  	- Situation: Give important and relevant details about the circumstances.
  	- Task: describe the main duties that you needed to complete.
  	- Action: outline the steps that you took to meet your goals.
  	- Result: share the results of your efforts.
  	- Learning: explain what you'd do differently or what you'd repeat.
 -  Every project team needs professionals just like you who can help them meet their deadline successfully.
 -  **Tell me about a time when things didn’t go as you had planned**.
 -  **Imagine that I am a senior executive who is sponsoring your project, and you are the project manager. I have just told you that the company is cutting budgets, and we need to trim 10% from the cost of your project. What should you do next?**
 	- The first step is to focus on flexibility and leadership.
  		- There are generally three ways to reduce the cost for a project.
    		- First, you may be able to get rid of unnecessary tasks and reduce your planned expenses. In other words, you can eliminate the waste.
      		- Next, you can reduce the scope for the project.
        	- And third, you can stretch out the timeline.
         - Align your actions with their needs.
- **Tell me about a time you manaed a project **     
# 17.07.2023 Fail Better: Closed loop systems: Lesson_2
- The key is to think about whether you're working in a closed loop system.
- A closed loop is when you're working in an environment that's rigid and unable to change. These systems usually have fixed inflexible processes. They don't change when you learn something new. These systems are not responsive and they don't create any feedback.
- E.X: The health care system in the United States, The system relies on fixed processes. There aren't a lot of practices in place to see if these processes still make sense.
- On the other hand, air travel in the United States is a good example of an **open loop system**. There are robust processes in place to make sure that any error is recorded. Each pilot benefits from other pilots' hard-learned lessons.
- That's why closed loop systems are much more dangerous than open loop systems. If the people within the system don't get good feedback, then they never make any progress.
- 
So if you're working in an organization, you have to create a mechanism for people to learn from their mistakes. You need to create an open loop system which learns from constant feedback. If you create a closed loop system, then your organization will be doomed to repeat the same mistakes. When making personal decisions, try to make sure that you understand when you've made a mistake, then use these smaller failures to learn from your mistakes. Try to get feedback from other people and apply any lessons that you've learned.
# 17.07.2023 Fail Better: Non/Linear failure: Lesson_1
-  **Linear failure** is when you make a mistake where you know the right answer. These are usually much easier to fix.
-  **Everything we know in aviation was because someone somewhere died. We have purchased these lessons at great cost**.
-  linear failure has a clear cause and you can improve your outcomes by getting feedback and learning from mistakes. That means that when you're working for an organization, you need to capture your failures. The more mistakes you make, the tougher it'll be to fail the same way.
-  Also, it means that at a personal level, you want to understand why you made mistakes. You must accept your mistakes and use them as opportunities to improve. If you don't acknowledge mistakes, then you're just in danger of repeating them.
-  With linear failure, the more mistakes you make, the more you can improve your outcomes. This is a huge advantage. It's not something you'll necessarily be able to do with nonlinear failures. These types of failures can have several causes. They're often difficult to predict or even recognize.
-  Most people think that failure is the opposite of success, but that's not usually the case.
-  Organizations that drive to make things faster and cheaper can sow the seeds for **nonlinear failure**.
-  One of the ways that you can avoid drifting into failure is to reconsider what it means to optimize.
-  Many organizations drift into failure by trying to make their processes more efficient. They streamline their organization. They want to know the exact expense to deliver their products. But maybe a better way to think about optimization is to think about the way your organization handles uncertainty. Instead of trying to perfect your process, you can build up extra resilience for employees to handle changes.
-  In fact, most personal failures come from a combination of several related events. So you might simultaneously lose your job and have a family member who needs care. So it wasn't linear, but instead a relationship between different events. So when you think about failure, you shouldn't imagine it as a different path from success. Instead, you should think of it as currents that drift towards failure.
-  You can drift into failure without really knowing that you're off course. One of the ways that you can avoid drifting into failure is to reconsider what it means to optimize.
-  Many organizations drift into failure by trying to make their processes more efficient. They streamline their organization. They want to know the exact expense to deliver their products. But maybe a better way to think about optimization is to think about the way your organization handles uncertainty. Instead of trying to perfect your process, you can build up extra resilience for employees to handle changes.
-  Linear failure can be traced back to one event. It could be a broken part or someone who made a crucial mistake.
-  Nonlinear failure is often a combination of several related events. Most of the time these are events that are difficult to predict. Most people approach nonlinear failure the same way as linear failure. They break the failure down into a series of steps and try to figure out the cause.
- So the best way to understand failure is to try and eliminate these traditional notions of figuring out what happened. Don't think of it in terms of blame or cause. Instead, think of failure as an opportunity to understand and improve. 

# 19.06.2023 Leadership_Masterclass: Styles for your boss: Lesson_10
- **Motivated, Not Competent**:  There'll be some things that you are motivated to do, but you're just not very competent. What is it that you are interested in but you're not very good at?
- **Motivated & Competent**: This is stuff that you are really good at, and you're also motivated to do.
- **Competent but not motivated**:  So this is the stuff where you're competent, but you're just not very motivated. So, what are the things that you are good at doing, but you're just a bit bored by?
- **Not Motivated, Not Competent**: where you're not competent and you're also not motivated. 
# 19.06.2023 Leadership_Masterclass: Situational Leadership Theory: Lesson_10
- Situational Leadership Theory, developed by Paul Hersey and Kenneth Blanchard in the late 1960s, is a widely recognized leadership model that focuses on the relationship between leadership style and the maturity or readiness level of followers. The theory proposes that effective leaders should adapt their leadership style based on the specific situation and the needs of their followers. According to Situational Leadership Theory, there are four primary leadership styles:
	- Directing (S1): In this style, the leader provides specific instructions and closely supervises the followers. The leader makes the decisions and tells the followers what to do.
	- Coaching (S2): In this style, the leader continues to provide guidance and direction but also seeks input from the followers. The leader explains decisions and encourages two-way communication.
	- Supporting (S3): In this style, the leader offers less guidance and allows followers to take more responsibility. The leader provides support and facilitates the development of followers' skills and confidence.
	- Delegating (S4): In this style, the leader provides minimal supervision, allowing followers to make their own decisions and take ownership of their work. The leader provides only necessary support and resources.
- The key idea behind Situational Leadership Theory is that the most effective leadership style depends on the readiness level of the followers, which is determined by their competence and commitment to perform a specific task or goal. The theory identifies four levels of follower readiness:
	- R1 - Low readiness: Followers are unable and unwilling or insecure about performing a task.
	- R2 - Moderate readiness: Followers are unable but willing or confident about performing a task.
	- R3 - Moderate to high readiness: Followers are able but unwilling or insecure about performing a task.
	- R4 - High readiness: Followers are both able and willing or confident about performing a task.
- Based on the followers' readiness level, the leader should adapt their leadership style accordingly. The leader's role is to assess the readiness of their followers and apply the appropriate leadership style to support their development and achieve the desired outcomes. Situational Leadership Theory provides a practical framework for leaders to adjust their behaviors and styles based on the needs of their followers, promoting flexibility and effective leadership in various situations.
# 19.06.2023 Leadership_Masterclass: Tannenbaum & Schmidt's Management Continuum Theory: Lesson_9
- According to Tannenbaum and Schmidt, leadership behavior can be placed on a continuum ranging from autocratic (manager-centered) to democratic (employee-centered) styles. They identified seven different leadership behaviors that lie along this continuum:
	- Manager makes the decision and announces it.
	- Manager makes the decision and then sells it to subordinates.
	- Manager presents the decision and invites questions or suggestions.
	- Manager presents a tentative decision, subject to change based on input.
	- Manager presents the problem, gets suggestions, and then makes the decision.
	- Manager allows the subordinates to make the decision, with the manager participating as a group member.
	- Manager delegates the decision-making authority to subordinates.
- The theory emphasizes that the appropriate leadership style depends on several factors, including the manager's personal leadership style, the competence and maturity of subordinates, and the situational context. As subordinates become more capable and experienced, the level of subordinate freedom and participation in decision-making can be increased.
Tannenbaum and Schmidt's theory suggests that leadership is not fixed but can be adapted and adjusted based on the circumstances and the development level of subordinates. It provides a framework for leaders to determine the appropriate level of involvement and decision-making authority to effectively lead their teams.
- Are things at the right level? Could they be pushed down a level? And also can you affect where your boss has put things? Can you encourage your boss to have things at the right level?
- How much to just do yourself when you're planning something or solving a problem?
- How much do you do yourself, and how much you involve your team?" So there are five levels really.
	- There's **Tell** where you just decide, and you just tell people.
 	- There's **sell** where you decide, and then you kind of convince them.
  	- There's **consulting** where you say, "I've got this plan. What do you think?" And you're actually prepared to change your plan a bit.
  	- Then there's **sharing** where you say, "I've got this problem.
  	- And then there's **delegating** where you say, "I've got this problem and I want you to do it.
# 18.06.2023 Leadership_Masterclass: Your boss's management style: Lesson_8
-  What I want to suggest to you is that you ask your boss to be a better boss.
	- Weekly meeting for --> We're asking them for concrete, easy things that they could do.
	- To involve you more in their decisions, particularly if you can give them a real example of something that they recently did and they didn't involve you.
	- Another thing you could ask them for is to allow you to do something or other without having to check first.
 	- Another thing you could ask for is for them to allow you to do things without having to report afterwards.
  	- You could ask them to thank you more.
   	- Another thing you could ask your boss for is to delegate something to you.
   	- Another idea is that you might ask your boss to not sit on stuff and then suddenly give it to you once it's become urgent. 
# 18.06.2023 Leadership_Masterclass: Personality types: Lesson_7
-  Four types of people:
	- Analytical: Top left, you've got the quiet, logical person. That's the analytical kind of engineers and accountants are quite often in that box, although not always. **You'd want to calmly go through all the details and facts with them, spreadsheets, that sort of thing.**
 	- Controllers: They're the sort of tough, decisive, you know, ballpark, just get on with it type of people. **You just want to cut to the point. You know, just three key reasons, bullet points, that sort of thing.**
  	- Enthusiasts: They are also outgoing, but they're much more emotional than the controllers. So enthusiasts love an exciting vision of the future. **Then everything's got to be fun. This is why we're doing it. You got to keep a bit of an eye on them 'cause they're quite disorganized, and just make sure that they don't drop any balls.**
   	- Amiables: These are the lovely caring people who are into things like trust and relationships and teamwork and that sort of thing.**You need to spend a bit of time with them. Get to know them, become their friend. Listen to them. Show that you actually care and make sure that they feel involved and that you're working as a kind of partnership with them.**

		- We've got two axes. And the first axis is extrovert to introvert. So we've got the really quiet people on the left and they are the ones who you would call introvert.  But they're the ones who they like to think. They like to listen rather than talk. They like lots of detail. That kind of person. The more cautious person. On the right you've got the mouthy, outgoing, decisive, just weighed in type people. And by the way, there's no right or wrong. It's just how people are.
 		- The other axis, which I've got from top to bottom. The top two I've got are the logical people. They like to have facts and reasons and numbers. And it's all down to logic. They're ruled by their head. The bottom two people are ruled by their heart. So their decision making preference is emotional. They're much more influenced by how other people feel, how they feel. So with them, they're ruled by their heart. Again, no right or wrong. People are just different.
   	- What type of person am I? which one am I at least most of the time because we can move around the boxes, of course, but you probably have a **home box**?
   		- Analytical person who loves **Detail**, **Attention to detials**, **Clever**? OR
   	 	- Controller person: I would say their strength is **decisiveness**. They're really good at making decisions. They **can function under pressure**. They **can do the tough jobs, the difficult tasks** OR
   	  	- Enthusiasts Person: I think their strengths are **vision** and obviously **enthusiasm**, the ability to **inspire other people** and also **creativity** comes from there. OR
   	  	- Amiable Person: Their strength is **relationships**. Everybody likes them. They're really **good at building up friendships**, even with customers and suppliers. They're **good listeners**, and they're **good at noticing things**. So they actually can make really good managers and leaders, and they're **good at caring**.
- Which one are you most of the time? Now, if you're stuck on this question, and you just can't think about, "oh, I just don't know," then a good question is to think **what** do you find most difficult and **who** do you find most difficult?
- Weaknesses of each types:
	- Analytical person 
		- if you're an analytical person, the weaknesses that you need to keep an eye on are that you might be too **cautious**, you know, because you hate change or uncertainty. So you'll tend to **resist changes**, and you'll resist **taking risks**, which can be a problem. Also, analyticals can't really operate without fact, and there are lots of environments in life where we don't have facts. The other problem with analyticals, sometimes, there are **oblivious to other people's moods**, **to other people's feelings**. So there is a risk that you'll be not very good at empathy, and that might be something that you want to work on and try to improve that.
  	- Controller person
  		- you might want to try **improving your patience** because controllers are often really impatient. I'm kind of laughing because this is me. I'm a controller. So, you know, trying to not be so impatient, and also controllers frighten some people because they come stamping and go, "have you done it yet? Why haven't you done it? What's the problem?" So try not to be **so scary**. I think everyone's a little bit frightened of their boss, even if their boss is really nice, but if you're a controller, there is a risk that you'll be a scary boss. So I want you to just think about that. Are you a scary boss? And also controllers **hate detail**, and sometimes that can be a problem. The other problem controllers have is they **hate being told what to do**, and (chuckles)this is so me. So controllers hate being told what to do, and if you are a controller, sometimes it's good to be told what to do. Sometimes you can learn from other people. So try to make the effort to at least give them a chance before you go, "nope, no, I'm not doing that." 
  	- Enthusiasts person
  		- what might be your areas for improvement? Well, they tend to be **disorganized**, and they **can't be bothered with detail**. So trying to make an effort to be a bit more organized, at least work with an analytical person and try to not find them too annoying (chuckles) because they will help you to become more organized, and they will probably do the detail for you, but sometimes you have to do the detail yourself. The other problem with enthusiasts is they do tend **to get bored easily**. So they flip from one thing to another, and sometimes you need a little bit of staying power to do something properly and to finish it off.
  	- Amiables person
  		-  If this is you, what do you need to do to improve? And their main issue is they're **too nice**. They tend to **avoid conflict**, and sometimes that can cost them. Sometimes you have to have the occasional bit of conflict. I think if you are a manager or a leader, sometimes you have to confront people, you know, poor performance or even just disagreements about direction. You have to fight your corner and say, "no, I think that's wrong. I think we should be doing this." So force yourself to confront people occasionally, when you're sure you're right. I think amiables also, **they don't like pressure**. They avoid any situation that involves pressure, and that can cost them too. So they don't really like dealing with unpleasant people. They **can't handle unpleasant people**, and sometimes I think you have to force yourself to deal with that unpleasant person or face up to them and deal with them. So there's some things to think about if you are an amiable.
- Which of the four types do you think you are?
- What do you need to become better at?
# 07.06.2023 Leadership_Masterclass: Ultimate Motiviator: Lesson_6
- Training People.
- Give them challenges.
- Give people variety.
- Find out what their skills are.
- Find out their future plans.
- Show them how their job matters.
- Agree large, longer term goals.
- Give people more freedom on certain tasks.
# 07.06.2023 Leadership_Masterclass: Feeling_Valued: Lesson_5
- How can we make each person who works for you feel valued?
- How can you male people feel important and feel valued?
	- Notice what people do, and thank them
	- Spend time with them
	- Show them how they make a difference
	- Give public recongnition
	- Give people ownership
	- Give them the job of coaching or training someone else.  
# 07.06.2023 Leadership_Masterclass: Feeling_of_Belonging: Lesson_4
- Do you feel that you work for company?
- Do you actually feel that you're part of the company? 
- Ways that you can do to make your team feel part of things:
	- Have a weekly Team Meeting
	- Have a meal together.
	- Think about your working environment 
	- Do activities outside work
	- Create Team challenges
# 07.06.2023 Leadership_Masterclass: Improve Security : Lesson_3
- How you can make your team feel more secure: 
	- You could spend time with people
	- Get to know them as people
	- Tell them about the big picture
	- Praising and thanking people
	- To be supportive about the things that they're less good at.
	- Have clear objectives for them, for their job.
	- To have clear rules.
	- Invest on people.
	- Encourage people.
# 07.06.2023 Leadership_Masterclass: Team Motivation Audit: Lesson_2
- Most Famous Managamenet Theory: Maslow's Hierachy of needs.
	- Survival (Level 5)
	- Security (Level 4)
	- Feeling of Belonging (Level 3)
	- Feeling Valued (Level 2)
	- Self-Fulfillment (Level 1) 
# 07.06.2023 Leadership_Masterclass: Leadership self-audit: Lesson_1
-  The real essence of a great boss is about being creative. It's about thinking about better ways to do things, and about perhaps a better direction of where we're going to go in the future. So it's about creating things, and then planning how you're going to make it happen, and then about shaping the process to make sure that it does actually go in the direction that you want. 
-  There are three things that a great boss should be doing, vision, systems, and people.
	- Sets a vison
	- Makes sure systems work effocoently
	- Make sure they have the right people
- So that's five ratings of yourself out of 10 
	- How clear is your vision?
		- How clear is your vision of where your company or your department or your team are actually going? What's the vision for the future?
	- Communicating this vision
		- Do your team know where we're going? What's the direction, what's the vision?
	- Efficiency of systems
		- How efficient are the systems at the moment in your area? And I don't necessarily mean computers. I mean just in terms of how it all fits together. Do things fall between the gaps? Are there overlaps? 
	- Your level of focus on systems
		- How good are you at standing back and thinking about the systems day-to-day, or do you just get drawn into all the action and the stuff that goes on?
	- People
		- I've kept them till last 'cause in a way, I think they're the most important. So how good are your people in terms of both the quality of the people, and also are they happy?  
# 02.05.2023 Leadership_for_Non_Mangers: lesson_5: Specific Characteristic of Leaders
- Leading by Design
	- **Lead by example**
		- Knowledge
		- Skills
		- Abilities
	- **Lead by Design**
		- Systems
		- Process
		- Culture
- "Leading by example shows the way, but leading by design creates a system that discovers the way. Those who lead by design do not invent, nor are they involved in the specific desisions to get the job done. Done well, such leadership creates an organization that takes us places we never imagined" Bill Barnet.
- Integrity: "The quality of being honest and having strong moral principles." Google Dictionary
- Leaders have Integrity: 
	- Educational Programs
	- Understand integrity
	- Have we been taught about integrity?
	- Who teaches us about integrity?
	- Integrity mismatch leads to stress
- What does Integrity look like?
	- Doing the right thing, **even if** it is hard.
	- Being honest, **even if** would be easier or more profitable to be dishonest.
	- Helping others who need or deserve help, **even if** others won't help them.
	- Treating everyone fairly, **even if** it would be so easy to cheat, especially if no one would know.
	- Giving up certain rewards, **even if** once again, no one would know
# 02.05.2023 Leadership_for_Non_Mangers: lesson_4: Leadership Styles
- **The Autocratic Leadership Style**
	- Include Others in the decision making process
		- Team feels involved
		- Create buy-in
		- Not for fast or small decisions
- **The Autocratic Leadership Style**
	- You make all decisions
	- Does Not include others
	- No input of opinions
	- Decisive and fast-moving
	- Less loyalty, support, and buy-in
	- Team doesn't feel involved
-  **The Laissez-Faire Leadership Style**
	- Lots of room
	- Hands-off leader
	- Can love freedom and trust
	- Or be very frustrated
	- Need a team that thrives with hands-off
- **The Strategic Leadership Style**
	- Focus on strategy and future
	- Understands competition
	- Sees opportunities
	- Ready to pivot
	- Focused on winning
	- Anticioates and undestand situations
- **The Servant-leader Leadership Style**
  	- Leader serves team
  	- what does team need?
  	- Lead by example
  	- Loyal following
  	- Perhaps not as competitive
  	- Help and empower
- **The Transormational Leadership Style**
  	- Inspiration, motivation, excitment
  	- Exiting trajectory
  	- High integrity and EQ
  	- The whole package
- **The Transactional (Managerial) Leadership Style**
  	- Focus on results
  	- Working within the system
  	- Tells you what you will do
  	- Authorities, penalties, rewards, title
  	- People know what they will get
  	- Know how to be successful      
- **The Bureaucratic Leadership Style**
  	- Strictly following rules
  	- Abiding by policies
  	- Not for innovation or flixible teams
  	- Trustworthy and prediczable
  	- If I underst the rules, I understand you
- **The Best Leadership Style**
  	- Depends on circumstances
  	- Circumstances can change
  	- What was their style(s)?
  	- What do you think your style is?     
# 02.05.2023 Leadership_for_Non_Mangers: lesson_3:The Very Bad Leaders
- Lack of trust
- Suspicious
- Discouraged
- Corecion and threats
- Questioning of motives
- Toxicity
- Great Leader
	- Satisfaction
	- Happy
	- Excited
	- Contribute
- Bad Leader
	- Paranoid#
	- Selfprotection
	- Unmotivated
	- Uncreative
	- Second guess
- Negetive feels
	- Unhappy
	- Looking elsewhere
	- Not engaged
	- Bad branding
- Leadership and shifting leadership had a huge impact on just about every aspect of the company.
 # 02.05.2023 Leadership_for_Non_Mangers: lesson_2: Leadership vs Management
- Leadership
	- Strategy
	- Vision
	- Leading and Persuasiving
	- Inspiring
	- Bigger picture
	- Gather informantion
	- on the road more
- Mangement
	- Carry out vision and strategy
	- Operational
	- Daily focus on teams
	- Daily focus on Projects
	- Deadlines, numbers, and reporting
	- Tactics
	- in the oofice more
- Leadership Generalization
	- Deponeds on size and culture
		- Persuader
		- Influencer
		- Visionary
		- Strategist   
# 02.05.2023 Leadership_for_Non_Mangers: lesson_1:Leadership
- Leadership can mean:
	- Personal growth
	- New challanges
	- Self-improvement
- Leadership:
	- Peter Drcker says that leaders have followers.
	- Warren Bennis says a leader is someone who turns vision into reality. 
	- Bill Gates says, leaders empowes others.
	- John Maxwell says that leadership is simply influence. 
	- Kevin Kruse: Leadership is a process of social influence, which maximizes the efforts of others, towards the achievement of a goal
- Leadership characteristics
	- Face
	- Decisions
	- Vision
	- Persuasive
	- SMART
	- Lucky 
# 01.05.2023 Project_Management_Foundations: lesson_12: Managing technologies
- Author Jeffrey Gitomer is quoted as saying, "You don't earn loyalty in a day, "you earn loyalty day by day." 
# 01.05.2023 Project_Management_Foundations: lesson_11: Addressing technical project challenges
- One, would this project be best managed by traditional or agile methods and why?
- Two, there is one requirement type that will likely be very important for this project, what type do you believe it will be and why? 
- Three, what do you believe will be the area or areas of change you most need to focus on? Technical tool change, process change or cultural change and why? 
# 01.05.2023 Project_Management_Foundations: lesson_10: Change in a technical project
- Former US president, Woodrow Wilson, is quoted as saying, "If you want to make enemies, try to change something."
-  To avoid fate, we need to focus on change in four dimensions.
	- First, there's change to the products we produce.
	- Next, focus on changing processes.
	- The third type of change to manage is system integration and maintenance changes. 
	- Finally, there is cultural or organizational change. 
# 01.05.2023 Project_Management_Foundations: lesson_9: Requirements
- Two types of requirements: functional and non-functional.
	- Functional requirements focus on what the system needs to deliver. Non-functional requirements focus on solution characteristics and how the technical component works, such as response time or how a system would be displayed on a green or color computer terminal.
	- Non-functional requirements are sometimes referred to as technical requirements.
- Here are four areas of non-functional expectations that need to be addressed in virtually every technical project. 
	- The first area is devices and the Internet of Things
	- The second non-functional requirements area to address is 24 by seven access.
	- The third non-functional requirement area to address is accessibility.
	- Finally, there are non-functional requirements relating to search engine optimization, or SEO.   
# 01.05.2023 Project_Management_Foundations: lesson_8: Waterfall vs. agile
-  Here are some considerations that indicate whether traditional or Agile approaches are appropriate for your technical project
	- First is the clarity of your requirements
	- The second consideration is the product you are producing.
	- Another consideration is the need for speed and the ability to break down your product into value producing pieces.
	- Finally, your organizational norms and practices may dictate whether Waterfall or Agile is best.
# 17.02.2023 Project_Management_Foundations: lesson_7: Organizational Structure
- Project Work will align with organizational goals, Expectations, Policies, Practices
- Organizational structure can affect
	- How projects develop and progress
	- How resources are allocated
	- How resources are made available
- Organizational Influences on Project Mangemenr
	- Culture of organizatin
	- Style of Mangement
	- Structure 
- Project stucture may be influenced by broader organization
	- PMOs
	- Program Management
	- Portfolio Management
- External factors can also have an impact
	- Clients
	- Joint Ventures
	- Partnerships
# 17.02.2023 Project_Management_Foundations: lesson_7: Realizing Benefits Through Project Initiatives
- Organizations undertake projects to create or gain access to new sources of value
- Retaining alignment between project work and organizational objectives is critical to ensuring value creation
- Value may be traced through several steps to ensure alignment
- Strategy
	- Core reasons for an organization's ongoing existence.
	- Described in the organization's mission and vision statement
	- Should be evident in the shared ethos and purpose of organizational staff and leadeship
- Objectives
	- Distillation of strategic vision into specefic, measureable goals
	- Objectives in this level are likely to remain high-level in nature
	- Many initiatives may be neccessary or desired in achieving objectives
- Initiatives
	- Specific portfolios, programs, and projects put in place in order to achieve objectives.
	- Each initiatives may be responssible for a part of an objective or may be targeted at accomplishing an objective on its own.
- Capabilities
	- Projects generate new capabilities that organizations use to meet objectives
	- This capabilities may be the goal or an ancillary result of project work
- Outcomes
	- New capabilities developed through initiatives provide the organization with results that may be tangible or intangible in nature.
- Benefits
	- The benefits of these outcomes may be tangible or intangible as well and could be result of initiatives, newly developed or improved capabilities, and associated outcomes of our project.
- Value 
	- Project resaults should be traceable all the way back to strategic vision in order to ensure authentic value creation.
	- Project work may influence higher levels of stack, underlining the importance of consistent alignment.
           
# 13.02.2023 Project_Management_Foundations: lesson_6: Risk Plan
- Your risk management plan captures the methodology or the overall approach you'll follow to manage risks.
- The plan should describe:
	- How risks will be identified, 
	- Evaluated and analyzed,
	- Documented,
	- Controlled and managed, 
	- Reported
- Good risk management plans also include the **roles and responsibilities** for team members. aslo, how to manage risk-related communication. The plan should explain how communication will happen, when, and to whom.
- This is essential to set expectations and for stakeholders to allocate the time required for their risk-related responsibilities. It's a good idea to use a matrix with a list of risk-related activities and which team members perform risk monitoring, provide input, approve, and own a given risk response activity.
- The plan should also include a glossary to make sure everyone is aware of risk-related terminology. 
- Also, the risk management plan should include the approach to **budgeting** for negative risk mitigation activities, enabling positive risk opportunities, responding if risk events occur, and planning a contingency budget.
- Finally, document how risk reviews will be performed throughout the project to make sure the risk process is effective and efficient.
# 13.02.2023 Project_Management_Foundations: lesson_5: Volatility in a project env
- Common factors that change on a project are: 
	- Key stakeholders, 
	- Available skill levels,
	- Sponsor expectations or concerns,
	- Risks that actually do happen.
- Being prepared for a bit of volatility can help you deliver your project and keep your sanity
	- Keep a one page project purpose and status summary up to date. 
		- Outcomes your project will provide to the organization
		- The projected cost and timeframes
		- What resources each key stakeholder must contribute
		- Current status against baselines.
- Being Prepare for volatility
	- Understand available staffing options and impacts.
	- Get to know your sponsor
	- Make risk management your top priority.  
# 13.02.2023 Project Management Foundations: lesson_4: Ambiguity
- "My stakeholders don't know what they want." It's called ambiguity, when I may interpret a requirement statement to mean one thing, and a teammate reads it and understands something very different. 
- PMI talks about two types of ambiguity, **conceptual** and **situational**. 
- **Conceptual** ambiguity is when a sentence can be interpreted more than one way.
- **Situational** ambiguity is when more than one solution pathway or outcome can result from a project decision.
# 13.02.2023 Project_Management_Foundations: lesson_3: Incorporating risk in a complex environment
- Digitization Leader and Author Pearl Zhu said, "In business, complexity both drives innovation and hinders it."
- Project complexity
	- Systems-based: approaches involve breaking down systems into small independent pieces.
		- PMI refers to this complexity reduction approach as "decoupling."  
	- Reframing: involves collecting a broad set of opinions, including opinions from people who wouldn't normally be approached, like new customers or people with experience in different industries. 
	- Process-based: These are often driven by your project methodology.
# 13.02.2023 Project_Management_Foundations: lesson_2: Risk
- PMI defines as a lack of understanding and awareness of issues, events, paths to follow or solutions to pursue.
- Risks are events that can have an impact on your project but have not yet occurred. The impacts can be **positive** called **opportunities** or **negative** called **threats**.
- **Issues** are things that have already occurred on your project.
- There are four things you can do to reduce and manage risk. 
	- First, leverage your project team and key stakeholders. 
	- Second, think through possible outcomes. Look at individual tasks or groups of tasks that create one of your projects deliverables. 
	- Next consider other approaches to completing your project tasks. 
	- Finally have a plan B.
# 13.02.2023 Project_Management_Foundations: lesson_1: Risk Glossary
- Risk category: A classification used to group identified risks.
- Risk management plan: A document that captures the processes and approaches a team will follow to manage risks in a project.
- Risk register: A tool used to identify and document a project’s potential risks and details.
- Risk standard: A term used by the Project Management Institute (PMI) that states project managers should continually evaluate exposure to risk, both opportunities and threats, in order to maximize positive impacts and minimize negative impacts to the project and its outcomes.
- Uncertainty: A lack of understanding and awareness of issues, events, paths to follow, or solutions to pursue, which will contribute to a risky project.
# 06.02.2023 Project Management: Lession 3: Project Methodologies and the Project Life Cycle
- **Initiation**: Business case is made Project is chrtered Core team is assembled
- **Planning**: Plans outlined for management of all aspects of the project
- **Executing**: Actual work of the project is completed Objectives and requirments are met.
- **Monitoring & Conrolling**: Project progress and performance is measured Changes are poposed where necessary to meet existing or shifting goals.
- **Closing**: confirm objectives were met. Turn over final product to customer, project sponsor, or designated recipient
- Choosing a Project Methodology
	- Predictive
		- Clearly different work takes plac in each phase.
		- Major changes to team composition often take place at project milestones.
		- Preferred when deliverable is well undestood, based on established practices, and lacks value unit fully complete.  
	- Iterative
		- Develops product through series of repeated cycles.
		- Incremental development process with careful change management.
		- Helpful when objectives and scope are subject to change.
	- Adaptive
		- Similar to iterative model, but on a faster pace, often of 2-4 week cycles.
		- Ideal in rapidly changing environments when scope is hard to define fully in advance. 
		- Oftern used when partially completed products offer value to stakeholders as development continues.  

# 05.02.2023 Project Management: Lession 2: Key Project Roles
- **Leader**: May be known as Project Manager, Coordinator, Scrum Master, or by other titles.Primary person responsible for ensuring objectives are met and outcome are satisfactory in nature.
- **Project Facilitator**: additional role often fullfilled by project leader. Responsible for helüing team members achieve goals by combating challenges and facilitating progress.
- **Project Sponsor**: individual or entity responsible for commitiing organizational resources, providing funding, and certifying project objectives.
Often selects the project leader and other key roles helping to form the beginning phases of the project team that will actually achieve the initiatives and objectives that the sponsor has defined. 
- **Product Owner**: Additional role often fullfilled by project sponsor prioritizes requirments for ongoing work based on an understanding of value, risk, and activity dependencies. 
- **Domain SME**: typically associated with the peoject for only a portion of its total duration.
- **Customer**: May also serve as the product owner depondeing on the nature of project. Represents the primary beneficiary of project work, defines vale and verfies deliverables are acceptable. Provides useful insight in specifying requirments and may assist in implementation activities.
- **End User**: May or may not be the same as customer. Will be most directly impacted by the project's implementation and is an important source of perspective in planning and validating work.
- **Governance**: May be internal to the team or organization or may be an external regulatory authority. Ensures project work and results are in compliance and may provide approval in case of formal review
# 05.02.2023 Project Management: Lession 1: Project Foundations
- Needs Assessment: May be conduct by Project Manager or Business Analtyst. To determine what the underlaying needs might be that indicate that there is on opportunity for a project to create value or to solve problems. By addressing needs, value is created. 
- Business Case
	- Business case lists objectives and justifications for project initiation
	- Should indicate economic feasibility and expected net benefit of project
	- Timeline of benefits realization vs. cost incurrence should be described
 - Benefits Management Plan
 	- Describe how and when project benefits will be delivered
 	- Defines target benefits and timeframes, lists risk factors and assumptions/constraints
 	- Includes metrics that can be used to verify delivery of benefits.  
- Project Charter
	- Founding project document created or approved by project sponsor
	- Defines core project objectives, provides for founding, names key staff and project manager.
- Project Management Plan
	- Created by project manager and project team
	- Describes how project objectives will be completed and how project work will be managed 
# 12.01.2023 Gantt Chart: Factors that important order
- Resources availability
- Dependencies
- Urgency
- Importance
- Stakeholders
# 12.01.2023 Gantt Chart: Resources
- People
- Money
- Space
- Equipment
- Time
- Goodwill
# 12.01.2023 Gantt Chart: Strategic way
- Program management say the Program Managers deal with the **WHY** while Project Managers tend to to deal with the **HOW**.
- Link to the how and why is the idea that projects are intersted in **OUTPUTS** we made the road on time and on budget while programs are more interested in **OUTCOMES**. 
- Program **OPEN Endedness** while Project Management is **END Date**.
- **Shifting Stakeholders** in Program Management while it is **Manageable Stakeholders** in Project Management.
- **Unclear edges** in Program Management while it is **Edges defined** in Project Management. 
- **Complex planning** in Program Management while it is **Simple Planning** in Project Management. 
- **Documentation critical** in Program Management while it is **Documentation important** in Project Management.
# 12.01.2023 Gantt Chart: Planning
- Top Down: Estimate numbers and confirm.
	-  Advantages:
		- Faster
		- Discover critical elements early

- Bottom Up: Ask for numbers.
	-  Advantages:
		-   You get them to open first (Others bid first)
		-   More accurate estimates
		-   Project Managemees have more buy-in
# 12.01.2023 Gantt Chart: Monitoring Cost
- Cash-flow time delay
- Effect of lateness on amount spent
- 
# 01.01.2023 Gantt Chart: Coloring in
- Proportional Colouring: where if you've done half a taskyou color in half of it.
- Colour in when complete : until whole task is done.
# 01.01.2023 Gantt Chart: Speeding Up (First Half) the Project with Gant Chart
- Crashing the Project
	- Putting the money up, means Increse Resources
	- Putting the quality down, Reduce quality
	- Overlapping some of the tasks, Overlap tasks  
# 01.01.2023 Gantt Chart: Speeding Up (Second Half) the Project with Gant Chart
- Crashing the Project
	- Putting the money up, means Increse Resources
	- Putting the quality down, Reduce quality
	- Overlapping some of the tasks, Overlap tasks
	- Let the Project Slip to just run a bit later, Let Slip
# 01.01.2023 Gantt Chart: Forecasting Challange
- Forecast Cost at Completion (FCC): An estimate of the project's final cost.
- You got to estimate this from a combination of the progress in the spend.
# 01.01.2023 Gantt Chart: Five Common Mistakes should be Avoid 
- Jumpping straight to the Gant Chart
- Getting the wrong level of Granularity
- Forgetting Contingency
- Neglecting the Gant Chart once you've started
- Changing your plan more than once
# 27.12.2022 Gantt Chart: Unit of Measure for Resource Plan
- Hours per Week
- Person days per week or month
- Number of People (Full-Time Equivalents=FTEs) per week/month
# 27.12.2022 Gantt Chart: Ask to Sponsors: 
- How certain project are getting on?
- How's the X project getting on?
# 26.12.2022 Gantt Chart: Slipping
- what has happened compared with waht should have happend
# 26.12.2022 Gantt Chart: Linking Tasks
There are four ways tasks can be linked.
- Finished to Start
- Start to Start
- Finish to Finish
- Start to Finish
# 26.12.2022 Gantt Chart: Gantt Chart
- A project management tool that helps you make plans and monitor progress.
# 26.12.2022 Gantt Chart: Lead and Lag
- There is the time lags that can happen between tasks, sometimes known as lead and lag.
# 26.12.2022 Gantt Chart: Granulate
- which means cut them up into smaller parts.
# 26.12.2022 Gantt Chart: Critical Path
- The longest path, or the tasks that take the longest time to complete
# 26.12.2022 Gantt Chart: Agile
- Also known as scrum. A task management methodology based on the idea that it’s not worth having a detailed plan at the start of a project, but rather remaining flexible and iterating as you go along
# 26.12.2022 Gantt Chart: Waterfall
- Also known as the APM or PMI method. Task management that copes with uncertainty using one of four methods: Worst case, most likely case, contingency, and dividing the task into phases
# 25.12.2022 Review Session: Why People Avoid Reviews
- Review Session: It's a chance to learn for next time, to celebrate the achievement of the project, and to thank everyone.
- All the reviews are saved in a folder for future reference. 
- There are Seven types of faulty thinking
  - No Time
  - Too Stressful
  - Can't admit mistakes in public and in writing
  - Stored in memory
  - It went well, so we don'y need a review.
  - Project was unique and we'll never do another project like that one.
  - No one will read them.
- What should a project review consist of?
  - Friendly  environment and informal
  - Sets the tone informal and positive 
  - Ask three questions
	  - What was good we will do again next time?
	  - What was bad that we will avoid next time?
	  - What could we do differently next time?
# 24.12.2022 12-Steps Process: 12 Steps to Managing a Project Successfully
- Define the Project
- List of tasks
- Plan the running order.
- Add contingency
- Consider crashing
- Make a Gantt chart
- Calulate resource requirments
- Assess Risks and prepare action plans
- Monitor progress using the Gantt chart
- Monitor costs
- Readjust your plan
- Review
# 22.12.2022 Resource Management Plan: Create Resource Management Plan
  - Roles
  - Responsibilities
  - Reporting Structure: Who reports to whom
  - Skills needed to do the project work
  - Staffing Plan: which describes everything about how you'll staff the project
    - identify sources for resources
    - when are they needed
    - training requirments
    - resource processes 
- Responsibility Matrix: includes four categories of responsibility.
  - R= Responsible:a group is Responsible for performing work.
  - I= Informed:a group gets information
  - C= Consult:a group about decisions
  - A= Accountable: agroup makes or approves decisions and delegates work. 
# 22.12.2022 WBS: What is Work Breakdown Structure (WBS)
- A WBS contains two kinds of tasks:
  - **Summary tasks**: Higher-level tasks that summarize work in some way.
  - **Work packages**: Lowest-level in WBS and it is in Eight-to-Eighty-hour tasks
# 22.12.2022 Tailoring: Four-step Tailoring Process
- Step 1: Select Initial Development Approach
- Step 2: Tailor for the Organization
- Step 3: Tailor for the Project
- Step 4: Implement Ongoing Improvement
# 22.12.2022 Proccess-Based Approach: Five Project Managment Proccess Gropus
- **Initiating**: Those processes performed to define a new project or new phase of an exsiting project by obtaining authorization to start the project or phase.
- **Planning**: Those processes required to establish the scope of the project, refine the objectives, and define the course of action required to attain the objectives that the project was undertaken to achieve.
- **Execution**: Those processes performedto complete the work defined in the project management paln to satisfy the project requirments.
- **Monitoring and Controlling**: Those processes required to track, review, and regulate the progress and performance of the project; identify any areas in which changes to the plan are required; and initiate the corresponding changes.
- **Closing**: Those processes performed to formally complete or close the project, phase , or contract.  
# 22.12.2022 Agile Project Management: Basics Of A User Story
- What
  - It describes a feature (or component of a feature) and is short and simple.
- Who
  - It’s from the perspective of the person who will use the feature.
- Why
  - It incorporates the “value” of the feature so the team knows what is driving this request.
- When
  - User stories are prioritized in terms of when they’ll be completed.
- Create User Stories: 
  - You and your team will create and capture user stories in a specific format.
    - “As a… I want… so that…”.
    - As a…
      - This describes who the user is. You might design a feature differently if you know that the end user is tech-savvy versus one who is not.
    - I want…
      - This expresses what the user is trying to accomplish. Understanding the feature request is critical to delivering the right thing.
    - So that…
      - This is perhaps the most critical part of the user story format. Why the user wants to accomplish something can be very enlightening to the goal just described.
      - As [USER], I want [Some Feature] so that I can [Get some Value].
      - As a restaurant owner, I want to be able to put my menu online so that people will be interested in my restaurant.  --- > What vs How.
- Create a Task:
  - Has the Scrum Master or Disciplined Agile Scrum Master worked with the team to determine the tasks that will be completed during the sprint?
  - Are the user story point estimates in the sprint agreed to by the team members?
  - Does everyone understand the work they need to complete during this upcoming sprint?
  - Does the workload realistically match the team’s capacity?
# 21.12.2022 Agile Mindset: Treating Software Different From Manufacturing
- Management of software is simply impossible without a very high degree of documentation. Why so much documentation:
  - 1) Enough designer must communicate with interfacing designers, which his management and possibly with the customer. A verbal record is too intangible to provide an adequate basis for an interface or management decision. An acceptable written description forces the designer to take an uniquivocal position and provide tangible evedence of completion.
  - 2) During the aerly phase of software development the documentation is the specification and is the design

# 18.12.2022 Project Goal: Identify the project goal
- Define the end result
- Solves the problem
- Take advantage of opportunity 
# 18.12.2022 Problem Statement: Clearly define the problem or opportunity
ABCD
# 18.12.2022 Project Objectives: Identify the project objectives
- **Business Objectives**: support your organization’s goal.
- **Financial Objectives**: ex. Cutting costs by 10%.
- **Quality Objectives**: specify how good results need to be.
- **Technical Objectives**: 
- SMART Objective
  - **S**pecific Objectives: Inform what needs to be achieved. Ex: increase 15& Revenue
  - **M**easurable Objectives: show how much has been achieved. E.x: Revenue increase
  - **A**chievable Objectives: tell what can be done with resources available. 
  - **R**ealistic (2:26)  
  - **T**ime-Related Objectives: Identify when objectives need to be achieved. 
# 18.12.2022 Choose a Strategy: Choose a strategy
- Brainstorming
  - Identify possible strategies 
  - Allow free flow od ideas
- Questions about strategy:
  -  Is the Strategy feasible?
  -  Are the risks acceptable?
  -  Does Strategy fit the culture?
# 18.12.2022 Gathering requirements: collect the requirments for a project
- Requirements challenges:
  - Incorrect requirements
  - Inconsistent requirements 
  - Missing requirements 
  - Unnecessary requirements 
  - Customers don’t commit time 
- Techniques for gathering requirements:
  - Interview
  - Focus Group
  - Observation 
  - Surveys
  - Document analysis 
- Analysing Requirements: 
  - Delphi Approach  

# 15.12.2022 Stakeholder Managmenet: Identify Project Stakeholders
- Prepare Project Charter
     - Stakeholders
          - Project Customer: is the person or group with a problem to solve. Bring Three crucial things to a project
               - Funds the project
               - Inform what needs to be done
               - Approves deliverables from start to finish.
          - Project Sponsor: Someone who wants to see the project succussed and has enough formal authority to make that happen.
               - Prioritize objectives 
               - Talk to stakeholders who aren’t being supportive 
               - Suggest Improvements to the project plan
          - Functional Manager: 
               - Achieve department goal
               - Mange team members
          - Department 
          - Team Member(s)
- Have we listed all the project assumptions we can think of?

# 14.12.2022 Organization Structure: How Organization Structure Affects Projects
- Hierarchy: each person reports to only one supervisor
     - PM has almost no authority
     - Functional Manager is typically in charge of things like project budget
     - Resources are hard to come by because they report to Functional Managers not PMs.
     - PM has divided responsibilities 
- Matrix: where people report to both managers and PMs
     - PM has some authority to make decision
     - Resources repoert to Two managers, Functional Manager & Project Manager
     - PM and staff work full time in a strong matrix
- Projectized: Where most of the people work on projects
     - PM has almost complete authority
     - Resources are dedicated to project
     - PM and admin staff work full time  

# 14.12.2022 Project Managmenet Approaches: Waterfall vs Agile Project Management
- Waterfall Approach: Processess flow from one to the next.
     - Simplicity
     - Low risk
     - Familiar technology
     - Experience resources 
- Agile Approach: 
     - To deliver partial, yet production-quality solutions at regular intervals
     - Value deliver sooner
     - More customer involment
     - Small independent teams
# 14.12.2022 Process Groups: PM can be categorized into 5 Groups of Process
- Initiating: is about getting the commitment to start a project.
    - Defining the project: 
    - What’s the project supposed to accomplish?
    - What’s the scope?
    - What’s the rough estimate of Resources needed and the cost?
    - Identifying the Stakeholders and make sure they agree on what the project is.
    - Ask for Approval to proceed. 
- Planning: is where you figure out how you’re going to perform the project.
    - What are we going to do?
    - How are we going to do it?
    - How will we know when it’s done?
    - Executing: Lunching a project, bring the resources on board, get them settled in, and explain the rules you’re using to run the project.
- Executing: Lunching a project, bring the resources on board, get them settled in, and explain the rules you’re using to run the project.
- Monitoring and Controlling
    - Checking what’s going on the project?
    - How that compares to what you planned?
- Closing Process: this part is short but important
     - Get the cleint to accept project is complete
     - Document the project performance, gather lesson learnes, 
     - Close contracts
     - Help resources move to the their next assigments.

# 07.12.2022 Risk Management: Risk Matrix
- Identify risk and then make them less of a proble, and then report to our boss, customer, or stakeholders what the risks are that we have not been able to get rid of. 
- **Risk Factor** = How likely they are to happen?
- **Impact Factor** = How serious they would be if they did happen?
- The Unknown
  - Remember that a risk is something that hasn’t happened yet. Risks that you are aware of are called issues.
- The Flip Side
  - Risk is not always negative. It can be positive, as well. Act on opportunities that can make the project go faster or provide greater value.
- Categorizing Risks
  - Risks can be analyzed and prioritized using the following categories:
    - Avoidance: Remove risky areas from the project scope
    - Mitigation: Do some risk response planning to reduce the likelihood of occurrence, impact, or both
    - Transferral: Move risky work to someone else (e.g., a subcontractor via modification to their statement of work)
    - Acceptance: Accept and deal with the risk (this would happen if the cost to mitigate exceeds the cost of the risk itself)
- QUESTIONS TO ASK THE TEAM
  - Can anyone spot any risks or opportunities coming down the pike?
- QUESTIONS TO ASK YOUR SPONSOR
  - Can your Sponsor think of any risks that might occur based on historical information or previous similar projects?
- Risk Response Planning is the process of developing options and determining actions to enhance opportunities and reduce threats to the project's objectives.

# 04.12.2022 Prenciples: Project Management Principels
- Be a diligent, respectful, and caring steward.
- Create a collaborate Project team environment.
- Effectively engage with stakeholders.
- focus on value.
- Recognize, evaluate and responds to system interactions.
- Demonstrate leadership behaviours.
- Tailor based on context.
- Build quality into process and deliverables. 
- Navigate complexity.
- Optimize risk responses.
- Embrace adoptability and resiliency. 
- Enhance change to achieve the envisioned future state.

# 04.12.2022 Phrases and Idioms: How to Use Proper and Professional Phrase?  
- For the sake of brevity
- Nailed it! Your project charter is starting to come together!
- awkward steps
- You’re making it happen
- Keep on keepin’ on! Great work!
- Yeah baby! Make that schedule happen!
- In case you need to hear it today: you're awesome.
- Look at you! You’re crushing it!
- If you can do this, you're off to a solid start.
- Yeah baby! Make that sprint schedule happen!
- Woo hoo! You're on the way to agility!
- Look at you go!
- To use the posh language,
- Put simply
- In our analogy, 
# 26.12.2022 Terminologies: Portfolio
- Projects, programs, subsidiary portfilios, and operations managed as a group to achieve strategic objectives.
# 26.12.2022 Terminologies: Portfolio Managemnet
- The centralized management of one or more portfolios to achieve strategic objectives.
# 04.12.2022 Terminologies: Key Terms and Concepts
- Outcome =
- Portfolio = Projects, programs, subsidiary portfilios, and operations managed as a group to achieve strategic objectives
- Portfolio Mangemnet= The centralized management of one or more portfolios to achieve strategic objectives
- Product =
- Program = Related projects, subsidiary programms, and program activities that are managed in a coordinated manner to obtain benefits not available from managing them individually
- Project = A temporary endeavor undertaken to create aunique product, service, or result
- Project Management = 
- Program Mangement = The application of knowledge, skills, and principles to a program to achieve the program objectives and obtain benefits and control not available by managing program components individually
- Project Manager = 
- Project Team =
- System for Value Delivery = 
- Value =
- features describe the main functionality of the product. 
- Epics are a way to break features into smaller chunks of work.
- Project Life Cycle = can be predictive or adaptive. Whithin a project life cycle, there are generally one or more phases that are associated with the development of product, service, or result. These are called development life cycle, which can be predictive, adaptive, iterative, incremental, or hybrid model.
- Project Phase = is a collection of logically related project activities that culminates in the completion of one or more deliverables.
  - Concept development
  - Feasibility study 
  - Customer requirments
  - Solution development
  - Design
  - Prototype
  - Build
  - Test
  - Transition
  - Commissioning
  - Milestone review
  - Lessons Learned 
- Phase Gate: is held at the end of aphase. The project's performance and progres are compared to project and business documents including but not limited to:
  - Project business case
  - Project charter
  - Project management plan
  - Benefits mangement plan
- 
# 03.12.2022 Cost: How to evaluate cost?
- ABC. 
 
# 03.12.2022 Communication: How to communicate with stakeholders?
- Communacation Matrix: 
- Are we reporting out the right things at the right time to the right people?
# 03.12.2022 Lessons Learned: Tips and Tricks
- Before any action, I must inform Sponsor(s) about the next steps of the project and after his/her/thier green light, will move on the next step. 
- Ask Two key questions in the meetings: 1) Who will be responsible, 2) When will recieved answer?
- If Project is running late
  - More resources
  - Reduce quality
  - Overlap tasks
  - Let Project slip
  - Abandon the project
- If you are overspent
  - Reduce Quality (or Scope)
  - Overspend
# 02.12.2022 Parking lot: Intesting Tpoics to know 
- 25/10 crowd sourcing approach
- Penny Game Agile
	- most of us cling to the notion that we could just focus on our work in a quiet office all by ourselves, we'd be much more productive. The problem is that you’re actually right but most organizations aren’t just one individual. 
	- You as an individual probably would be much more productive just working on your own tasks but as a team overall, you’d actually be less productive. You probably don’t believe me and that’s why I love penny game.
	- You’ll arrange several people around a table. These people represent members of a team or even different functional areas. Each team member has their own batch of work. To keep things simple, this work is just to fill pennies.  
	- Each team member flips pennies two at a time then pass them to a coworker. To monitor the team’s progress, you can record how long it takes each person to finish their work and how long it takes for the customer to get their first glance of the product and when it’s finished.
	- I usually run the penny game in the three rounds. For the first round, I have each person flip all 10 pennies. Remember that this is how most people prefer to work. They can just focus on all 10 pennies and when they’re done, they can hand it off to the next person. This is the equivalent of sitting in your office all day and focusing just on your own work. You can see that each person is pretty productive. Their finishing their big batches around 10 second but the customer doesn’t get their product until 52 seconds. Foe the second round, the team creates two batches of five pennies. In this smaller batch, their coworkers can start working much more quickly. Each team member doesn’t have to wait for the full handoff. They can start to work as soon as they receive their first batch. So you can see this is making each individual team member much less productive.
	- The smaller batches are slowing down each person. So now everyone is hovering around 12 seconds but the customer gets their first batch of work in only 28 seconds and then the team finished in 34 seconds. 
	- For the third round, they break their work down into five batches of two pennies so we’re getting rid of these big handoffs and keeping the team from multitasking. Everyone is focused on their own two pennies. It took each team member around 14 seconds to complete the work, four seconds longer than the batch of 10 but the customer gets to see the work dramatically faster, receiving the first glimpse in only 11 seconds and the entire product in 23 seconds, half the time of the first round. 
	- During the first round when people could focus on the entire batch, they were individually more productive but the customer 
- Simple Lean-Agile Mindmap (SLAM)
- Organizational Project Management (OPM)
- Parametric Model
- Firm Performane 
  - Net Present Value (NPV)
  - Return on Investment (ROI)
  - Internal Rate of Return (IRR)
  - Payback Period (PBP)
  - Benefit-Cost Ratio (BCR)
- Gantt of Gantts: Shows both the past and future. Use a Gantt of Gantts to monitor the past and plan for the future.
- Deterministic Agile (DA) Approach
