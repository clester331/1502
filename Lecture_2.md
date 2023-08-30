# Deterministic Finite Automaton (DFA)
* DFA has an input and an output
  * An input would be a string
  * An output can be one of two things: **Accept** or **Reject**
    * If the state ends on **q0, we reject**
    * If the state ends on **q1, we accept**
   
## DFA Language
* A language is a set of strings
* A language of DFA A **(L(A))** is the set of all strings accepted by DFA A
* DFAs can have unreachable states, and can have more than 1

## DFA Formal Descriptions
* Formal Description of a DFA: (Q, Σ, δ, q, F), where:
  * Q is a non-empty finite set of **states**
  * Σ is a non-empty finite set of **symbols**
  * δ: Q x Σ -> Q is a transition function
  * q ∈ Q is the start state
  * F ⊆ Q is the set of accept states
