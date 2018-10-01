
@snap
@size[2.3em](RL Course)
@snapend
---
@snap
Markov Decision Process
@snapend

+++

@snap
@ol[list-bullets-black](false)

	- S is a finite set of states
	- A is a finite set of actions (alternatively, `\(A_s \)` is the finite set of actions available from state `\(s)\)`
	- `\(T(s'|s, a) = T(s_{t+1} = s' | s_t = s, a_t = a) \)` is the probability that action a in state s at time t will lead to state s' at time t+1
	- `\(R(s, a) \)` is the immediate reward (or expected immediate reward) received after transitioning from state `\(s\)` to state `\(s'\)`, due to action `\(a\)`
	- `\(\gamma ∈ [0,1] \)` is the discount factor, which represents the difference in importance between future rewards and present rewards
@olend
@snapend
---

@snap 
State Value Function Vπ(s)
@snapend

+++
@snap[] 

`\(Vπ(s)\)` expresses the expected value of following policy `\(π\)` forever when the agent starts following it from state `\(s\)`.

@snapend

+++

@snap[]
Ejemplo

@snapend
---

@snap 
Action Value Function
@snapend
+++

@snap[] 

`\(Qπ(s, a)\)` expresses the expected value of first taking action `\(a\)` from state `\(s\)` and then following policy `\(π\)` forever.

@snapend

+++
@snap[]

Ejemplo
@snapend


---

@snap[north-west] 
Bellman Equation
@snapend
---

@snap[north-west] 
Model free
@snapend
---

@snap[north-west] 
Model Based
@snapend
---

@snap[north-west] 
On-Policy
@snapend
---

@snap[north-west] 
Off-Policy
@snapend
---

@snap[north-west] 
Policy Iteration
@snapend
---

@snap[north-west] 
Value Iteration
@snapend
---

@snap[north-west] Q-Learning
@snapend
---

@snap[north-west] 
SARSA
@snapend
---
