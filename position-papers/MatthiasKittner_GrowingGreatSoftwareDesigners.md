# Position paper
Matthias Kittner (mkt@esi-group.com), Platform Architect at ESI Group, Stuttgart (Germany)

Submission to the SATURN 2018 workshop: Growing great software designers. Planned for May 7, 2018 in Plano, TX, USA.

## Introduction
We are a multi-national company providing Virtual Prototyping solutions helping our customers to replace physical prototypes by enabling them to virtually fabricate, assembly and test products in different environments. Our development teams spread across variuos time zones in US, Europe and India.

In my position as Platform Architect my task for the last 2 years was and still is to setup and grow a horizontal cross-team architecture organization. The challenge is to align software development from various cultural backgrounds, different approaches of our acquisitions and in some cases a long history of existing and still used and maintained code to a common vision. Connecting architects, growing them and identifying potential architects go along with maintaining a design culture and successful processes.

The company faces the challanges to overcome silos and create and use more common platforms, fighting technical debt from historical code and maybe really transform these codes if applicable and necessary.

## Who and how to grow?

Who can become a great software designer?
* A potential great designer is somehow gifted with a high level of being able to abstract and think through the things very deep. Not every developer has that. It will be grown with the level of skills but it is also a kind of precondition to be able to develop the skills.
* Good skills and practices is what we want to grow but an additional important precondition is character. Skills can be trained in a comparatively short period of time (not the experiences with the skills) but the character is a not very flexible attribute and therefore more important. The software designer needs to be: ready and keen to learn, willing to adapt to differnet requirements and repent from own mistakes. The desire to get an awesome result should be greater than to be right. He/she is open hearted to listen to the experiences others may have even if they would disagree with their conclusions.
* A designer is a good communicator, because its half the designers job, so he/she needs to have and maintain good relationships within their environment.
* A designer is one who knows that Software Architecture is fun and art, not like a solitary painter, more as a musician in an orchestra. I really believe it is an art because it is a very creative, because we create structure, information and processes.
* Enthusiastic about learning new things is rounding up the attributes of one who I think has a good starting point to become a great software designer.

How to grow them?
* Well defined processes with enough freedom to be pragmatic in the solutions will give a great enviroment to grow and not get lost. First and foremost the design process and decisions need to be driven by the quality attributes and functional requirements.
* Creating a common language and the awareness of "dialects" in words, diagrams, notations is important. In the different environments we are confronted with a common language in all cases or even a common notation is not (yet?) easy.
* A great way to learn is by example. Having one who shows how to design, structure, think deeply and transport the design decisions to teams is a way to effectively learn by role modeling. But this also includes learning from design patterns, best practices, common guidelines etc.
* An environment of open, supporting peers with short iterations on designs resp. feedback loops will help them sharpen their skills.

## My personal story
My way of growing was more or less on the job without getting a lot of formal training. I did not learn much about software engineering at university and I needed to learn from the way the company I was working for was doing it. An initiated large refactoring of the main code brought an external software architect into our team. His role model and the way he approached things really opened my eyes to the beautiful world of great software design. It was the way he asked questions and challenged every little implicit design decision I did not even think about. This was frustrating and at the same time a releasing kickstart which helped me to work on my personal growth since then.

I believe role modeling and enable designers to be a role model themselves is a very important and effective approach.

## Some challenges (we face)
* Maintaining very old code bases is usually done by a team which is used to implement solutions which were good in the past but would not be decided for today. Even the thinking that a good architecture is one thing "but we need performance". Changing this kind of mindset, creating an awareness of necessary paradigm shifts and bridging the gap between old legacy code (e.g. FORTRAN) and new technologies (e.g. web deployment) is a big challenge.
* A myth we face is: "An architecture is a single page diagram containing all information." But the documented architecture is a multi view communication instrument containing the complexity of the system. This needs to be made transparent and understandable in a consistent way.
* Our multicultural environment shows us that cultural differences need to be considered in how to grow people. Areas like reasoning, hierarchical distance, professional relationships or the way to communicate need different approaches on how to train or role model resp. how to grow software designers in these different teams.

## Some principles
Here are some principles (list not complete) I see in this context great software designers should follow:
* Ask the right questions
* Create a balance between thinking carefully through and being pragmatic (you need to make decisions even when you don't know everything)
* Document everything, first and foremost the backlog of design decisions
* Do design reviews (initial and continuous) for short iterations and continued communication and interaction
* I begin to hate quick wins and low hanging fruits (they tend to touch the ground and get brown). In many cases we stick to it and not finish the work by harvesting the whole tree. 
* Design is not only at the beginning the one big step. It is a really iterative path of many design decisions along the way, many small and larger reviews including to assure that the design is at the in the implementation. What matters is the implemented/delivered/used architecture.

The "Continuous Architecture" approach described in the book by Pierre Pureur and Murat Erder [1] helps us a lot including their 6 principles:
* Architect products - not solutions for projects
* Focus on quality attributes - not on functional requirements
* Delay design decisions until they are absolutely necessary
* Architect for change - leverage "The Power of Small"
* Architect for build, test and deploy
* Model the organization of your teams after the design of the system you are working on

## Expectation
I am looking forward to this workshop to bring what I have, to listen to you all other participants and to contribute to our set goal to come up with concrete suggestions and practices on growing great software designers.

## References
[1] Continuous Architecture: Sustainable Architecture in an Agile and Cloud-Centric World, Pierre Pureur and Murat Erder, 2015 ISBN: 978-0128032848
