# Chapter 3 - Part 2 Hints

These are hints to solving homework questions based on questions I've received from office hours and the like. My suggestion is that **you attempt the problems _before_ you seek out these hints!** If these hints still aren't helping you, then you should reach out to your instructor for help.

## Problem 3.73
This one is tricky since it has no independent sources.

<details>
<summary>Hint 1 - Finding Thevenin voltage</summary>

You'll want to find $V_{Th}$ by finding the open circuit voltage across nodes _a_ and _b_. Since there are no independent sources, $V_{Th}=0$. This means that your Thevenin equivalent circuit only contains a resistor, and no power source.
</details>

<details>
<summary>Hint 2 - Finding Thevenin resistance</summary>

In this scenario, when we short nodes _a_ and _b_, we get $i_{sc}=0$. This isn't helpful since we still won't be able to calculate the Thevenin resistance.

Instead, you'll want to attach a known voltage source, which I'll call $V_k$, across nodes _a_ and _b_. From here, you can calculate how much current it delivers to the circuit, $i_k$. If we model the circuit as a single resistor $R_{Th}$, we can then find the resistance value by calculating:

$$R_{Th}=\frac{V_k}{i_k}$$
</details>
