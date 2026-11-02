* generalizing to entire CS - difficult to prove
* specialize to specific industry or concept - achievable




* continuous architecting -> write down only the components I need 
  * verify or falsify the statement
* other options -> how, why Data Mesh exists - focus on bits that have not been solved yet.
  * multi-vocal empirical study - gray literature x interviews

method must be
* robust
  * reproducible
* not a new invention

if i go to multi case study, compare x different case studies in different concepts, but **same** research question.

also contribute to business relevancy

if not case study: formal modeling of gray literature sources or other literature sources, based in grounded theory, qualitative research paradigm - where I don't answer a question but at the end formulate a theory.

option 1:

Hypothesis - Data Mesh compexity can be measured by .... 
The metric number (# microservices) - find out the actual number
7 components - hypothesis - go into the field and do interviews - how many services can you manage? - loc, kloc


the other way around is go directly into the field
* take gray literature, like blog articles, or interviews


option 2:
ask why, gray literature, conferences, specific statements, code it (grounded theory, comparitative analysis) - interviews and gray literature either converge or diverge. 10-15 interviews or 30-50 gray literature sources. Theoretical saturation - if I add one more interview, I don't get any more information. - qualitative goal of the theory building. Find out - it's not only about technology, but about how to connect industries, interweave the standards into existing infrastructure. - Gaia-X relies a lot on the concept of federation - trusted parties are allowed to issue things and to check the formal requirements of data sharing. Member list - a lot of telecom providers, cloud service providers from europe. telecom motivation - bandwidth, they provide the infrastructure, 

question - how efficient data mesh is compared to gaia-x ("standard"). Take the open source implementation from them and run in loops of data sharing requests. 

focus on one level (energy, compute)... 

Telecom - take over the role of a trusted party - confirm whether you are compliant in the process of data sharing, or provide access 

- Gaia x goal - create a new data market - telco will get a share of transactions.

IDSA - international data space association - kind of competing with gaia-x
gaia-x completely taxpayer, idsa e.g. microsoft involved 

nexyo 


need to decide - data spaces and infrastructure (use/buy data). It would make sense to mention the stack of interoperability. But intra-organizational data sharing is a different scope.

what about bodies of government - kind of both. E.g. in Austria there is an EU wide law for open data - govmts who build datasets using taxpayer money need to make collected data public. Second layer - everything in law enforcement - they need to share data, not publicly, but have to - e.g. insurance and police, employment and finance, ams etc.

But when it comes to environmental organizations - they need to share satellite data and they might build another data product from that.



"is it possible" to assemble a Data Mesh using open source tools.
frame it a bit differently - hypothesis - it is possible that... 
Instantiate a data mesh in 2 seconds.


todo dbt now part of Fivetran

measuring compexity is difficult - in terms of entropy of systems


Margaret Storey

icse 2019 keynote
look at her slide deck - formal sciences, explanatory, design sciences.

for research - build rigor cycle, and knowledge base. interaction with the environment keeps it relevant.

instantiation - solution construct - data mesh, solution instance - canonical data mesh. missing: generalized ability.
measure developer experience

"publish or perish

works for canonical is one question, doesnt mean it will work for others.

maybe we're talking more about the data mesh components and more about the gluecode.


statement - some kind of a limit or a possibility. would be interesting to make it simple somehow - some research question that tries to come up with a little theory of operational intelligence. 3 mini-theories:

* you manage huge overhead you need for establishing connections
* ...
* ...

I could solve this by going into the field, making notes, building the knowledge base.

"operational intelligence"

another direction would be to build one artifact which is missing, for example 
* distributed tracing

there are other orchestrators out there. 

would be good to focus on the hypothesis that Canonical has: orchestration needs to work like "this and that" - usually needs to have 2 or 3 arguments why, which problem does it solve.

compare it with other orchestrators the same way. focus on similar concepts that I define, measure - how long does it take to orchestrate a service with tool xyz - measure it in different ways.


I could collect blog articles about orchestrations - classify into "practitioners reports". E.g. Netflix - they have engineering articles, Uber, Discord - they share what didn't work - this is a viable source for finding out what works and what doesn't. - dependency tree didn't resolve, etc. If I am able to find some patterns, then the case could be made. A few patterns would already be a strong result - 15-20 high value engineering articles that converge on a specific industry best practice. - this is a descriptive methodology. 

e.g. if sidecar pattern is mentioned often - out of 30, 29 say sidecar is main - architectural pattern for operating a specific service. 

---

Currently there is a trend of "continous" - custom orchestrator.

new paradigm currently on the horizon - no data to work on. - hyper-agile development with zero dependencies.

---

Feline Hermans - from netherlands - recently talked at DDD event - watch the talk 

https://www.youtube.com/watch?v=0-6-f94n_9M

---

maybe see some patterns in the gray literature

---

existing research - "design smells"

---

Margaret's research and framing - look at titles

---

self-hosting could also be a filter

---

all enterprise/ctos say they can't afford AGI, they need their specialized models. 

DORA - financial regulation.

--- 

what are the barriers of self-hosting the Data Mesh.

---