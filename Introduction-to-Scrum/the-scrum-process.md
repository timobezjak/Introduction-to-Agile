# The Scrum Process

![The Scrum Double Loops][image-double-loops]
The Scrum process is simple to understand, yet difficult to implement. It defines a few roles, events and artifacts, as shown below, and its basic working is usually explained using the double loops illustration displayed above. The full, authoritative definition of Scrum is contained in a small booklet, the [Scrum Guide], which is available for download on the internet. It is regularly revised and updated by its maintainers, the inventors of Scrum, Jeff Sutherland and Ken Schwaber.

## Sprint (Don’t Rush)
What the illustration fundamentally shows is the transformation of user needs into a new version of a product under development. The basic unit of this transformation is called a _Sprint_ in Scrum terminology, or an iteration in more general terms. Each Sprint is a _mini project_ that takes one to four weeks, with a preference for the shorter time scale, and is immediately followed by another Sprint throughout the project until it finishes.

This means that the team must not be exhausted at the end of a Sprint, which makes the term somewhat misleading. A Scrum project must be managed in such way that everyone involved keeps working at a _sustainable pace_, i. e. under a work load that would, in theory, allow the project to go on forever.

## Events
Agile software development is fundamentally about communication between all parties involved with the creation of a new product. Scrum prescribes a number of time-boxed events. They help create transparency and shared understanding between team members. The Sprint is the “big” event that encompasses all the others as described below.

### Sprint Planning
Each Sprint begins with a Sprint Planning event during which the Scrum Team agrees on the work for the sprint. It therefore has to answer two questions: What will be done, and how will it be done.

Considering the current project state, the Scrum Team identifies what should be worked on next. Starting after a few Sprints, the team will be able to tell with some confidence how much work may fit into the available capacity. Pulling from the Product Backlog (see below) and any remaining work from the previous Sprint, they compile a set of items to work on. They should all support a common objective for the sprint that can be expressed in a statement of one or two sentences, the _Sprint Goal_.

In the second part of the Sprint Planning, the Development Team defines _how_ it plans to achieve the Sprint Goal. What are the tasks? What do we have to learn? Which work items will we pair up for? At the end of the second part, the Development Team declares their readiness to go for the Sprint Goal. Any trouble that has the potential to block the Development Team from reaching the Sprint Goal needs to be communicated and resolved with the Product Owner and Scrum Master immediately.

After the Sprint Planning, the Sprint’s scope and goal are immutable. Even if at some point during the Sprint the Product Owner feels some of it has become obsolete, it cannot be changed. The Sprint can, however, be cancelled at any moment, at the Product Owner’s discretion. It is an extreme measure that generally has to be avoided.

### Daily Stand-Up
Every day at a fixed time, the Scrum team stands together to very quickly exchange the most vital status information so everyone is on the same page. Each member of the group answer three questions:
1. Which work items did I finish since last Daily Stand-up?
1. Which work items am I going to work on next?
1. Are there any impediments, anything I need help with?

Answering to these questions shouldn’t take more than 10–15 minutes for any resonably-sized team. Additionally to making sure everyone understands how much of the work has been done, the Daily Stand-up also ensures that upcoming problems be raised ad fixed at the earliest possible moment. This is a crucial element of Scrum’s quality management strategy.

### Sprint Review
At the end of each sprint, the developers show and explain their implementations of the Sprint’s planned work, thereby also explaining if and how the Sprint Goal was reached. The Product Owner is invited to try out features and to ask questions about their implementation and properties.

The Product Owner also verifies if the implementations meet his acceptance criteria, as defined at or before Sprint beginning. If so, the new feature is accepted into the new increment of the product. Otherwise, finishing the feature is scheduled for an upcoming Sprint.

### Sprint Retrospective
And the end of each sprint, the team also takes the time to reflect on their way to collaborate. What did work out well? Which practices need improvement? Did communication flow without friction? Usually, the team will define a small number of experiments aimed at working together more effectively, or in a more enjoyable way.

Adjustments can be made at any time, but the retrospective provides a formal structure to do so regularly. Attacking problems early, and continuously adjusting to a changing environment, is not only less invasive than infrequent organisational change. It also helps to detect problems early and attack them effectively.

<!-- # For a separate text on retrospecives
It is also more effective in at least two ways.

First, problems (or deviations) summarise over time. If you walk in a slightly wrong direction for two days, you may end up in a very unexpected place. Taking a rest every hour to figure out where you send and how to continue will actually save you a lot of time reaching your target destination.

Second, frequent small changes help you understand their results better, due to short feedback loops. Only one change at a time, is the most basic rule of scientific experimentation. Combining many changes into a big package will be likely to leave cause and effect relationships in the dark. -->

Also, frequent retrospectives keep the team used to question and improve things, and to do all they can to keep motivation and efficiency high.

## Artifacts
Scrum distinguishes a mere three artifacts – comprehensive documentation is not seen as value delivered to the end user. The cross-functional structure of a Scrum team also limits hand-overs to a minimum, effectively reducing the need for writing down the details.

### Product Backlog
Any requirements identified are written down as _Product Backlog Items_ (PBI), usually in the form of _User Stories_. Hence, it is the _Product Backlog_ that holds any planned product functionality.

The Product Backlog should actively be kept to a reasonable number of items. Too few, and you may run out of ideas what to build. Too many, and you will find yourself blocked from responding to change in or around the project. In other words: your ability to work in an agile way. Also, the more items are in a backlog, the greater the administrative overhead for selecting, prioritising, and estimating them.

### Sprint Backlog
In the Sprint Planning meeting, backlog items are moved from the Product Backlog to the Sprint Backlog. Once in the Sprint Backlog, they are entirely owned by the Development Team. During the sprint, nothing can be added to, or removed from, the Sprint Backlog, and neither can Product Backlog Items be altered in any way. This immutability is necessary for the team to effectively plan and do the implementation. It’s their responsibility, so no-one else can interfere.

Product owners and stakeholders are notorious for pointing out the need to react to change quickly, not allowing to wait for a whole sprint to finish. But changing one’s mind every other day and pushing others to constantly adapt to that is _not_ what agility is about. Quite the opposite – going at a sustainable pace invariably implies avoiding firefighting sessions.

### Increment
Agile teams accept running software as their only measure of progress. Having finished a “concept phase” is equivalent to having accomplished 0% of the project’s goal.

Scrum teams, therefore, deliver a new version of the product by the end of each sprint. It is called the Product Increment and contains the newly-implemented User Stories and has production-level quality. It’s the product owner’s decision if the increment should be put into production or not.

## Roles – The Scrum Team
Scrum roles are clear and simple. If everyone on the team live up to their tasks, everything important to the project will be taken care of. The difficulty is, that doing just that entails much more than immediately meets the eye.

![The Scrum Team][image-scrum-team]

### Product Owner
… Which brings us to the Product Owner. The Product Owner has _one job_: To manage the Product Backlog. However, it’s hers to figure out, how she wants to do that. She’ll need to talk to a steering committee, to their line managers, to her line manager. To the sponsor. She’ll also want to learn from end users directly how they will use the product. She’ll talk to the developers, since they know how to build things.

Managing a product backlog doesn’t mean to only write down requirements. They have to be sorted, prioritised, and often discarded. The product backlog needs structure so it can be understood and communicated. One job, lots of work.

As the Scrum Guide states: Its the Product Owner’s goal to maximise the value of the team’s work.

### Development Team
The Development Team is responsible for building a new Increment of the system each Sprint. The Development Team self-organises to optimally work together; it can rely only on its own members, therefore it can accept only Backlog Items into the Sprint that can be implemented without external dependencies.

All necessary expertise therefore has to be available on the team. From a Scrum perspective, there is no distinction between roles or job titles at the Development Team level. The team is responsible as a group.

### Scrum Master
It is the Scrum Master’s job to ensure everyone involved understands Scrum and work according to the Scrum Team’s agreements. This includes coaching and training the Product Owner, the Development Team _and_ the rest of the organisation.

He helps all to communicate effectively and in ways supporting the common goal.

## Putting it All Together
As a whole, this set of events, artifacts and roles defines a minimal setup for any complex software development project. Changing any of them will damage their mutual reinforcement, and thus result in a much less effective development environment.

On the other hand, it isn’t anything _more_ than a well-balanced, minimal project setup either. At a more detailed level, the developers will have to establish development practices to complement the project setup. Likewise, the Scrum Master will work on her facilitation, moderation, and motivational skills; and the Product Owner will have to set up processes and technique to discover, understand, and communicate user needs. Scrum is entirely agnostic about _how_ team members fulfill their roles.

The same is true at a higher flight level. Scrum tells us nothing about program or organisational management. Teams and managers will have to grow environments within which Scrum teams can thrive.


[image-double-loops]: files/Double-Loops.jpg "Backlog->Iteration->Increment"
[image-scrum-team]: files/Scrum-Team.jpg "Product Owner, Developers, Scrum Master"
[Scrum Guide]: http://www.scrumguides.org "Download Scrum Guides"
