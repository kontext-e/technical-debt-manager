# What is Technical Debt?
* well known term
* see Ward

# What is a Technical Debt Manager?
* understands what Technical Debt is (and what not)
* somebody in the team who cares on code quality and handles Technical Debt
* asks the (right) questsions, inconvenient admonisher, point to the dirty places
 - especially in the long run
 - not only in cases of impulsive actions when a problem raises or management got attention
 - does not loose TD out of mind after a short period of "lets improve all things"
* who understands where Technical Debt comes from, how it is created
* who programs with the team
* responsible person for technical stuff so that the team can Deliver Value Continuously
* Make the Architect and the Developers awesome about Code, Design, and Architecture Quality
* Cares about the Safety which is needed to make code and architecture changes
* Experiment and Learn
* Drives systematic improvement of the system
* Steers developers in code quality improvements
* So not the top 10 sonarqube warnings but top 10 for high ROI (most positive effect on the system)
* Drives Value Based Improvements
 - ROI
 - Improvements are Investments
 - Business Value
 - Increasing Productivity
 - ... "constantly deliver Value to the customer"
* Analyzes where TD comes from - skills, culture, management, customer, ...
* Tacles the root causes for origins of TD
* Translates the technical domain (classes too large, packages too tangled and coupled, test coverage too low) to the management domain (cost, time to market, ...)
* Estimates the cost of not doing an improvement (cost of problem/issue) vs. saving cost when it is done
 - Estimation skills
 - Tools and techniques for estimating system improvements
* Comes up with several options for an problem
 - plus an minus for each option
 - consequences
 - choose an option
 - maybe document it (design decision)
* Has also other improvments in mind
 - organizational
 - infrastructore
 - operational

There is always a reason why there is Technical Debt. In most cases more than "a" reason, but a bunch of them. 
The Technical Debt manager understands them, can separate them in handable parts, knowns who to address and
speaks the language of persons in charge.

# Why would we need one?
* too many projects out there that suffer from a load of Technical Debt
* even if people are complaining about bad code, costly changes, slowing down progress - not everytime someone is feeling responsible to change something
* sombody needs to take action
* 

# Needed Skills
* can communicate to managers
* can communicate to team
* can communicate to QA
* diplomatic communication style without offending people
* teaching good code quality
 - host and facilitate Code Retreats
 - Coding Dojos
 - knows katas which train the missing skill for a developer
 - developer trainer
* discuss factually without bringing the discussion to a personal level (developers will defend their code and coding style)
* Know and understand all the technical stuff best:
 - programming languages
 - language eco systems: libraries, frameworks, services, tools
 - Design and Architecture techniques, patterns, styles, principles
 - build pipeline
 - build and test automation
* a bit of an Architect, a QA, an Ops, and a Senior Dev
* happy to learn, try new tools, libraries, org processes
* balancing technical progress vs. effort of change
 - investment and ROI
* Fearless Change
* knows how to refactor

# Is it the Architect?
* don't mix people and roles
* different role
* different skillset
* but in small projects can be the same person
* in larger teams a senior developer
* if too much work to do: full time TDM
* Architect and Technical Debt Manager can have conflicting goals, esp. if Architect is heavily influenced by a Project Manager

# Useful Tools
* IDE power user
 - also the lesser known features like Structural Search & Replace, Dependency Matrix
 - maybe create own plugins to watch special code places or make larger changes like changing a used library
 - example: IDEA SSR for replacing jMock by Mockito
 - example: IDEA Live Plugin
* SonarQube
* jQAssistant, Structure101, Sonargraph
* static code analysis tools
* Test Coverage tools
* Jenkins, Drone, GoCD, ...
* SCM Servers like Gogs, GitHub, Gitlab
* Scripting languages to process metrics before breaking build
* arc42, Asciidoc, PlantUML
* Simon Brown C4
* automatic architecture and design rule checker
 - degraph
* some lightweight arch drawing tool
* walkmod

# Duties
* recognize Technical Debt
* watch the amount of Technical Debt
* Code Quality Guardian
* create stragies how to handle Technical Debt
* communicate impact if not handled to Architect, Team, Managers
* find best spots where to invest in code quality according to ROI
* helps the team with techniques how to tackle Technical Debt
* educates the team, e.g. Legacy Code Retreats
* negotiate whether to increase Technical Debt to reach short term project goals
* analyzes project situations
* suggests operational, tactical and strategic actions, discuss them with all stakeholders, decide together
* stick to it also in the long run, motivate people
* measures success of the actions, steer or stop them
* suggest better/easier/simpler technical solutions
 - prerequisit: wide range of knowledge about alternatives

# What is Technical Debt?
* all technical stuff that makes team slower

# How to tackle
* refactoring
* team learning

# What do other domains do
* Put Safety First and Minimize the 12 Common Causes of Mistakes in the Aviation Workplace https://www.faasafety.gov/files/gslac/library/documents/2012/Nov/71574/DirtyDozenWeb3.pdf

# Citations
The code got that way for a reason, & if you can't change people's habits, it'll just re-messify again after the refactoring.
(Sarah Mei (@sarahmei) on Twitter https://twitter.com/sarahmei/status/715639963274969088)

The art of programming is the art of organizing complexity; mastering multitude & avoiding its chaos as effectively as possible. - Dijkstra
(Rich Rogers (@RichRogersHDS) on Twitter https://twitter.com/RichRogersHDS/status/712791280632348672)

