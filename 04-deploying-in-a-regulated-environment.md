# Deploying in a Regulated Environment

Working in a regulated environment changes the way you implement technology.

There are things you simply can't decide to figure out later. Security requirements matter. Risk matters. Testing and approvals matter. Depending on what you're introducing, Legal, Compliance, Procurement, Information Security, or other groups may need to be involved before anything moves into production.

That can sound like a recipe for making everything painfully slow. It doesn't have to be.

I've found that a lot of the frustration comes from treating those requirements as something that happens **after** the implementation plan is already built. If you know you're working in an environment with controls, those controls need to be part of the plan from the beginning.

## Find the boundaries early

One of the worst times to discover a requirement is right before deployment.

Maybe a security review was needed. A contract has to change. A production release requires approval. Testing evidence needs to be documented. Someone assumed a vendor could do something they aren't actually authorized to do.

None of those things are especially surprising in a regulated environment. They're only surprising if nobody asked about them early enough.

I want to understand those boundaries while we're still figuring out the solution. If we're introducing a vendor, new access, an integration, or a different type of data, I want to know whether that changes the path to production.

You don't need every answer on day one. You do need to know which questions are going to matter later.

## Controls are dependencies

Projects get into trouble when governance is treated as paperwork instead of part of the work.

If a production change needs approval, that's a dependency. If Security has to review the solution, that's a dependency. If Procurement needs a contract completed before equipment can be ordered, that's a dependency too.

Once you look at controls that way, they belong in the same plan as everything else required for go-live.

A required approval shouldn't magically appear as a blocker three days before go-live when everyone has known for three months that it was going to exist.

## Some decisions need a trail

In a regulated environment, sometimes you need to be able to show what was decided and who approved it. You may also need a record of what was tested or what changed before something moved into production.

That doesn't mean documenting every conversation anyone has ever had. It means knowing which decisions need a record.

I've worked with formal change and release processes where production deployments had defined testing, approvals, implementation plans, and controls around how changes were introduced.

The change process is part of how the organization knows what's entering production and whether it's ready to be there.

## Deal with risk while you still have choices

Risk management can become strangely ceremonial if you're not careful.

A risk register nobody looks at isn't doing much for the project.

I'm more interested in the practical side. I want to know what could prevent us from moving forward and which dependencies I'm least confident about. If something will be much harder to fix after go-live, that's worth knowing now.

Then we decide what we're going to do about it.

I'm much more comfortable accepting a known risk than discovering an obvious one after we've run out of good options.

## Testing includes the environment around the technology

Successful testing isn't only about proving that the main function works.

Access and integrations need to work too. The right people need the right permissions. We need to understand what else the change might affect and what happens if we have to back it out.

That's one reason I like having both technical and operational people involved. A technical test can tell you whether the system behaves correctly. Someone who understands the workflow can tell you whether that behavior actually makes sense where it will be used.

You need both.

## "Fast" and "controlled" aren't opposites

What slows teams down is often uncertainty.

Nobody knows who needs to approve something. Security gets involved too late. A required document doesn't exist. Procurement starts after everyone expected equipment to arrive. Testing has to be repeated because nobody captured the evidence the first time.

Those aren't problems caused by having controls. They're problems caused by not planning for them.

A repeatable approach can actually make controlled deployments faster because the team already knows what has to happen and when.

## The process can still get better

Working within controls doesn't mean accepting a bad process forever.

If the same approval regularly causes delays, I want to know why. If teams keep missing the same requirement, move it earlier. If we're recreating the same documentation every time, build something reusable.

That doesn't mean quietly working around a control because it's inconvenient. It means understanding why the control exists and working with the people who own it when there's a better way to meet the same need.

When "just ship it" isn't an option, that's fine.

I just want to know what it takes to ship it before we're standing at the finish line.


---

[← Previous](./03-from-pilot-to-deployment.md) | [Back to README](./README.md) | [Next →](./05-deploying-physical-technology.md)
