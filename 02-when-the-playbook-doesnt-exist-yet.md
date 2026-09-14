# When the Playbook Doesn't Exist Yet

Some projects come with a mature process. There are established requirements, known dependencies, existing documentation, and people who have done it before.

Others start with some version of, **"We've never done this before."**

I actually like those. Not because I enjoy unnecessary chaos. I don't. There's just something different about working with new technology when the process has to be figured out along with it.

I've also learned that you don't have to walk into that kind of work already knowing everything about the technology. Sometimes you have to learn the system while you're figuring out how the organization is going to use it. That means asking a lot of questions, finding the people who know different pieces, and getting comfortable saying, "I don't know yet, but I know what I need to find out."

In some ways, not knowing everything yet can make you pay closer attention. You can't rely on assumptions or "the way we've always done it." You have to understand why things work the way they do.

You can't pull out the old checklist and change the project name. You have to understand the problem well enough to decide what should be on the checklist in the first place.

## Start with what actually happens today

When something new is being introduced, it's tempting to spend all your time designing the future state. I want to understand the current one first.

How does the work happen now? Where does it get stuck? What systems are involved? I also want to know where people have created their own workarounds because the official process doesn't quite work.

A workaround isn't always someone doing something wrong. Sometimes it's evidence that the process doesn't match the work anymore.

New technology doesn't enter an empty environment. It's being added to something that already has people, habits, systems, rules, and probably a few weird exceptions nobody thought to mention during the kickoff meeting. Understanding those things gives you a much better starting point than designing around how the work is supposed to happen.

## Keep assumptions where you can see them

New implementations come with assumptions. That's unavoidable.

We think the site already has what it needs. We expect users to follow a certain workflow. Someone thinks the vendor will handle part of the setup. Everyone assumes Support can take ownership after launch.

Maybe all of that is true.

The problem isn't making assumptions. You have to make decisions before you have perfect information. The problem is forgetting which things were assumptions and quietly starting to treat them as facts.

If an important part of the rollout depends on something we haven't confirmed, I want to know that. Maybe we can validate it now. Maybe we can't. Either way, I'd rather keep it visible than let it introduce itself on deployment day.

## Don't build the 47-page playbook yet

When there isn't an existing process, my first instinct isn't to document every possible detail before we've tried anything.

We don't know enough yet.

We need enough structure to move forward safely and learn from what happens. People should know what they're responsible for. Major dependencies need to be understood. We need some idea of what "ready" means. The people involved also need enough information to do their part.

Then we try it.

The first version is our best current understanding of how this should work. Reality gets a vote next.

## Pay attention to what people keep rescuing

This is where the real process starts showing itself.

Maybe someone has to manually fix the same configuration every time. One person keeps answering the same question. A dependency consistently takes longer than planned. Someone built their own spreadsheet because the official tracking method doesn't give them what they need.

Individually, those things can look small. Sometimes they are.

But if the same person has to save the same step every single time, that's probably not an exception anymore. That's part of your process whether you intended it to be or not.

Maybe the step needs to change. Ownership may not be clear. Sometimes the manual workaround really is the best option for now and we just need to acknowledge it.

The important part is noticing the difference between an unusual problem and a pattern.

## Let the playbook come from the work

I care a lot about documentation, but writing something down doesn't make it true.

The first version of a new process is based on what we think should happen. Once people start using it, we find out what actually happens. That's when it should get better.

If a step needs to happen earlier, move it. If the handoff doesn't make sense, change it. If people consistently interpret something differently than expected, figure out why.

I'd rather have a slightly imperfect playbook that has been corrected by experience than a beautiful one everyone quietly ignores because it doesn't match reality.

Eventually, parts of the process become predictable enough to standardize. If we've learned that something needs to be checked before every deployment, put it into the readiness work. If a configuration should always be the same, make that the standard. If we're asking the same question every time, stop relying on someone to remember to ask it.

I don't want to standardize something just for the satisfaction of having a standard. I want to stop spending time reinventing things we've already figured out.

## Someone else should eventually be able to run it

This is one of my tests for whether we've actually built something repeatable.

Another capable person should be able to pick it up without having sat through every project meeting or remembering every strange exception. They need enough information to understand what should happen, recognize when something isn't right, and know where to go when they hit something the process doesn't cover.

If the only reason it works is because the same few people know how to hold all the pieces together, we've built expertise.

That's valuable, but it's not quite a playbook yet.

When there isn't already a process, I don't think the job is to sit down and invent the perfect one. Learn the technology. Understand the environment it's going into. Keep track of what you know and what you're still assuming. Put enough structure around the early work to do it safely, then pay attention.

Keep what works. Fix what doesn't. Write down what you learn.

Over time, the playbook becomes less about how everyone **thinks** the work should happen and more about what you've learned actually works.


---

[← Previous](./01-technical-translation-in-implementation.md) | [Back to README](./README.md) | [Next →](./03-from-pilot-to-deployment.md)
