# OCE-100 — Objective Conceptual English

Issue 1. A controlled writing standard in the form of ASD-STE100. ASD-STE100 restricts aerospace English so a maintenance procedure is unambiguous. OCE-100 restricts expository English so a claim can be checked against the facts it names.

## Purpose

Force every term to one meaning, every action to a named agent, and every abstraction to the concretes or prior concepts that justify it.

## Scope

Expository, technical, and procedural writing. Not dialogue, not fiction, not slogans.

What it governs: word choice, definition order, sentence form, and the trace from a claim to its referents.

What it does not govern: which facts are true, what the writer values, or any program for a life. A false sentence can still be OCE-100 compliant. Compliance only means the sentence is checkable.

## Word rules

1. Give each word one meaning and one part of speech in a given text. If you need a second meaning, use a second word and define it.
2. Do not rotate synonyms. Pick one verb for one action and keep it (`measure`, not `measure` / `assess` / `evaluate` for the same operation).
3. Define a new term before its first use. Give genus and differentia. Do not define by non-essentials or by negation alone.
4. A technical noun may enter once defined. A package-deal may not. Split it, name the parts, and state the relation you claim. `Stakeholder`, `society`, `the public`, `equity` (as equal outcome), `sustainability` (with no metric or time span), and `the greater good` fail this test until split.
5. Do not use an anti-concept (a word that only negates) until you have named the positive it attacks.
6. `Value`, `price`, `cost`, and `profit` name a relation between a voluntary exchange and the purposes of the parties. They are not moral accusations. If you mean a moral judgment, write the judgment in other words and give the standard.
7. Count metaphors. Keep one only if you can state the shared attribute. Otherwise delete it.

## Sentence rules

8. Name the agent of every action. Use active voice when the agent is known. Passive voice is allowed only when the agent is unknown and you say so.
9. One claim or one instruction per sentence.
10. Limit a procedural or claim sentence to 25 words. A formal definition may run longer.
11. Do not write `it is known`, `experts agree`, `one must`, or `studies show` as the subject. Name the person, the method, or the measurement.
12. Do not use `should` or `must` unless the sentence names the beneficiary and the means. An unearned obligation is not a sentence; it is a gap.

## Concept rules

13. Do not use a concept that rests on concepts you have not yet established in the text or in an explicit prior reference. If you use `rights`, `proof`, or `ownership`, the facts those words rest on are already on the page or cited.
14. Tie every abstract noun to its concrete, or drop it. `Better`, `efficient`, and `value` are incomplete until the text names the quantity, the meter, or the trade.
15. On demand, a footnote or an earlier sentence must trace an abstraction to the referents that justify it.
16. Replace a collective noun with the specific persons or the named organization, unless that organization has defined members and you are writing about the organization.

## Procedure rule

17. End a procedure with the observable result that shows the step succeeded. Name the unit. `The fuel meter reads 12 percent lower` passes. `The process is more sustainable` does not.

## Worked example

Uncontrolled:

> Companies should embrace stakeholder capitalism so that innovation serves the community and delivers inclusive, sustainable growth.

OCE-100:

> A producer offers a product at a price. A customer buys it if the price is lower than the result he expects from it. The exchange is the evidence of that result. No person who does not buy sets the price. A firm that replaces its boiler and cuts measured fuel use by 12 percent keeps the saved cash. The fuel meter, read before and after, is the check.

## News example (2 October 2026)

Uncontrolled:

> The Group of Seven moved Friday to stabilize energy markets and shield households from the fallout of the U.S.-Israeli war with Iran. Meeting under French presidency, leaders agreed on decisive, coordinated measures to release 100 million barrels of diesel and crude from emergency reserves over four months, with a substantial diesel release frontloaded inside 20 days. The International Energy Agency will coordinate the draw. The war has throttled traffic through the Strait of Hormuz and driven an affordability crisis. European diesel prices have doubled since the fighting began in late February, and the bloc has paid more than €100 billion extra for fossil-fuel imports without receiving additional energy. President Trump pressed allies to act and welcomed the deal. Members also pledged not to ban energy exports. The March IEA action, the largest in the agency’s history, has already put about 325 million barrels into the market out of 400 million pledged. Officials said further diesel releases could follow if needed, and expressed hope the step would cool prices and strengthen long-term resilience.

OCE-100:

> On Friday, 2 October 2026, the governments of Canada, France, Germany, Italy, Japan, the United Kingdom, and the United States agreed to sell or lend 100 million barrels of diesel and crude oil from stocks they hold for emergency use. France holds the rotating G7 presidency. President Emmanuel Macron chaired the meeting. The International Energy Agency will schedule the release. The release starts now and runs four months. A large share of the diesel is due inside the first 20 days. The statement does not say how many barrels are diesel, how many are crude, or which government supplies which volume.
>
> The same governments say the release answers a price rise they attribute to the U.S. and Israeli war with Iran. Iran has restricted ship traffic through the Strait of Hormuz. The European Commission says diesel prices in Europe have doubled since the end of February. Commissioner Dan Jorgensen says EU buyers have paid more than €100 billion extra for fossil-fuel imports since the war began, and have not received more fuel for that money. Ukrainian strikes on Russian refineries have also cut diesel supply. The text does not separate those causes by volume.
>
> President Donald Trump asked the other governments to release diesel stocks. He welcomed the agreement. The statement says the seven will not ban exports of energy products. Macron said Trump was explicit on that point.
>
> In March the IEA’s 32 members pledged 400 million barrels. Director Fatih Birol says about 325 million barrels of that pledge have been released. The 2 October statement does not say whether the new 100 million includes the unreleased remainder of the March pledge or adds to it. As of Tuesday, Germany had not released about 77 percent of its March pledge. Spain had released about one third. The United States this week approved another 40 million barrels from the Strategic Petroleum Reserve and called its share complete.
>
> A barrel in a government tank is not diesel in a truck. Crude must be refined. Refinery capacity, shipping, and the grade of crude set how much extra diesel reaches buyers, and when. The statement names no price target and no meter that would show the release succeeded.

## Dictionary posture

The core stays small and open to technical nouns once defined by essentials. Production and measurement verbs are preferred: `build`, `measure`, `trade`, `own`, `prove`, `replace`, `read`. Words that conceal a package-deal are not banned as politics. They are rejected until split, because an unsplit package-deal cannot be checked.

## Agent skill

Agents that rewrite prose under this standard should load `.agents/skills/oce-100/SKILL.md`.
