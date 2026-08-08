# Pressure Test: A Complex Grant Through the Model

The five-workflow model in the main README is easy to validate against a clean, average-sized domestic grant. The real test is whether it holds up against the grant that breaks every assumption at once. This is a theoretical scenario built specifically to stress it, and an honest accounting of where the model needed to bend.

## The scenario

A $40M commitment to an international research consortium, surfaced with three weeks' notice because a time-sensitive scientific opportunity will close if funding isn't confirmed by a fixed date. The grantee is a foreign research institution with no U.S. tax status, so it can't be treated as a standard public charity grant. The board wants the money moving before the standard diligence cycle would normally complete.

This scenario is designed to hit the model in three places at once: compressed time, cross-border legal complexity, and pressure to skip steps under real organizational urgency.

## Running it through the five Workflows

### 1. Infrastructure

The grant register and tracker handle this fine as long as they were built to record structure type as a first-class field, not an afterthought. If "domestic public charity" was the only structure the system assumed, this grant has nowhere to go. The infrastructure workflow has to account for equivalency determination and expenditure responsibility as tracked states from day one, not a special case bolted on later.

### 2. Diligence and Structuring

This is where the pressure is highest. A standard diligence protocol sized for a domestic grant does not fit a foreign grantee under a three-week clock. The model's answer isn't to skip diligence - it's to have a pre-built expedited path: a defined, still-rigorous diligence track for time-sensitive grants, with equivalency determination or expenditure responsibility review run in parallel with legal structuring rather than sequentially. If that expedited path doesn't exist before the grant shows up, it gets improvised under pressure, which is exactly how compliance gaps happen.

### 3. Execution

Templated agreements by structure type only work if "foreign grantee, expedited timeline" was anticipated as a template, not written from scratch under deadline. This is a direct test of whether the infrastructure workflow's template library was built broad enough or just built for the common case.

### 4. Administration and Monitoring

Once funded, this grant needs tighter monitoring than a standard domestic grant, not looser - cross-border grants carry more reporting risk, not less. The model holds here as long as risk tier, not just dollar amount, drives monitoring intensity. A $40M international grant and a $40M domestic grant should not get the same review cadence.

### 5. Modifications and Closeout

International, time-pressured grants are the ones most likely to need a scope amendment six months in, when the on-the-ground reality diverges from what was diligenced in three weeks. The model needs the amendment path to be genuinely fast to use, not just theoretically available - otherwise program teams route around it, which is the exact adoption failure this whole model exists to catch.

## Where the model held, and where it needed to bend

It held: the five-workflow separation itself. Even under pressure, keeping diligence, execution, and monitoring as distinct trackable states - rather than one collapsed "grant is active" status - is what let the compressed timeline get visibility instead of getting buried.

It needed to bend: the model as written in the main README assumes diligence is a single sized protocol. Under this scenario, diligence needed a second dimension - not just size, but urgency and jurisdiction - with a genuinely pre-built expedited path, not a one-off exception. A framework that only works at normal speed isn't a real operations framework; it's a description of the easy case.

## What this means for the build order

The "first 90 days" plan in the main README holds, with one addition: the expedited diligence path and the foreign-grantee structuring template can't be phase-two work. If they're built after the first complex grant already needs them, the foundation is back to improvising under deadline - the exact failure mode the infrastructure workflow was supposed to prevent.
