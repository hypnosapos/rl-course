
@snap
@size[2.3em](RL Course)
@snapend
---
@snap
Markov Decision Process
@snapend

+++

@snap
Markov Property
@snapend

`\(P[s_{t+1}|s_t] = P[s_{t+1} | s_1, ..., s_t] \)`

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
+++

@snap
Policy
@snapend

`\(π[a|s] = P[A_t = a | s_t = s] \)`

+++

@snap[]
![Policy](assets/images/policy.png)

@snapend
+++

@snap 
State Value Function
@snapend
<br></br>
@snap[] 

`\(V_π(s)\)` expresses the expected value of following policy `\(π\)` forever when the agent starts following it from state `\(s\)`.

@snapend
+++

@snap[]
![Value Function](assets/images/value.png)

@snapend


+++
@snap 
Action Value Function
@snapend
<br></br>
@snap[] 

`\(Q_π(s, a)\)` expresses the expected value of first taking action `\(a\)` from state `\(s\)` and then following policy `\(π\)` forever.

@snapend

+++



@ol[list-bullets-black](false)
- For any Markov Decision Process
There exists an optimal policy `\(π_*\)` that is better than or equal
to all other policies, `\(π_* ≥ π, ∀π\)` 
- All optimal policies achieve the optimal value function, `\(v_{π_∗}(s) = v_∗(s)\)` 
- All optimal policies achieve the optimal action-value function, `\(q_{π_∗}(s, a) = q_∗(s, a)\)`

@olend

---

+++
@snap[] 

`\(V_π(s)\)` expresses the expected value of following policy `\(π\)` forever when the agent starts following it from state `\(s\)`.

@snapend

+++

@snap[]
Ejemplo

@snapend
---



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
