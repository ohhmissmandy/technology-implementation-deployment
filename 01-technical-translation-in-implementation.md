# Technical Translation in Implementation

Implementation gets messy in the spaces between teams.

A requirement makes sense on paper. The technology works in testing. The rollout plan looks solid. Then it reaches the people, places, workflows, and systems it has to work with in the real world.

That's usually where the gaps start showing up.

The business knows what it needs to accomplish. Technical teams understand what the system can do and where its limits are. Operations knows what will actually work day to day. End users know where the workflow makes their jobs harder.

Everyone may be talking about the same implementation. They just aren't necessarily talking about it the same way.

That's where technical translation becomes useful.

## It's more than explaining the technology

When people hear "technical translator," they sometimes think it means taking something complicated and explaining it in plain English.

That's definitely part of it. The bigger job during implementation is making sure information survives as it moves between people.

A business need has to become something a technical team can build or configure. Technical limitations have to come back in a way the business can use to make decisions. Eventually, all of it has to become something that works for the person actually using it.

A lot can get lost along the way.

I've learned to pay attention to whether the **meaning survived the handoff**.

Something can be documented correctly and still mean something different to three different teams. A feature can work exactly as designed and still make no sense in the user's workflow.

Neither necessarily means the technology failed. Sometimes we lost something between the original need and what eventually got deployed.

## Sometimes the request isn't the requirement

People naturally describe solutions when they're trying to explain problems.

"We need another button." "We need this automated." "We need a report that shows this."

Maybe they do. Before I turn that into a requirement, though, I want to understand what they're actually trying to accomplish.

I want to know what happens before and after the problem they're describing. I want to understand who is doing the work and what makes the current approach difficult. Sometimes one small detail completely changes what the right solution looks like.

That doesn't mean interrogating someone every time they ask for a feature. It means understanding enough of the problem that we're not spending time building the wrong solution really well.

## Translation has to go both ways

If a technical team says something isn't possible, creates a security concern, has another dependency, or would require significantly more work than expected, I can't take "Engineering said no" back to the business and call that communication.

They need enough context to understand the constraint and decide what to do with it.

The same applies in the other direction. "The users don't like it" isn't useful technical feedback either.

Maybe they're confused. The new workflow might take longer or something important could be missing. They may be getting an error. We may have misunderstood how they actually perform the task.

Those are different problems and they lead to different conversations.

Part of technical translation is figuring out what information the next person actually needs, not simply passing along what the last person said.

## Then comes Tuesday

One of the questions I come back to during implementation is:

**What happens when somebody has to use this on a normal Tuesday?**

Not during the demo or UAT. Not during go-live when the project team is hovering nearby and everyone knows exactly who to call.

Just Tuesday.

Someone is busy. The person who went to training is out. A new employee is trying the workflow for the first time. Something looks different than the screenshot. Maybe the system is doing exactly what it was designed to do, but the user has no idea what to do next.

That's where you start seeing things that were easy to miss while everyone was focused on whether the technology worked.

Maybe the user needs better instructions. Support may need more information. A location wasn't actually ready. Or maybe we solved one problem and accidentally added five manual steps somewhere else.

Sometimes the workflow technically works but is miserable to use.

Those things count too.

## Translation continues after go-live

The period after a deployment can tell you a lot.

People start using the technology without the controlled environment around it. Questions show up. Tickets come in. People find workarounds nobody expected. Something that seemed obvious during training turns out not to be obvious at all.

I don't want to treat all of that as noise after the "real" project is finished.

Of course the immediate problem needs to be handled. I also want to know why it happened and whether there's something we should change before the next rollout.

Sometimes the answer belongs in the technology. Sometimes it belongs in the workflow, training, or documentation. Occasionally you discover that an assumption everyone made six months ago was simply wrong.

That's useful information if it gets back to the right people.

## Technical translation is really about connection

I don't think technical translation needs a complicated framework.

Most of it comes down to staying curious long enough to understand what people actually mean. Listen to the person who knows the business problem. Understand what the technical team is telling you. Pay attention to the people who have to use what gets deployed.

The job isn't to walk in knowing everything each specialist knows. A lot of technical translation comes from learning enough of each side to ask better questions and recognize when something isn't connecting.

Eventually, technical decisions become somebody's real-world work.

I want to make sure the meaning survives long enough to get there.


---

[Back to README](./README.md) | [Next →](./02-when-the-playbook-doesnt-exist-yet.md)
