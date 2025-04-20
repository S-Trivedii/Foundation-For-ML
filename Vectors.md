### 📌 What is a Vector?

A vector is something that has both direction and size (we call the size "magnitude").

You can think of a vector like an arrow:

- The arrow starts somewhere.
- It points in a direction.
- It has a certain length (how long the arrow is).

### 🟢 Example:

Let's say you walk:

- 3 steps east and
- 2 steps north

We can represent that movement as a vector:

```bash
v = (3, 2)
```

This tells us:

- Go 3 units right (east)
- Then 2 units up (north)

### ✳️ Components of a Vector

The numbers inside the vector like (3, 2) are called its components:

- 3 → movement in the x-direction (horizontal)
- 2 → movement in the y-direction (vertical)

### 📏 What is Magnitude (Length) of a Vector?

The magnitude (or length) of a vector is "how long the arrow is."

Use the Pythagorean theorem to calculate it:

For vector v = (a, b),
Magnitude = √(a² + b²)

#### Example:

For v = (3, 4):
Magnitude = √(3² + 4²) = √(9 + 16) = √25 = 5

### 🧭 What is Direction?

The direction of a vector tells you where the arrow points.
Example: (1, 0) → points directly right
(0, 1) → points directly up
(-1, 0) → points left

You can find the angle of a vector (if needed) using trigonometry, but for now just understand it gives you the "which way" info.

### 🎯 What is a Unit Vector?

A unit vector is a vector with length = 1.
It just shows direction, not size.

#### Example:

- (1, 0) is a unit vector pointing right
- (0, 1) is a unit vector pointing up

You can turn any vector into a unit vector by dividing it by its magnitude.

#### 🧱 What is a Basis Vector?

Think of basis vectors as Lego blocks — you can build any other vector using them.

In 2D:

- e₁ = (1, 0) → points right
- e₂ = (0, 1) → points up

Any vector like (3, 2) can be made like this:

(3 × e₁) + (2 × e₂)
= 3 × (1, 0) + 2 × (0, 1)
= (3, 0) + (0, 2) = (3, 2)

So, (1, 0) and (0, 1) are basis vectors of 2D space.

### 🔄 What is Linear Combination?

A linear combination means you're just adding and scaling vectors.

Example: If v = 2 × (1, 0) + 3 × (0, 1), then:
v = (2, 3)

You’re using the basis vectors to build new vectors.

### 🔗 What is Linear Independence?

Vectors are linearly independent if you can’t make one from the others using scaling and adding.

Example:

- (1, 0) and (0, 1) → linearly independent ✅
- (1, 0) and (2, 0) → not independent ❌ (because (2, 0) is just 2 × (1, 0))
