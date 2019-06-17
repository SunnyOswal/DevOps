**ALIGNMENT**  
- [ ] We prioritize according to business objectives. 
DevOps is all about alignment. It was born out of frustration and trouble between the disparate priorities and incentives of Development and Operations teams. Alignment comes from unifying towards a common goal.
- [ ] We volunteer for tasks rather than having them assigned. 
Autonomy is a critical facet to motivation and job satisfaction. By allowing team members to self-select tasks, you'll see them work on what they're best suited to complete.
- [ ] Our team has clear objectives that correspond with our company vision. 
- [ ] Our product team is focused on sustainable velocity rather than current speed. 
- [ ] We focus on time to repair rather than time between issues. 
A great deal of software delivery theory actually stems from manufacturing. The major difference is that testing failure is faster, cheaper and non-destructive. Thus, we focus on early failure detection through automated testing, as far upstream as possible to catch issues before they become costly. We also focus on learning from simulating production failure by staging 'Game Days', 'Failure Fridays' and optimizing reaction time and corrective process.
- [ ] DevOps is not isolated to a specific role in our organization. 
Hiring a 'DevOps engineer' is an antipattern because it charges an individual with understanding and operating in two worlds with their respective opposing incentives, while remaining independent of either, as their own silo. Even more confusing is reconciling that position with a larger organizational DevOps pursuit. Hiring an Automation, Systems, Operations or Development engineer specifically, or just simply an engineer would be more humane and doesn't require you to write a manifesto for your job descriptions. For more info on hiring for DevOps, see O'Reilly's free book.
- [ ] DevOps is not isolated to a specific team in our organization. 
DevOps works best as a cross-functional team focus. Large organizations have often seen success with an exploratory task force team or a greenfield project team, but in order to get optimal results every team should be able to build and deliver without relying on another department. Vote no on silos!
- [ ] Our operational functions are seen as a source of competitive advantage. 
A large part of why DevOps exists is in reaction to common perceptions of IT as a cost to an organization, yet we now know it can just as easily be a source of innovation.

**CONTEXT**  
- [ ] Making relevant information and contact available to those who need it, when they need it.
Representation from our operations team is involved in development sprint planning. 
- [ ] We make potential changes visible to all members of our product team. 
- [ ] We have an automated system for running tasks and receiving notifications with our team chat. 
- [ ] We consult with auditors and regulators regularly and seek guidance when designing systems. 
- [ ] Our team is encouraged to question tasks and priorities. 
- [ ] We have a centralized instant message system including all members of our product team. 
- [ ] All members of our product team have access to environment status, metrics and history. 
- [ ] All members of our product team have access to code status, metrics and history. 
  
**LEARNING**  
- [ ] Empowering personal growth and fostering understanding through continuous improvement.
- [ ] We cultivate an environment of continuous learning. 
- [ ] We regularly celebrate our product team's learnings and success internally. 
- [ ] We regularly share our product team's learnings and success with the rest of our organization. 
- [ ] We openly discuss failures in order to share learning. 
- [ ] We identify skills needed to improve or address future objectives. 
- [ ] We strive to examine how we complete our work, and how effectively we complete it. 
- [ ] We estimate based on measurement and past experience. 
 
**LIFECYCLE**  
- [ ] Focus on software as a product deserving of care, attention and reflection, within an ever-changing ecosystem.
- [ ] Our software development cycle is 2 weeks or less. 
- [ ] Our software development cycle is defined by releasing a working change into production. 
Iterative development and process optimization depends on repeatedly performing the critical functions of building and deploying software. The more it's done, the better it's understood, the easier it is to improve and automate.
We stop development upon discovering a defect and prioritize its repair. 
- [ ] Developers or product owners are able to deploy our product to production. 
The focus here is empowering the most informed to perform the task. Someone intimately familiar with a change is best positioned to evaluate its performance and correctness. Developers and POs should be empowered to measure and visualize the operation of the change as well, in order to give them a holistic view of the changed system.
- [ ] We have automated testing prior to automated production deployment. 
Production deploys can still be manually initiated in cases where a signoff is required, yet the testing, deployment process and validation should be entirely automated to ensure consistency, accuracy and optimal speed. Automating deploys means no copy and paste, less security risk, more auditability, more confidence.
- [ ] Our configuration of systems is automated. 
Friends don't let friends manually configure systems.
- [ ] Our deployed system configuration is immutable. 
Immutability is an ideal state as it allows operations to focus on optimizing consistent and predictable systems.
- [ ] Our release and deployment automation is environment agnostic. 
To avoid fragmentation or repetition, it's best to limit environmental differences to variable values only.
  
**ORGANIZATION**  
- [ ] Providing structure for interaction and cohesion supporting collaboration and productivity.
- [ ] Our subject matter expertise is not isolated to individuals. 
If you're lucky, you're surrounded by experts. Ideally, they're not just islands of knowledge and responsibility, but part of a peer group within the organization.
- [ ] We enable peer and cross-functional review for changes. 
- [ ] Our organization is configured around cross-functional teams. 
Cross-functional teams are more empowered to build and deploy their own software without being hindered by constraints. They also avoid an 'us vs them' effect of siloed functional teams, learn from, and foster awareness and empathy for eachothers priorities and interests.
- [ ] Our teams are customer and product oriented. 
- [ ] Customer focus helps align teams towards valuable goals, and keeps development and engineering zeroed in on delivery and processing feedback.
- [ ] We review priorities on a regular basis. 
- [ ] Our developers have access to production-like systems to work and test on. 
- [ ] Our developers have access to production-like data to work and test against. 
- [ ] Our developers have access to dependencies required to build and test software. 

  
**PROCESS**  
- [ ] Rituals crafted to foster consistency and confidence, providing a framework for continuous improvement.
- [ ] Our organization follows agile development practices. 
To realize the full power of a focus on DevOps, feedback and regular iteration are critical. DevOps is built on agile.
- [ ] We practice blameless postmortems. 
- [ ] Focus on learning and continual improvement. This is the human equivalent of focusing on MTTR vs MTBF. Read: John Allspaw's great article on Etsy's process
- [ ] We regularly examine constraints in our delivery process. 
- [ ] Our system configuration is committed into version control. 
- [ ] Our documentation is version controlled and shared. 
- [ ] We maintain a backlog of tasks, visible to all team members and available for comment. 
- [ ] We practice test or behaviour driven development. 
- [ ] We test our changes against a merge with our mainline code. 
Until you prove your code isn't a destructive regression, it shouldn't be deployed for someone else to discover. Automated testing and frequent merging should catch most of these issues, and make sure you don't find out about problems from someone else - or worse, Twitter.
- [ ] We test our changes against production-equivalent load and use patterns. 
