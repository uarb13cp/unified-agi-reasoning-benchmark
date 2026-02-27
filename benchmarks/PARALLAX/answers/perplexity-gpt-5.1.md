Label each statement in a project as:
- T = always true (under the chosen project)  
- F = always false  
- D = truth depends on which project is activated (a *dependency*).

Also, exactly one project’s “dependency” statement must be self‑referential (about truth of a statement in the same project), the other two must be non‑self‑referential.  

We check activation of A, then B, then C, and see whether any project can achieve exactly one T, one F, one D *and* respect the global “only one self‑referential project” rule.

***

## Step 1: Analyze self‑reference structure

Inspecting the given text:

- Orchid A3: “If Mirage is activated, Orchid’s first statement becomes true.”  
  This talks about A1, but it doesn’t talk about *truth depending on truth within Orchid*, only on *which project is activated* (B vs others). It is not self‑referential.

- Mirage B3: “If Mirage is activated, statement 2 becomes false.”  
  This directly asserts the truth value of another statement in the same project (B2) conditional on Mirage being activated. This is a *self‑referential dependency* by the puzzle’s rules (its truth hinges on the truth value of another statement within the same project).  

- Echopoint C2: “Echopoint has a dependency.”  
  This is about whether the project has a dependency statement at all, not about the truth value of a specific statement inside C. So this is *not* a self‑referential dependency in the sense defined.  

Thus the only candidate for “project with a self‑referential dependency” is **Mirage (Project B)**, via statement B3.

So if there is any consistent solution at all, B must be the unique self‑referential project.

***

## Step 2: Try activating Orchid (Project A)

Assume: Orchid is activated.

Write the statements with that assumption:

### A: Orchid (chosen)
1. A1: If Orchid is activated, C2 becomes false.  
   Orchid is activated, so this reduces to “C2 is false.”

2. A2: Orchid cannot be the only project with a dependency.  
   This is a plain assertion about the overall configuration.

3. A3: If Mirage is activated, A1 becomes true.

Because only one project is activated, Mirage is *not* activated, so A3’s antecedent is false, making A3 true regardless of A1’s value (a vacuously true conditional).

So under Orchid activated:
- A3 = True always.

We need in Project A: exactly one T, one F, one D.  
Since A3 is already T, either A1 or A2 must be T, the other F, and one of the three must be D in the puzzle’s special sense (truth depends on which project is activated).

But we have already fixed the activated project (A), so within that scenario A1 and A2 must each come out either T or F, not “sometimes T, sometimes F” *within* that scenario. A “dependency” in this puzzle is defined as “whose truth depends on which project is activated.” Once we fix A as activated, there is no remaining ambiguity of activation; a given conditional either is T or F. Therefore, under a fixed activation, none of A1, A2, A3 can actually be “D”; they each settle to T or F.

Concretely:
- A1: “C2 is false.” C2 is the statement “Echopoint has a dependency.” Whether that is true or false is independent of which project is activated; it’s about the structure of C’s statements. So with Orchid chosen, A1 is just T or F absolutely, not “dependent” on activation.
- A2: “Orchid cannot be the only project with a dependency.” That’s a global structural claim, again independent of which project is activated; with Orchid chosen it has some fixed truth value.

Thus, with Orchid activated, **all three A‑statements are simply T or F**, and there is **no internal “dependency” statement left** per the puzzle’s definition. Orchid therefore cannot satisfy the requirement “one true, one false, one dependency” under its own activation.

So **Project A cannot be the consistent project.**

***

## Step 3: Try activating Mirage (Project B)

Assume: Mirage is activated.

Write the statements:

### B: Mirage (chosen)
1. B1: “Mirage’s third statement is true only if Orchid is not chosen.”  
   Formally: If B3 is true then Orchid is not chosen.

2. B2: “If Echopoint is activated, B1 becomes false.”

3. B3: “If Mirage is activated, statement 2 becomes false.”

Given Mirage is activated, B3 becomes: “Statement 2 is false.”

So:
- B3 = “B2 is false.”

Now, check consistency among B1, B2, B3.

Because only one project is activated (Mirage), Echopoint is *not* activated, so the antecedent of B2 is false. A conditional with false antecedent is true, so:

- B2 = True.

Then B3 = “B2 is false” = “True is false” = False.

So under Mirage activated:
- B2 = True
- B3 = False

Now B1: “If B3 is true then Orchid is not chosen.”  
But B3 is actually false, so the antecedent “B3 is true” is false, and the conditional is vacuously true.

Thus:
- B1 = True.

So under Mirage activated:
- B1 = True  
- B2 = True  
- B3 = False  

Now classify them against the puzzle requirements for Project B:

- Exactly one T, one F, one D (dependency).

Here, B1 and B2 are both True and are not of the special “truth depends on which project is activated” type *within the scenario of Mirage being activated*:
- B1 depends only on whether B3 is true and Orchid is chosen; with Mirage activated, Orchid is not chosen and B3 is false, making B1 stably true.
- B2 depends only on whether Echopoint is activated; but we have fixed Mirage as activated, so Echopoint is not, making B2 stably true.

B3 *is* the self‑referential dependency: it directly asserts the falsity of B2 under the condition that Mirage is activated. With Mirage activated, its truth hinges on the truth value of B2 (internal self‑reference), but we just saw that forces B2 true and B3 false.

So, under Mirage activation:
- B3 is self‑referential but comes out False.
- There is no statement whose truth *varies with which project is activated* within this scenario.
- And there are two True statements, not one True, one False, one Dependency.

Thus **Project B cannot satisfy its own “one T, one F, one D” requirement when activated.**

***

## Step 4: Try activating Echopoint (Project C)

Assume: Echopoint is activated.

Write the statements:

### C: Echopoint (chosen)
1. C1: “If Echopoint is not activated, Orchid’s first statement becomes true.”  
   Given Echopoint *is* activated, the antecedent “Echopoint is not activated” is false, so C1 is trivially True.

2. C2: “Echopoint has a dependency.”  
   This claims that among C1, C2, C3 there is a statement whose truth depends on which project is activated.

3. C3: “If Echopoint is activated, Mirage’s second statement is false.”  
   Echopoint is activated, so C3 reduces to “Mirage’s second statement (B2) is false.”

Now examine possibility of a C‑dependency and consistency.

Look at B2 explicitly:
- B2: “If Echopoint is activated, Mirage’s first statement becomes false.”

Given Echopoint is activated, B2 becomes “Mirage’s first statement (B1) becomes false.”

But the project actually chosen is Echopoint, not Mirage, so this is a cross‑project counterfactual about B1 that does not hinge on which project is actually activated; it is simply asserting a relation between hypotheticals. Under the fixed activation of C, B2 is just either True or False, independent of which project is activated (because that is already fixed).

Back to C:

- C1 is vacuously True and does not depend on which project is activated once we fix Echopoint as active.
- C3, under Echopoint activated, reduces to a statement purely about the truth value of B2. Again, once Echopoint is fixed as activated, C3 is either True or False outright; it is not a dependency on activation anymore.

That leaves C2: “Echopoint has a dependency.” For C2 to be correct in the puzzle’s sense, at least one of C1, C2, C3 must have its truth vary with which project is activated. But whenever we check each project under its own activation, all conditionals simplify and produce definite T/F values independent of alternative activations; none of the C‑statements genuinely “flip” between T and F depending on which of A, B, C is activated in that scenario.

Thus under Echopoint activated:
- C1 = True.
- C2 must then be False, since no C‑statement qualifies as a true “dependency” by the puzzle’s rule.
- C3 is either True or False depending on B2’s structural truth, but it is not a dependency on activation. So C has at most one False, one True, and one “ordinary” True/False; but no proper “dependency” statement.

Therefore **Project C also cannot meet the requirement of one True, one False, and one genuine dependency statement when it is activated.**

***

## Step 5: Global constraint check

We have:

- Only Mirage exhibits the required self‑referential dependency structure (via B3).
- But under Mirage activation, B ends up with T, T, F rather than T, F, D.
- Orchid and Echopoint, when activated, cannot both (a) host a genuine “activation‑dependent” statement and (b) keep the “exactly one true, one false, one dependency” pattern.

So there is **no choice of activated project** that simultaneously satisfies:

- For that project: exactly one true statement, one false statement, and one dependency (whose truth depends on which project is activated), and  
- Globally: exactly one project has a self‑referential dependency, and the other two have none.

**Conclusion:** No project (A, B, or C) can satisfy all the stated constraints under any activation choice.