# Chapter 1 · Section 1.5
# Principle of Moments
### *"How does a 30 kg child balance a 90 kg man on a see-saw — and how do we calculate exactly where they must sit?"*

> 🧑‍🏫 **Professor Magnus** | 👧 **Mira** | 🧒 **Arjun** | 🐱 **Newton the Cat**

---

## 🎯 What You Will Learn

By the end of this section, you should be able to:

- State the principle of moments.
- Use $\sum M_{ACW} = \sum M_{CW}$ to solve lever and metre-rule problems.
- Decide whether a force produces clockwise or anticlockwise moment.
- Include the weight of a uniform ruler when required.
- Set up ICSE-style moment equations without mixing units.

---

## 🔮 The Mystery — The Unfair See-Saw

Professor Magnus draws a see-saw on the board. On the left: a large man, 90 kg. On the right: a small child, 30 kg.

> **"The man is three times heavier than the child.**
> **By common sense — the man's side should always slam down.**
> **But I promise you: there is a position where the child perfectly balances the man.**
> **The child does not need to get heavier. The man does not need to get lighter.**
> **Something else must change. What?"**

---

### 🧪 Socratic Discussion

**Arjun:** "The child moves farther away from the centre. That's obvious — I've done this on playgrounds."

**Professor Magnus:** "Good instinct. But *why* does distance help the child? What is the child gaining by moving farther?"

**Arjun:** "...More leverage?"

**Newton the Cat** 😼: "The child is cheating by using physics. I respect that."

**Mira:** "The child is farther from the pivot, so its force has a *larger perpendicular distance* — so a larger moment. The child increases its moment without increasing its weight."

**Professor Magnus:** "Exactly. The child cannot change its weight. But it can change the *distance* at which its weight acts. And moment = force × distance. Now — can we find the *exact* distance where they balance?"

---

## 🎯 Prediction Challenge

A 90 kg man sits 1 m from the pivot on the left. A 30 kg child is on the right.

**Where must the child sit to balance the man perfectly?**

- **A)** 1 m from the pivot (same as the man)
- **B)** 2 m from the pivot
- **C)** 3 m from the pivot
- **D)** 0.33 m from the pivot

> 🤔 *Use your intuition first. Then we'll verify with the principle.*

---

## 🖼️ Image Prompt 1

```
[IMAGE PROMPT]
Scene: A see-saw balanced on a triangular pivot (fulcrum) in the centre.
LEFT SIDE: Large figure (Man, 90 kg) sitting 1 m from pivot. Downward force arrow labeled "W₁ = 90 × g = 900 N". Horizontal distance marker "d₁ = 1 m". ACW/CW rotation arrow showing this side wants to go DOWN (CW from right perspective).
RIGHT SIDE: Small figure (Child, 30 kg) sitting 3 m from pivot. Downward force arrow "W₂ = 30 × g = 300 N". Horizontal distance marker "d₂ = 3 m". Rotation arrow showing this side ALSO wants to go down.
CENTRE: Pivot with golden star. Balance scale indicator showing LEVEL.
CALLOUT BOXES:
  Left: "CW Moment = 900 × 1 = 900 N·m"
  Right: "ACW Moment = 300 × 3 = 900 N·m"
  Bottom: "ACW Moment = CW Moment → BALANCED"
Characters: Arjun measuring with a tape on one side. Mira writing calculations on the other.
Style: Clear educational diagram. Blueprint grid background. Bold force arrows. Distance markers in contrasting color. 2:3 vertical ratio. Print-friendly.
```

---

## 👁️ Observation

- The man's moment: $900 \times 1 = 900$ N·m (clockwise)
- The child's moment at 3 m: $300 \times 3 = 900$ N·m (anticlockwise)
- They are **equal** → the see-saw is perfectly balanced
- The child sits **3 times farther** because the man is **3 times heavier**

The Principle of Moments is right there in the numbers.

---

## 🧠 Deep Explanation — Feynman Style

### Step 1: The Battle of Moments

Imagine a pivoted beam with forces on both sides. Each force "tries" to rotate the beam — some clockwise, some anticlockwise.

For the beam to remain still (rotational equilibrium), these competing rotations must cancel each other out perfectly.

This is not magic — it is the direct consequence of Newton's second law applied to rotation:

$$\text{If } \sum \tau_{net} = 0, \text{ then angular acceleration} = 0$$

Which means: no rotation. The beam stays put.

---

### Step 2: Stating the Principle

The **Principle of Moments** is simply the second condition of equilibrium written as a practical rule:

> **When a body is in rotational equilibrium, the sum of all anticlockwise moments about any point equals the sum of all clockwise moments about that same point.**

$$\boxed{\sum \tau_{ACW} = \sum \tau_{CW}}$$

This is the tool you use every time you solve a see-saw or lever problem.

---

### Step 3: The 5-Step Method for Every Numerical

**Arjun:** "I keep making errors in these calculations. I get confused about which side is CW and which is ACW."

**Professor Magnus:** "Then follow this method every time. Without exception."

---

#### 🔧 The No-Panic 5-Step Method

| Step | Action |
|:---|:---|
| **1. Draw the beam** | Sketch the lever/ruler with all forces marked as downward arrows |
| **2. Mark the pivot** | Put a triangle (△) at the pivot point — this is your reference |
| **3. Calculate distances** | Distance = position of force minus position of pivot (always positive) |
| **4. Assign directions** | Force to the LEFT of pivot → ACW. Force to the RIGHT → CW. (If pivot is not at center, this changes — always check visually.) |
| **5. Apply the principle** | $\sum ACW = \sum CW$. Solve for the unknown. |

---

### Step 4: The Weight of the Ruler — The Hidden Force

**Newton the Cat** 😼: "In every problem I've seen, the ruler is treated as 'massless.' But rulers have weight! My favourite ruler weighs at least 50 grams!"

**Professor Magnus:** "Newton is absolutely right. Real beams and rulers have weight. This weight acts at the beam's **centre of gravity** — which for a uniform beam is at its geometric centre (midpoint)."

**Mira:** "So for a uniform 1 m rule, the weight acts at 50 cm — its own centre. And that weight creates its own moment about the pivot?"

**Professor Magnus:** "Exactly. And if the pivot is NOT at the 50 cm mark, the ruler's own weight creates a moment that you must include in your calculation."

**Rule:** For a uniform beam of mass $m$, treat it as a single downward force $mg$ acting at the **midpoint** of the beam.

---

### Step 5: Worked Example — Step by Step

**Problem:** A uniform metre rule (mass = 100 g) is pivoted at the 30 cm mark. A 200 g weight hangs at the 10 cm mark. Find the weight needed at the 80 cm mark for equilibrium.

**Step 1: Draw the beam.**

```
0cm     10cm    30cm(pivot)         80cm    100cm
|-------|-------|------|------------|-------|
      200g    △(pivot)             ?g    (ruler CG = 50cm)
```

**Step 2: Mark the pivot at 30 cm.**

**Step 3: Calculate perpendicular distances.**

- 200 g weight at 10 cm → distance from pivot = $30 - 10 = 20$ cm (LEFT of pivot → **ACW**)
- Ruler's own weight at 50 cm → distance from pivot = $50 - 30 = 20$ cm (RIGHT of pivot → **CW**)
- Unknown weight at 80 cm → distance from pivot = $80 - 30 = 50$ cm (RIGHT of pivot → **CW**)

**Step 4: Assign directions and calculate moments.**

| Force | Weight | Distance | Moment | Direction |
|:---|:---:|:---:|:---:|:---:|
| Hanging weight | 200 gf | 20 cm | 4000 gf·cm | ACW |
| Ruler's own weight | 100 gf | 20 cm | 2000 gf·cm | CW |
| Unknown weight | $W$ gf | 50 cm | $50W$ gf·cm | CW |

**Step 5: Apply the Principle of Moments.**

$$\sum ACW = \sum CW$$
$$4000 = 2000 + 50W$$
$$50W = 2000$$
$$W = 40 \text{ gf}$$

**Answer:** A 40 g weight must hang at the 80 cm mark.

---

## 🖼️ Image Prompt 2

```
[IMAGE PROMPT]
Scene: A metre rule balanced on a pivot at 30 cm. Shown as a precise scientific diagram with annotations.
- 200g weight at 10cm. Red downward arrow. Distance "20cm" marked from pivot (ACW).
- Ruler's own weight: single downward blue arrow at 50cm (midpoint). Distance "20cm" from pivot (CW).
- Unknown weight W at 80cm. Green downward arrow. Distance "50cm" from pivot (CW).
Pivot shown as a triangle at 30cm with the label "△ Pivot".
Below the beam: two moment columns — LEFT column "ACW: 200 × 20 = 4000 gf·cm", RIGHT column "CW: (100×20) + (W×50) = 2000 + 50W". Balance equation below.
Characters: Arjun following the 5-step checklist. Newton the Cat double-checking whether the ruler has weight.
Style: Technical blueprint diagram. Dark background with white/colored labels. Precise distance markers. 2:3 vertical ratio. Print-friendly.
```

---

## 👁️ Observation — After Image 2

- Every force, including the ruler's own weight, gets its own row in the calculation.
- Forces left of pivot = ACW. Forces right of pivot = CW.
- The pivot position is arbitrary — any point can be chosen, but choosing the pivot point itself eliminates the reaction force of the support (which has zero distance → zero moment).

---

## 🔍 Critical Thinking Corner

| Scenario | Effect on Principle of Moments |
|:---|:---|
| You choose a different reference point (not the pivot) | The reaction force at the pivot NOW has a moment — but the equation still holds |
| The ruler is non-uniform (denser on one side) | Its CG is NOT at the midpoint — must find it separately |
| A force acts directly at the pivot | Its perpendicular distance = 0 → moment = 0 → ignored in calculation |
| Multiple forces on the same side | Each creates its own moment — sum them all on that side |
| A force is applied at an angle | Use only the component perpendicular to the beam, OR use the perpendicular distance from pivot to the force's line of action |

---

## 🖼️ Image Prompt 3 — Verification Experiment

```
[IMAGE PROMPT]
Scene: A laboratory setup for verifying the Principle of Moments.
Equipment: A uniform metre rule. A sharp-edged support (pivot) at the 50cm mark. Multiple weights on both sides hanging from thread loops.
LEFT SIDE: Two weights — 50g at 20cm and 100g at 40cm. Distances from pivot labeled.
RIGHT SIDE: One weight — unknown at some mark. Distance labeled.
CALLOUT: Step-by-step process — 1) Note positions, 2) Calculate each moment, 3) Sum ACW moments, 4) Sum CW moments, 5) Verify equality.
Observation table shown in bottom corner with columns: Weight | Position | Distance from Pivot | Moment | Direction.
Characters: Mira writing in observation table. Professor Magnus watching.
Style: Laboratory illustration. Realistic scientific equipment. Clean labeling. 2:3 vertical ratio.
```

---

## 📘 Formal Conclusion — ICSE Board Ready

### ✅ Principle of Moments (Statement)

> **If a body is in rotational equilibrium, the sum of the anticlockwise moments about any point is equal to the sum of the clockwise moments about that same point.**

$$\boxed{\sum \tau_{ACW} = \sum \tau_{CW}}$$

---

### ✅ Verification of the Principle of Moments

**Apparatus:** Uniform metre rule, sharp-edged support (pivot), known weights, thread.

**Procedure:**
1. Balance the metre rule on the support at its centre (50 cm mark). Verify it is horizontal.
2. Hang known weights at various positions on both sides of the pivot.
3. Adjust positions until the rule is again perfectly horizontal.
4. For each weight, measure: (a) the weight in gf, (b) the perpendicular distance from the pivot in cm.
5. Calculate the moment of each weight (weight × distance).
6. Sum all ACW moments. Sum all CW moments.
7. Observe that $\sum \tau_{ACW} = \sum \tau_{CW}$ (within experimental error).

**Observation Table Format:**

| Weight | Position (cm) | Distance from Pivot (cm) | Moment (gf·cm) | Direction |
|:---:|:---:|:---:|:---:|:---:|
| 50 gf | 20 cm | 30 cm | 1500 | ACW |
| 100 gf | 40 cm | 10 cm | 1000 | ACW |
| 150 gf | 70 cm | 20 cm | 3000 | CW |

**Conclusion:** $\sum ACW = 2500$ gf·cm, $\sum CW = 3000$ gf·cm → adjust until equal → Principle verified.

---

### ✅ Units Used in ICSE Problems

| Quantity | SI Unit | ICSE Practical Unit |
|:---|:---:|:---:|
| Force (Weight) | Newton (N) | gram-force (gf) or kilogram-force (kgf) |
| Distance | metre (m) | centimetre (cm) |
| Moment | N·m | gf·cm or kgf·m |

> **Note:** In ICSE practicals, `gf·cm` is acceptable. In theory questions asking for SI units, convert to N·m.
> $1 \text{ gf} = 9.8 \times 10^{-3} \text{ N}$ (or use $g = 10 \text{ m/s}^2$ for simplification unless told otherwise)

---

## ⚠️ Newton Cat's Exam Traps

> 🐱 *Newton the Cat tried to balance a ruler by guessing. He got it wrong. Five times.*

**Trap 1 — "Forgetting the weight of the ruler itself"**
> ❌ Unless told "the ruler is massless/negligible," always include the ruler's weight acting at its midpoint (geometric centre for a uniform ruler). Forgetting this = wrong answer.

**Trap 2 — "Distance = position number on the ruler"**
> ❌ Distance for moments = distance **from the pivot** to the force, not the absolute position on the ruler. Always subtract the pivot position first.

**Trap 3 — "Forces on the left are always ACW"**
> ❌ Only if the pivot is to their right. The direction (CW or ACW) depends on which side of the pivot the force acts. **Always draw the beam and visually check.**

**Trap 4 — "The support reaction at the pivot doesn't matter"**
> ✅ TRUE when you take moments about the pivot itself (reaction has zero distance, zero moment). But if you take moments about a different point, the reaction force must be included.

**Trap 5 — "gf·cm and N·m can be mixed in the same calculation"**
> ❌ **Never mix units.** Convert everything to one consistent unit system before calculating. If the question gives gf and cm, work entirely in gf·cm.

---

## 🧩 Mini Challenge

### 🧠 Conceptual
> A uniform wooden plank of mass 4 kg and length 2 m is pivoted at its centre. Two children sit on it — one of mass 30 kg at 0.8 m from the pivot, another of mass 20 kg at $x$ metres from the pivot on the other side.
> **(a)** Does the plank's own weight affect the calculation? Explain.
> **(b)** Calculate $x$ for equilibrium.
> **(c)** If the 20 kg child moves 10 cm closer to the pivot, which side goes down?

### 🔢 Numerical
> A uniform metre rule of mass 80 g is pivoted at the 20 cm mark. The following weights are placed: 60 g at the 5 cm mark, 100 g at the 50 cm mark, and an unknown mass $m$ at the 0 cm mark.
> **(a)** Find the moment of each force (including ruler's weight) about the pivot.
> **(b)** Identify the direction (CW/ACW) of each moment.
> **(c)** Find $m$ for equilibrium.

### 🌍 Application
> A seesaw in a playground is 4 m long and pivoted at its centre. Child A (mass 25 kg) sits 1.6 m from the centre. Child B (mass 40 kg) sits on the other side.
> **(a)** Where must Child B sit for the seesaw to balance?
> **(b)** If Child B moves to the end of the seesaw (2 m from pivot), what weight must Child A have to still balance?
> **(c)** A third child (30 kg) sits beside Child A at the same position. Now where must Child B sit?

---

*→ In **Section 1.6**, we will find the exact point in any object where all its weight appears to act — the mysterious **Centre of Gravity** — and understand why it can exist in empty space.*

---
