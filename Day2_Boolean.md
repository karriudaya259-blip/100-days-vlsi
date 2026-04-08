# Day 2 – Boolean Algebra & DeMorgan's Laws

## 📖 Theory Covered

### 9 Boolean Laws
| Law | AND Form (·) | OR Form (+) |
|-----|--------------|-------------|
| Annulment | X · 0 = 0 | X + 1 = 1 |
| Identity | X · 1 = X | X + 0 = X |
| Idempotent | X · X = X | X + X = X |
| Complement | X · X' = 0 | X + X' = 1 |
| Involution | (X')' = X | (X')' = X |
| Commutative | X · Y = Y · X | X + Y = Y + X |
| Associative | X · (Y · Z) = (X · Y) · Z | X + (Y + Z) = (X + Y) + Z |
| Distributive | X · (Y + Z) = X·Y + X·Z | X + (Y·Z) = (X+Y)·(X+Z) |
| Absorption | X · (X + Y) = X | X + (X·Y) = X |

### DeMorgan's Theorems
| Theorem | Equation |
|---------|----------|
| Theorem 1 | (X · Y)' = X' + Y' |
| Theorem 2 | (X + Y)' = X' · Y' |

**Golden Rule:** *Break the line, change the sign.*

---

## 📊 Problems Solved (15 Total)

### Task A: Boolean Simplification (10 Problems)

| # | Original Expression | Simplified | Laws Used |
|---|---------------------|------------|-----------|
| 1 | A + AB | A | Absorption |
| 2 | A(A + B) | A | Absorption |
| 3 | AB + AB' | A | Distributive + Complement |
| 4 | A + A'B | A + B | Distributive + Complement |
| 5 | (A + B)(A + C) | A + BC | Distributive |
| 6 | A(A' + B) | AB | Distributive + Complement |
| 7 | A'B'C + A'BC + AB'C + ABC' | AB' + A'C + BC' | (Solved step by step) |
| 8 | XY + X'Z + YZ | XY + X'Z | Consensus Theorem |
| 9 | (X + Y)(X' + Z)(Y + Z) | (X + Y)(X' + Z) | Consensus Theorem |
| 10 | ABC + ABC' + AB'C + A'BC | AB + AC + BC | Distributive + Absorption |

### Task B: DeMorgan's Applications (5 Problems)

| # | Original | After DeMorgan |
|---|----------|----------------|
| 1 | (A + B)' | A' · B' |
| 2 | (AB)' | A' + B' |
| 3 | (A + B + C)' | A' · B' · C' |
| 4 | (ABC)' | A' + B' + C' |
| 5 | (A(B + C))' | A' + (B' · C') |

**Challenge:** (A'B + CD')' → (A + B')(C' + D)

---

## 💡 Key Takeaways

1. **Boolean algebra** is the mathematical foundation of all digital circuits.
2. **DeMorgan's theorems** allow conversion between NAND/NOR gates — essential for CMOS design.
3. **Absorption and Consensus** are powerful for minimizing logic expressions.
4. Every simplification reduces transistors → less power, smaller chip area.

---

## 🔗 Proof of Work

- **Live table:** https://karriudaya259-blip.github.io/100-days-vlsi/
- **GitHub repo:** https://github.com/karriudaya259-blip/100-days-vlsi

---

## 🎯 Tomorrow's Target

Universal gates (NAND/NOR as building blocks for any logic circuit)

---

*End of Day 2*
