## Terms

- **Knowledge and truth:** knowledge is defined as understood information, and an agent can understand something false, so the word's usual sense of truth does not hold. "Belief" loses the sense of usable know-how. Proposed: keep "knowledge", defined as understood information that may be false; truth is judged by comparing it with the state.
- **What a role or agent has:** a single word for its resources, tools and access to information sources. Proposed: "holdings", as a plain list and not a shared class.

## Elements

- **Tool and agent:** whether a tool is best seen as an agent without choice.
- **Role:** whether a role also holds resources and access to data.
- **Skill and knowledge:** how they relate. Proposed: each skill lists the knowledge it needs, if any, and nothing else is assumed.
- **Action requirements:** whether meeting an action's requirements (knowledge, tools) is what makes it available to an agent.
- **Graded knowledge:** skill has levels: for some skills an agent either can or cannot do the thing, but proficiency and speed still vary. Whether knowledge has levels too is open. Proposed, and agreed in principle: knowledge is held as items, each understood or not; skill carries the levels. Doubt remains about treating a large body of knowledge as a set of smaller pieces.
- **Time:** time is a strange resource, if it is one at all. An agent does have a certain amount of working time per period, and well-being, once modelled, may bring better concepts for it. Whether to model working hours is open: it may be a large cost for uninteresting change. Proposed: model it as capacity, the amount an agent can spend on actions per period; not a resource, since it cannot be stored or moved, and renewed each period; working hours not modelled, the length of a period a setting. Needed because the split between exploring and direct work is a split of capacity, and overloaded roles become bottlenecks only if capacity is limited.
- **One action at a time:** a person works on one thing at a time unless a task involves waiting, when the time can go elsewhere. Whether this is worth modelling is open. Proposed: no simultaneity; capacity within a period can be split across actions, an action waiting on something else consumes no capacity, and arriving requests consume capacity to read. A switching cost could be added later as one parameter.
- **Choice rule:** to be defined later; for now choice is by probability. Its inputs (view, foresight, understanding, predisposition, aims, push, attention) overlap and need consolidating into a short list first.
- **Motivation and compliance:** why an agent follows a request beyond the sender's authority, and what pay, fatigue, satisfaction, leaving, informal influence and persuasion do. Absent for now.

## State and view

Current view:

- The state is the truth. The consequences of actions fall on it.
- Each agent has a view: its own perspective, from which it chooses. The view holds what the agent knows, what it expects actions and sources to give, and its biases and limitations. It can be partial, delayed or distorted.
- Choice is made from the view, never from the state. The gap between the two is what structure shapes.

Open:

- **Contents of the view:** what exactly it holds (data, knowledge, expectations, plans, requests received), and where a received message sits before it is read. Proposed: a received message is an unread information source until the agent reads it; reading is an action that takes capacity and puts the message's content into the view; overlooking then follows from limited capacity.
- **Bias and limitation:** how foresight, understanding and predisposition are represented in the view and enter the choice.

## Action

Current view:

- Each thing an action can give has its own probability, rather than a single yield rule.
- The flow of information, and how each agent processes it, must be represented: it is essential for how managers decide on information from below, and for each agent's biases.
- To scale, action types will need templates, with each role a variation of a template, and new variations created automatically, for example when a new resource is discovered. What then keeps new actions realistic (not extracting too much too fast) and sets the speed of improvement is open.
- What the model does not define cannot happen in it. This is intrinsic to any simulation.
- Requests differ in priority and in the level they come from: enforcing is a request with high priority from a higher level; asking for help is one with medium priority from an equal level.

Open:

- **One form for all actions:** proposed: every action has a performer, needs (present, not used up), uses up (time, resources), applied to (source, tool, agent or nothing) and outcomes, each with a probability that depends on what went in. Sources and tools are what actions are applied to. Whether the form belongs to the action or to the object is open.
- **World chance and agent propensity:** proposed: probabilities in an action's outcomes are chance in the world only; which action an agent takes, and with what effort, is the agent's choice and depends on its view, foresight, understanding, predisposition, aims and push. The two are kept apart.
- **Decision, request and plan:** current view: a decision is a choice between actions. Carrying it out on others is an action that asks the receiving agent to perform an action, which may be limited to certain kinds of agent or to a deadline. A plan is a series of actions to be requested at certain times; plans differ in how adaptable they are. Proposed on top of this: no separate "decision" action type; a request is information stating what someone wants done and by when, weighed in the receiver's choice by the sender's authority; an approval is information that satisfies a need of an action; a plan is information held by an agent, making one is an action, and following one is part of choice.
- **Events:** changes nobody chooses, such as data going stale, tools wearing, external shocks and technologies arriving from outside. Proposed: a second kind of state change beside actions.
- **Bounds on new actions:** proposed: agents never make up actions; they realise possibilities, and each possibility carries the parameters of what it enables (rates, requirements). Improvement speed then follows from how fast the chain of possibilities is found.

## Exploring information sources

Current view:

- Exploring costs effort and its result is uncertain. The chance of success depends on the effort spent and on the agent's skill and knowledge.
- An information source has an actual value and an apparent value. The two can differ in either direction.
- Whether an agent explores a source, and how much effort they give it, depends on their skill and knowledge, what they are working on, their own and the organisation's willingness to explore, and the source's subject, age, number of readers and perceived importance.
- Less effort lowers the chance of finding what is there, but saves time when nothing is.
- A source's reading history can mislead: one that gave little to earlier readers may be avoided even if it is valuable.
- An agent may explore to solve something, to improve something, out of curiosity, or to open possibilities nobody has yet thought of. Exploration must not be limited to known problems.
- How much time an organisation gives to exploring, as against direct work, affects how much it improves. Societies and organisations differ widely in this, and it is a focus of the model.

Open:

- **Apparent value:** how it works. A separate visible description on each information source was proposed and not accepted as it stands. Proposed instead, for sources of both kinds: actual value is what a source really gives for what is put in, and apparent value is what an agent expects it to give.
- **Standing of an origin:** how to signal the standing of where stored information comes from. Reader counts alone would wrongly discourage reading new work from reputable origins. Proposed: reputation belongs to the origin and is known before reading; reader count and yield belong to the item.
- **Push:** what directs an agent's exploring. Proposed: a need, a wish to improve something, or curiosity, coming from the agent, the role or the organisation.

## Discovery

Current view:

- Progress is not only gradual. Research can run for a long time with no effect, then produce a finding that changes a great deal at once.
- A finding may improve a tool, improve an agent, speed up research, or change nothing.
- Reading may give part of what is needed for a solution, or nearly the whole of it.
- Recognising a solution requires skill, knowledge and awareness of where it applies. An agent who does not know what is happening in the organisation can read a solution and not see it.
- Working on something makes finding its solution faster. An agent far from it is very unlikely to find the solution, even with the right tools.
- Even with every requirement met, a solution can take a long time.
- Some large improvements are not visible beforehand as problems: nobody has the idea that things could be better until the possibility is found.

Open:

- **Gradual learning:** whether some learning raises output steadily, alongside discrete discoveries.
- **How discrete discoveries arise:** proposed: a discovery can need several pieces of information, with no effect until the last one arrives.
- **Closeness to the work:** the ways an agent can be related to the thing a discovery applies to, and how each affects discovery.

## Possibilities

Current view:

- "Problem" is not treated as an element. What exists is the possibility: something that could be made or done but has not been yet, with requirements and an effect once realised. It exists whether or not anyone knows of it.
- Possibilities are hidden from the agents but have to be defined in the model, by hand or by a rule. Large ones, such as the invention of AI or another major technology, can be decided by hand.
- Comparing structures on the same set of possibilities is fair, but by itself says nothing about the real world. The settings have to be varied over wide ranges to see how results change, and the settings that align with reality identified. This comes much later.
- Reality offers many cases to compare against: organisations differ by country and by period, so each is a separate history. Some assumptions are shared between them, but lessons can be extrapolated.
- The model answers how structures find and use possibilities, not which discoveries occur. The second is outside its scope, and the realism of the possibility settings is handled by varying them over ranges.

Open:

- **Defining possibilities:** how many to define, and how to set their requirements and effects, given that they strongly affect results and that the number grows with scale. Proposed: a few large ones written by hand and many small ones generated by a rule; the structures being compared face the same set. How to tie the settings to reality is unresolved.

## Not yet accounted for

So far the design looks at the organisation from the inside, with what is connected to it such as resources. The governing and outside lenses are underexplored and are being explored now. All of the following are important and need more thought.

Inside: choices made within the structure, by the agents and through the relations between them.

- **Structure itself:** relations between roles: who reports to whom, who may request what of whom, who communicates with whom, through which channels. Role holds tools but has no definition yet.
- **Learning by doing:** skill also rises through practice, not only through teaching and learning from sources.
- **Well-being and motivation:** well-being and equality criteria need a well-being attribute of the agent.
- **Cardinality:** whether a role can have several agents, and an agent several roles.

Governing: choices of the structure and the aims themselves, by whoever makes them.

- **Leadership that decides the structure:** not yet considered.
- **Making a plan, strategic decision making, structure and leadership:** how each of these happens and how it is modelled.
- **Changing the structure:** hiring, dismissing, moving an agent between roles, creating a role. Someone chooses these, so they are actions whose outcomes fall on the structure.
- **The organisation as a whole:** its willingness to explore and its aim need a home, since only agents choose: shared information, a leadership role or standing rules.

Outside: what nobody in the organisation chooses: what it exchanges with, and what happens to it.

- **How resources enter and leave:** money as a criterion implies selling and buying, so there must be an outside to exchange with, or resources come only from sources and go nowhere.
- **The scenario:** the bundle an organisation is run under (initial state, sources, possibilities, events) has no name, although several points depend on it.
- **Competitors, the environment, threats, events and shocks:** not yet considered.

## Raised, not yet discussed

- Stored information that is wrong, not merely empty.
- Teaching: knowledge passed directly from one agent to another.
- Obligations: what is owed to others.
