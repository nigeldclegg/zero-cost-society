# Transport

**Domain:** transport
**Status:** developing

## What it is

Moving people and goods without private vehicle ownership, without most of the space currently given to roads and parking, and without money at any point in the transaction.

Two separate systems doing two different jobs. People move on the surface in shared, driverless vehicles that nobody owns. Goods move underground, in small automated tubes, between communities.

Splitting them is the key structural move. A vehicle carrying a person must be comfortable, human-sized and safe at human tolerances. A vehicle carrying potatoes has none of those constraints — it can be small, fast, and entirely out of the way.

## Why the current system prevents it

**Private ownership is enforced by necessity, not preference.** In most places you must own a car to participate in normal life. That requirement puts roughly a tonne of steel per household into a system where each unit sits unused about ninety-six per cent of its life.

**The land cost is invisible because it was paid long ago.** Between a third and a half of urban land is given over to roads and parking. Nobody decided this in one go; it accumulated. It is the largest land subsidy in history and it appears on no balance sheet.

**Selling cars requires cars to be sold.** An industry whose revenue depends on individual ownership will not build the system that removes the need for it. Car-sharing schemes exist, and are structured to supplement ownership rather than replace it, because the alternative would be corporate suicide.

**Public transport is priced as a service rather than treated as infrastructure**, which makes it a cost centre to be trimmed. Routes that people need but that do not pay get cut, which pushes more people into cars, which reduces revenue further.

**Freight and passengers share the same congested surface**, because building a separate freight layer is enormously expensive and returns nothing to whoever pays for it — even though it would be cheaper for everyone within a generation.

## How it works

### Context

Applies at community and inter-community scale. The surface system works from a few dozen vehicles upward. The underground goods layer only makes sense between multiple communities and therefore comes later — it is what turns a set of separate places into a network.

Both depend on cheap electricity and reliable automation. Neither is speculative technology; both exist.

### What to look for

**Surface: shared driverless vehicles.**

Nobody owns them. You request movement and a vehicle arrives. It is not parked afterwards — a vehicle that is needed elsewhere goes elsewhere. Removing ownership removes parking, and parking is most of the land.

The safety case rests on something specific: **cooperative perception**. Every vehicle continuously shares what its sensors see with every vehicle near it. A vehicle approaching a blind bend has already seen what is round it, through the eyes of the vehicle already there. No human driver has ever had this. Every networked vehicle has nothing else.

Networked vehicles also cannot become bored, distracted, angry or drunk — the causes of most road deaths.

**Underground: automated goods tubes.**

Small-diameter tubes carrying containers of goods between communities. Because there is no human inside, the constraints collapse: the tube can be narrow, the acceleration brutal, the schedule continuous. What is spare in one place moves overnight to where it is short.

This is the physical layer of resource sharing. Without it, every community must be self-sufficient in everything, which is a hard constraint that no island ever managed well. With it, a network can specialise, cover each other's failures, and share surplus as a matter of routine rather than emergency.

### What the variations mean

**The reaction-time chain.** Safe following distance derives from human reaction time — over a second and a half, once perception and decision are included. Road capacity derives from following distance. A networked vehicle reacts in milliseconds and to what the *network* sees, not what it sees. Following distances collapse, and road capacity rises several-fold on unchanged tarmac.

**Junctions without signals.** Traffic lights exist to sequence humans who cannot negotiate. Networked vehicles can negotiate crossings continuously, threading gaps, which removes both the signals and the stop-start that causes most urban congestion.

**Storage is the real land cost.** Movement uses less space than people assume. Stationary vehicles use enormous amounts. Removing ownership recovers more land than removing traffic.

### Procedure

1. **Start with a small shared fleet within one community**, on internal lanes. Positional markers in the road surface are cheap and give centimetre accuracy without depending on satellite positioning.
2. **Extend to the lanes between neighbouring communities.** This is where the legal and regulatory difficulty begins.
3. **Add cooperative perception** once there are enough vehicles for shared sensing to be worth anything.
4. **Only then consider the underground layer**, which needs several connected communities to justify.
5. **Recover the land** as parking demand falls, and do it deliberately — the space does not reallocate itself.

### Common failures

**Building it as a taxi service.** If vehicles are requested, dispatched and accounted for like a paid service, the money logic re-enters through the door marked "efficiency" and ownership follows.

**Underestimating the permission problem.** The engineering is comparatively easy. Getting legal permission to run automated vehicles on public roads, and to tunnel under land you do not own, is the actual work, and it is measured in years.

**Ignoring who travels and why.** Engineers model journeys; people have lives. Someone who has driven a bus route for thirty years knows things about movement that no sensor knows — who travels when, and what a route is actually for. This knowledge is routinely omitted and its absence shows immediately.

**Keeping the cars.** Communities that retain private vehicles "for flexibility" retain the parking, and therefore the land loss, and therefore most of the problem.

## What cannot be written down

Less than in most domains — transport is unusually amenable to documentation, because much of it is genuinely engineering.

What does not transfer: local knowledge of a place's movement patterns. Where people actually need to go, when, and why. Which routes matter socially rather than economically. What time the school run distorts everything. This is knowable only by living somewhere, and it is the difference between a system that works on paper and one people use.

## Evidence

**Vehicle utilisation.** Private cars sit unused approximately ninety-five per cent of the time — a figure consistent across multiple national transport studies (RAC Foundation and equivalents).

**Urban land given to vehicles.** Estimates range from about a quarter to over half of city land depending on the city and what is counted. Los Angeles sits at the high end; dense European cities lower. Donald Shoup's *The High Cost of Free Parking* is the standard reference.

**Autonomous vehicles.** Commercially operating driverless passenger services now run in several cities. The technology works within limits; the debate is about edge cases, regulation and liability, not feasibility.

**Cooperative perception.** Vehicle-to-vehicle communication is an active, well-published research area with demonstrated safety gains. Not yet deployed at scale, because it requires a critical mass of participating vehicles that a market of competing manufacturers does not naturally produce — a coordination failure that a single network does not have.

**Automated freight tubes.** Small-scale pneumatic and rail-based automated freight systems exist industrially and in hospitals. Inter-city underground freight has been repeatedly proposed and never built at scale, mainly on cost grounds. There is no working precedent for the version described here.

**Car-free areas.** Numerous European cities have removed cars from central districts with documented gains in air quality, safety and street life. Not the same as this proposal, but evidence that the land recovers its usefulness quickly.

## Unsolved

**The tunnelling cost.** The underground goods layer is expensive to build and there is no precedent at the proposed scale. Whether it is worth it compared to simply running goods on the surface network at night is an open and legitimate question.

**Permission.** Who grants the right to tunnel under land nobody in the community owns? This is a legal and political problem, not a technical one, and no community has solved it.

**Long distance.** Everything here is local and inter-community. Movement across a continent, and aviation in any form, is entirely unaddressed and is a serious gap.

**Emergency and edge cases.** Ambulances, fire, evacuation, someone who must get somewhere now. A request-based shared system must handle priority, and how it does so without reintroducing hierarchy is not worked out.

**Rural sparsity.** Shared fleets work through density. A community of forty people spread over a valley may not reach the vehicle numbers that make cooperative perception or on-demand response viable.

**Manufacturing.** Where do the vehicles come from? Building them requires an industrial base, which currently means buying from the money economy. See `making.md`.

## Objections

**"Driverless vehicles are not safe enough."**
Partly fair. Current systems handle common conditions well and unusual ones less well. The response is that they need not be perfect, only better than humans, and the bar is low — over a million road deaths a year globally, almost all from attention failures machines do not have. But "better on average" is cold comfort in a specific failure, and liability remains genuinely unresolved.

**"People love their cars."**
Many do. The claim is not that nobody enjoys driving; it is that most car use is not pleasure but requirement. Where genuinely good alternatives exist, ownership falls sharply. Some people will want to drive for its own sake, and a system that cannot accommodate that at all is probably wrong.

**"This requires enormous upfront investment."**
Yes. The surface system is affordable at community scale; the underground layer is not, without external resource. This is the strongest practical objection and it has no clean answer beyond the observation that current road infrastructure also cost an enormous amount and is simply already paid for.

**"Automation destroys driving jobs."**
It does. Driving is one of the most common occupations in most developed countries. The response is that in a system where livelihood is not tied to employment, removing arduous work is a benefit rather than a catastrophe — but that response is only available *after* the transition, and during it the objection is entirely valid and largely unanswered.

**"Underground freight is science fiction."**
Not technically — the components all exist. Economically, at scale, it has never been done, and a fair reading is that it has repeatedly failed to be built because it does not pay under current accounting. Whether it makes sense under different accounting is exactly the claim, and it is unproven.

**"Shared vehicles get filthy and vandalised."**
Real experience from shared bicycle and scooter schemes is mixed and this is a genuine problem. The counter-observation is that shared systems inside communities where users know each other behave very differently from anonymous city schemes — which is an argument that this works at community scale and may not at metropolitan scale.
