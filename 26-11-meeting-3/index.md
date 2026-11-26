
> 1. Do you want to understand rather the structure or the behaviour of
> 'governed AI context(layer)' or both?
> 2. How do you want to study/oberve it? In design-time, build-time,
> inference/agent-time (agent loop), during run-time (e.g., through audit
> traces) or post-hoc, e.g., post-mortem, for incident management?
> 3. How do you want to specify the AI vs. Human agent "barrier"? How can
> Human-in-the-Loop fatique, e.g., rubber-stamping or skill atrophy be
> avoided?



Structure or the behaviour of context

How to study/observe it. 

* Design-time - brief, just do a simple organization mock and different data products require different access
* build-time - process of defining and changing the policies is out of scope
* what is difference between agent-timeand runtime?

* post-hoc, incident management - out of scope



* AI vs Human agent barrier
  * this is what most systems miss. what about the deterministic layer? define well what the agent can't and shouldn't do
  * I want to create a process that has no human in the loop. access policies are well defined and thre are clear, deterministc, governed paths to the information a human can get during the session
