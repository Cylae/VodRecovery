## 2025-12-31 - [Massive Loop Optimization]
**Learning:** Hoisting invariant calculations (especially expensive ones like hashing and datetime parsing) out of nested loops can lead to order-of-magnitude speedups (97x in this case).
**Action:** Always check loop bodies for calculations that depend only on outer loop variables or constants.
