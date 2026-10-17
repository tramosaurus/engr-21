# Chapter 4 Hints

These are hints to solving homework questions based on questions I've received from office hours and the like. My suggestion is that **you attempt the problems _before_ you seek out these hints!** If these hints still aren't helping you, then you should reach out to your instructor for help.

## Problem 4.15
This one is a tough one, as it combines op amps (Chapter 4) with Thevenin circuits (Chapter 3). From Thevenin equivalent circuits, we know that maximum power transfer happens when $R_L$ is equal to $R_{Th}$ of the circuit.

<details>
<summary>Hint 1 - Calculating positive input voltage</summary>

The input to the positive node $v_p$ of the op amp can be calculated using voltage division. Since you're not given a value $v_s$, you can either make up a value (it won't matter), or you can practice keeping your expressions in terms of $v_s$. We also know that the positive and negative nodes are equal.
</details>

<details>
<summary>Hint 2 - Calculating negative input voltage</summary>

The input to the negative node $v_n$ of the op amp can be calculated using voltage division. Since you're not given a value $v_0$, you can write your expressions in terms of $v_0$. We also know that the positive and negative nodes are equal.
</details>

<details>
<summary>Hint 3 - Finding Thevenin voltage</summary>

You should start by trying to find $V_{Th}$. This occurs when you have open circuit -- in this case, it means that $R_L$ approaches infinity. In this configuration, $v_0 = v_L = V_{Th}$. Your answer will be in terms of $v_s$.
</details>

<details>
<summary>Hint 4 - Finding short circuit current</summary>

Lastly you can find $i_{sc}$. This occurs when you have a short circuit -- in this case, it menans that $R_L$ approaches $0$. For this problem, $v_L \rightarrow 0$, and you're looking for the current going through the $4 \text{ k}\Omega$ resistor.
</details>

<details>
<summary>Hint 5 - Calculating Thevenin resistance</summary>

Once you find $V_{Th}$ and $i_{sc}$, you can calculate $R_{Th}$.
If you find leaving everything in terms of $v_s$ a pain in the butt, you can also assign a random voltage to $v_s$. Since it cancels out in the end, the value you choose here won't matter.
</details>

