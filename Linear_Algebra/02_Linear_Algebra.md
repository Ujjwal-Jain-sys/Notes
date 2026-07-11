# Essence Of Linear Algebra-2
---
**Date -** July 11
**Day-1**
- [x] Master vector addition and scalar multiplication geometrically - **(Maths)** ✅ 2026-07-11
- [ ] Implement matrix representation using nested lists and iterate through them using nested loops - **(python)**
- [x] Configure your Git globally, set up SSH keys for GitHub, and create your first local repository. - **(Tools)** ✅ 2026-07-11
- [ ] Create a local directory named py-engine-sandbox. Initialize Git, create a README.md, make your first commit, and push it to a new private GitHub repository. - **(Project)**
---
## Basis Vectors

$\hat{\imath}$ and $\hat{\jmath}$ are the "basis vectors" of xy coordinate system.

### **Technical definition of basis :**
>The basis of a vector space is a set of linearly independent vectors that span the full space.
---
## Linear Combination

### What is Linear Combination?
>Combining two different vectors.

When we scale two vectors - $\vec{a}$ & $\vec{b}$ And add them, it's called **"Linear Combination of  $\vec{a}$ & $\vec{b}$ "**
**Vector Example :**
$$\boxed{\vec{r} = m\vec{a} + n\vec{b}}$$
### Three Cases of Linear Combination of two vectors in 2-d:
1. **Unit vector of $\vec{a}$ & $\vec{b}$ are equal :** In this Case, Their combination will touch every point in a straight line.
2. **If Both $\vec{a}$ & $\vec{b}$ are null vectors :** In this Case, We will be stuck at origin as resultant will always be a null vector.
3. **If Both $\vec{a}$ & $\vec{b}$ are unequal :** In this Case, We can access every single point in the 2-d plane of those vectors. _(Important)_
---
## Span of vectors
>Set of All Linear Combination.

### What is Span?

The "*Span*" of  $\vec{a}$ & $\vec{b}$ is the set of all their linear combinations.

We Can Say,

`Span ---> How Many points we can cover by using these vectors.`

---
## Vectors Vs. Points

Using points to represent vectors is pretty common when we talk about Cases like:-
1. Representing 2 different vectors(none of them should be null) in a 2-d plane. -----> whole 2-d plane
2. Representing 3 different vectors(none of them should be null) in a 3-d plane. -----> whole 3-d plane
3. Representing 3 different vectors in a 3-d plane but two of them have same unit vector. -----> an infinite sheet.

---
## Linearly Dependent And Independent

_Illustration : -_ If we take three vectors  $\vec{u}$ ,  $\vec{v}$ and  $\vec{w}$ and they all lie in same plane. And if : $$\boxed{\vec{u} = a\vec{v} + b\vec{w}}$$
is defined (For some values of a and b) then we say that vector  $\vec{u}$ is linearly dependent on other two vectors.
**Example -** Consider three vectors in three‑dimensional space, with two lying in the same plane. In this case, one vector can be expressed as a scalar sum of the other two.

_Meanwhile :_ 
If three vectors each lie in a different plane, they are linearly independent.

---
