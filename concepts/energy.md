# Energy

**Domain:** energy
**Status:** developing

## What it is

Generating, storing and distributing enough energy for a community without buying it, and without the generation being owned by anyone.

The claim underneath this project rests here more than anywhere else. Cheap energy is what makes intensive growing possible, what moves goods without fuel, and what turns manufacturing into something a community can approach. If the energy argument fails, most of the rest fails with it.

## Why the current system prevents it

**Energy is sold, so using less is a problem to be managed.** Every supplier's revenue depends on consumption. Efficiency is therefore something the industry tolerates rather than pursues, and demand reduction is a threat to be offset.

**Generation is centralised because centralisation is billable.** Large plants and long distribution networks concentrate ownership, and the meter at the end is what makes the model work. Distributed generation that nobody meters is not a technical problem, it is a commercial one.

**Infrastructure is built for return, not for need.** Grid connections arrive where they pay. Communities on the wrong side of that arithmetic wait decades or pay enormous connection costs for capacity that exists a mile away.

**Storage is undervalued because the market rewards supply, not resilience.** A system optimised for cheapest delivered unit is fragile in ways that only show during failure, and failure is priced as somebody else's problem.

**Fossil generation carries costs it does not pay.** Extraction, emissions, health effects and climate damage sit outside the price, which is why the cheapest energy on the ledger has been, for a century, the most expensive energy in reality.

## How it works

### Context

Applies at community scale — tens to hundreds of people, with land. Assumes temperate maritime conditions unless stated; solar-dominant and arid contexts differ substantially and need their own treatment.

Nothing here is speculative technology. Every component described is commercially available and unremarkable.

### What to look for

**Match the source to the place.** Wind suits exposed upland and coastal sites and produces most in winter. Solar suits everywhere but produces least exactly when demand peaks in northern winters. The two are complementary rather than competing, and a community with both needs far less storage than one with either.

**Demand shape matters more than total demand.** Energy that can be used whenever it is available is nearly free. Energy that must be available at a specific moment is expensive. Growing systems, water pumping, heating stores and most automated processes can be scheduled around supply rather than the reverse — which quietly removes most of the storage problem.

**Heat and electricity are different problems.** Heat is easy to store, cheaply, in water and in mass. Electricity is not. A community that stores heat as heat rather than converting it twice avoids most of the expensive part.

**Ground as a battery.** Ground-source heat exchange and seasonal thermal storage are dull, well-understood, and disproportionately effective in temperate climates. Unfashionable and worth more than it looks.

### What the variations mean

**Winter, not annual, is the design case.** Systems sized on annual averages fail in the second week of a still, dark January. The relevant number is the worst plausible fortnight.

**A shortfall is usually a demand-shape problem, not a generation problem.** Before adding capacity, look at what is drawing power when, and what could be moved.

**Storage sized for autonomy is enormously expensive; storage sized for smoothing is cheap.** The cost difference between covering a bad night and covering a bad fortnight is not linear, and communities routinely bankrupt themselves on the last ten per cent.

**Connection to the wider grid is a resilience decision, not an ideological one.** A community that stays connected can export surplus and draw during a still week. Refusing connection on principle usually means building far more capacity than would otherwise be needed.

### Procedure

1. **Measure the demand shape first**, before sizing anything. What is used, when, and what could be moved.
2. **Reduce and reshape before generating.** Insulation, heat recovery, and scheduling flexible loads are cheaper than any generation.
3. **Build generation matched to the site**, sized against the worst fortnight rather than the annual average.
4. **Store heat as heat.** Water tanks, mass, ground. Cheap, dull, effective.
5. **Add electrical storage last and modestly**, sized for smoothing rather than autonomy.
6. **Keep the grid connection** unless there is a specific reason not to.

### Common failures

**Sizing on annual averages.** Produces a system that works beautifully for ten months and fails in the two that matter.

**Chasing autonomy.** Full independence from the grid is a badge, not an engineering goal, and it is where communities spend money they need elsewhere.

**Converting heat twice.** Generating electricity to make heat that could have been stored as heat is a large and common waste.

**Ignoring maintenance.** Generation installed by an outside contractor with no local knowledge becomes unmaintainable the day the contractor stops answering. Attach learners to every installation.

**Treating efficiency as finished.** Demand grows to fill supply, quietly, over years, until the system that was comfortable is marginal.

## What cannot be written down

Less than in most domains here — energy is genuinely engineering, and engineering documents well.

What does not transfer: knowing a specific site. How the wind actually behaves on that hill as opposed to how the wind map says it does. Where the frost sits. Which fortnight in that valley is the hard one. This is a year of watching, minimum, and it is the difference between a system sized correctly and one sized from a spreadsheet.

## Evidence

**Cost curves.** Solar photovoltaic and onshore wind are now the cheapest sources of new electricity generation across most of the world, having fallen by roughly ninety per cent and seventy per cent respectively over the past decade and a half. This is the single strongest empirical claim in this repository. Sources: IRENA's annual cost reports, IEA, and Our World in Data's energy section, all public.

**Battery costs** have fallen on a similar curve, though from a higher base and with more contested supply chains.

**Community energy works and is documented.** Denmark's wind cooperatives, and community energy projects across Germany, Scotland and Wales, demonstrate community-owned generation operating for decades. Most sell into a grid rather than operating outside money, which is a real difference, but the technical and organisational precedent is solid.

**Seasonal thermal storage** is proven at district scale, most notably in Denmark and Canada, including systems storing summer heat for winter use.

**Passive building** performance is well evidenced: the Passivhaus standard and equivalents demonstrate that heating demand can be reduced by around ninety per cent through fabric alone. Reduction is cheaper than generation and this is the least glamorous, most effective intervention available.

## Unsolved

**Manufacturing the equipment.** Panels, turbines and batteries come from industrial supply chains no community can replicate. Every community described here is dependent on the money economy for the hardware that frees it from the money economy. This is a genuine contradiction and it is not resolved. See `making.md`.

**Materials and their costs.** Lithium, cobalt, rare earths and copper carry serious extraction impacts and, in several cases, serious human costs. A project premised on "all money comes at a cost" cannot wave this away, and this repository currently does.

**End of life.** Panels last decades and turbines less; recycling exists and is immature. What a community does with a field of dead panels in thirty years is unaddressed.

**Long dark still periods.** The northern European winter anticyclone — a fortnight of no wind and little light — is the hard engineering case and the honest answer is oversizing, storage, or grid connection, all of which have costs.

**High-temperature industrial heat.** Some processes need temperatures that are hard to reach without combustion. Relevant to making anything.

**Aviation and shipping.** Not addressed anywhere in this project and not solvable at community scale.

## Objections

**"Renewables are intermittent and can't run a society."**
Intermittency is real and the standard responses — geographic spread, source diversity, storage, demand flexibility and interconnection — are well evidenced at grid scale. The honest limit is that no large economy has yet run entirely on renewables without fossil backup, and claiming the problem is fully solved would be false.

**"This depends on a global industrial system you claim to oppose."**
The strongest objection on this page, and it is correct. Every solar panel comes from a supply chain involving mining, international shipping and factories run for profit. A community running on renewables is not outside the money economy; it has bought its way to a comfortable position inside it. This project does not have an answer, and any version of it that pretends otherwise should be distrusted.

**"The materials have their own human and environmental cost."**
Also correct. Cobalt mining in particular carries documented human costs. The comparative response — that fossil extraction is worse in scale and duration — is true and is not a defence, only an accounting.

**"Community energy exists already and hasn't changed anything."**
Fair. Hundreds of community energy schemes operate within the existing system, selling power and distributing profit. They demonstrate the organisational form works while leaving the underlying logic untouched. The claim here is that the same technology inside a moneyless community does something different, and that claim is untested at any scale.

**"Efficiency gains get eaten by increased demand."**
The rebound effect is real and well documented. The response is that rebound is driven by price — cheaper energy invites more use — and that a system without price has a different, and untested, dynamic. Possibly better. Possibly worse, since nothing restrains use at all.
