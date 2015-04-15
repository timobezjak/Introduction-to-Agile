# Why Scrum?
> Tunde then took me to the realm of empirical process control, a technique used for small batch production when there is more unknown than known, where the complexity is greater than the predictable. He felt that this was more relevant to the field of software development. The churn in our requirements, the complexity of the many technologies, and the use of creative thinking by people made this approach most appropriate. This approach was set up to expect the unexpected through frequent inspection of progress and subsequent adaptation of next steps to optimize output. The basis of it was the container.
> —[Ken Schwaber][waterfall-leankanban-scrum]

For more than twenty years now, the Standish Group has been monitoring the success and failure of software development projects. What it boils down to is, that agile projects are three times more likely to fully succeed, and at a three times lower risk of failing completely than those run by traditional software engineering practices, as shows the following chart by [Mike Cohn].

![Agile: 42% Success, 49% Challenged, 9% Failure][image-chaos-agile-waterfall]

This certainly doesn’t mean that adopting agile practice will end all your software project troubles. But in many interpretations this means: Your most promising way to success will lead through Agile.

## Complexity
A [system][video-system] is a group of elements whose interactions define the whole. It is impossible to add or remove a part without changing the properties of the system itself. A _complex system_ is one in which the elements (or agents) interact in ways, than can be explained only in hindsight. But it is not possible to _predict_ interactions based on prior knowledge. _Complex adaptive systems_ continuously change their behaviour over time in order to self-optimise.

The development of novel software is one example for complex systems. Test-driven development and other practices focus on bringing down dependencies (or “coupling”) to a manageable amount. Still, adding of modifying functionality often affects the overall system behaviour in unexpected ways. Perhaps more importantly though, it usually affects its _users’_ behavioiur in unexpected ways.

Groups of humans are a prime example for complex adaptive systems. It has been observed long before, that [adding people to a late project will make it later][brooks-law]. However, any other change to a team, its environment, or its rules can have unpredictable consequences, good or bad, while the team adapts to the new reality, effectively re-calibrating itself.

## Scrum
Scrum has been designed to build software in a context of continuous change through empirical process control. The team is protected during an agreed-upon time box during which they are free to experiment in order to find the best solutions to the current highest-valued needs.

The entire Scrum team participates in the Scrum events, so the people _implementing_ the system are also the ones _designing_ it from the beginning. Valuable knowledge is thus preserved througout the process, and is readily at hand whenever a decision needs to be taken – which, in software development, is practically every few minutes.

> _But aren’t those big regular events a waste of money?_ Gathering ten people in a room to discuss user needs costs money. Not discussing them with the group costs even more. The Scrum team is generally the finest group of experts for the project’s requirements. Not including their knowledge will generally result in more costly, less optimal solutions. Declining to create a shared understanding of the needs will hinder self-organisation and thus their effectively working together.

Bringing a new software version into production every few weeks is very fast by most standards. Developers, stakeholders, and everyone else can _see_ and _test_ the current project status. The Product Owner can make informed decisions on what to build next.

> _But isn’t this trial-and-error approach a waste of money?_ It is obvioius that money is lost whenever a work piece is discarded. Iteratively going over the same functionality multiple times, refining it step by step, will cost more than doing it _right_ the first time. But how to find out, what the right thing is? Nothing will give you that answer more quickly or more reliably than approaching it in iterations.

Scrum is a [memeplex], a set of practices that support each other. Each of the practices’ usfulness may or may not be obvious, but as a whole they have been proven to lead to great results and a virtuous cycle of increasing motivation, overall product quality and profitability.

## What Comes After Scrum?
There have been reports of teams who’ve mastered Scrum and then decided to move on to a setup that better suited their needs. Spotify originally started as a Scrum compnay, but now their engineering teams [famously][spotify-eng-culture] freely choose whether they use Scrum, Kanban, or any other system.

Others decided, that with continuous deployment in place, inspect-and-adapt cycles of one to two weeks were inacceptable to them.

Both decisions _can_ be the results of a very agile-minded thinking process. Every team should be free to find their best way of working together (all the [Scrum Guide] demands is that you don’t call it Scrum if you don’t follow _all_ of the Scrum rules.) One should keep the memeplex argument in mind though. Glueing together practices from several tool boxes will require you to think hard about the glue, or else everything may fall apart.

In case of doubt, there’s always the golden rule for memeplexes: If it doesn’t work, apply more of it.


[Mike Cohn]: http://www.mountaingoatsoftware.com/blog/agile-succeeds-three-times-more-often-than-waterfall "Chaos Report Agile vs. Waterfall"
[video-system]: https://www.youtube.com/watch?v=OqEeIG8aPPk "YouTube Video: Russell Ackhoff on Systems Theory"
[image-chaos-agile-waterfall]: files/Chaos-Agile-Waterfall.jpeg "Chaos Chart: Agile vs. Waterfall"
[brooks-law]: https://en.wikipedia.org/wiki/Brooks%27s_law "Wikipedia: Brooks’ Law"
[waterfall-leankanban-scrum]: https://kenschwaber.wordpress.com/2010/06/10/waterfall-leankanban-and-scrum-2/ "Waterfall, Lean/Kanban, and Scrum"
[memeplex]: http://noop.nl/2010/02/the-success-of-the-agile-memeplex.html "The Success of the Agile Memeplex"
[spotify-eng-culture]: https://labs.spotify.com/2014/03/27/spotify-engineering-culture-part-1/ "Spotify Engineering Culture"
[Scrum Guide]: http://www.scrumguides.org "Download Scrum Guides"
