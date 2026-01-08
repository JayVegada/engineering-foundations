# Day 1 — Pointer Fundamentals (Notes)

1. **What is the value of a variable?**  
   The data stored inside a memory location. Example: if `int x = 10;`, the value is `10`.

2. **What is the address of a variable?**  
   The memory location (locker number) where the value is stored. Obtained using `&x`.

3. **What does `ptr` store?**  
   A pointer stores the **address** of another variable, not the value.

4. **What does `*ptr` give you?**  
   It dereferences the pointer and returns the **value stored at that address**.

5. **Why are `&x` and `ptr` equal?**  
   Because `ptr` was assigned `&x`, meaning the pointer stores the address of `x`. So both point to the same memory location.
