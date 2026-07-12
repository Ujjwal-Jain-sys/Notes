# Essence Of Linear Algebra 3
---
## Linear Transformation

>***Keep Two things in mind***

1. **Every line After transformation must remain a straight line.**
2. **origin must not change.**
**Note** ~ _Grid line remains parallel and evenly spaced_
### How would we describe these Transformation numerically?

$$\boxed{\vec{v} = -1\hat{i} + 2\hat{j}}$$
##### **AFTER TRANSFORMATION :**
$$\boxed{\text{Transformed} \; \vec{v} = -1(\text{Transformed} \; \hat{i}) + 2(\text{Transformed} \; \hat{j})}$$
![[Pasted image 20260712184821.png]]

Here we can see that $\hat{i}$ -> $\boxed{\begin{matrix}1\\-2\end{matrix}}$ And $\hat{j}$ -> $\boxed{\begin{matrix}3\\0\end{matrix}}$ :

And if we remember         $\vec{v} = -1\hat{i} + 2\hat{j}$ 
<div align = "center">⬇️</div>
And after transformation : $\vec{v} = -1 \, \boxed{\begin{matrix}1\\-2\end{matrix}} + 2 \, \boxed{\begin{matrix}3\\0\end{matrix}} =$ $\boxed{\begin{matrix}1x + 3y\\-2x + 0y\end{matrix}}$ 

---
## Matrices
>Matrix is the method of writing about these linear transformations and numbers in it tells about the coordinates after the transformation
>Meanwhile ![[Pasted image 20260712193335.png]]
>Matrix-vector multiplication is just a way to compute what that  transformation does to a given vector.
![[Pasted image 20260712192553.png]]

>_Note :-_ If the transformed $\hat{i}$ and $\hat{j}$ comes out to be linearly dependent.
>_Meaning-_ one can be written as scalar multiple of other.

---
