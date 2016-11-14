# What is Technical Debt?
* well known term
* see Ward

# What is a Technical Debt Manager?
* understands what Technical Debt is (and what not)
* somebody in the team who cares on code quality and handles Technical Debt
* who understands where Technical Debt comes from, how it is created
* who programs with the team
* responsible person for technical stuff so that the team can Deliver Value Continuously
* Make the Architect and the Developers awesome about Code, Design, and Architecture Quality
* Cares about the Safety which is needed to make code and architecture changes
* Experiment and Learn

There is always a reason why there is Technical Debt. In most cases more than "a" reason, but a bunch of them. 
The Technical Debt manager understands them, can separate them in handable parts, knowns who to address and
speaks the language of persons in charge.
�����
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
* Jenkins, Drone
* SCM Servers like Gogs, GitHub, Gitlab

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

# Citations
The code got that way for a reason, & if you can't change people's habits, it'll just re-messify again after the refactoring.
(Sarah Mei (@sarahmei) on Twitter https://twitter.com/sarahmei/status/715639963274969088)

The art of programming is the art of organizing complexity; mastering multitude & avoiding its chaos as effectively as possible. - Dijkstra
(Rich Rogers (@RichRogersHDS) on Twitter https://twitter.com/RichRogersHDS/status/712791280632348672)
