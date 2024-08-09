Markov Decision Process

In real world the agent will not always follow the plan

Deterministic serach :
The agent will 100% follows the plan

Non-Deterministic search :
The agent will 10% go right, 10% left...

Markov Process :
conditional probability distribution of future states of process depends only on present state, not on sequence of events that preceeds it
Doesnt matter how agent came there; only depends on present state

Markov Decision Process :
Mathematical framework for modellinfg decision making in situations where outcomes are partly random and under control of decision maker

v(s) = max(r(s,a) + $v(s')) 
0.10*V(s1') + 0.80*V(s2') + 0.10*V(s3')

so, v(s) = max( r(s,a) + $ sum{ P(s,a.s')*v(s') } ) 
