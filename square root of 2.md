## A Very Brief History of Part of Mathematics

Mathematicians may find this chapter trivial. Philosophers may find it intimidating. I can only plead necessity and promise that the positions will be reversed when I look at an overview of philosophy.

The history of mathematics obvious covers much more ground and many more topics than are relevant here.


### Greek Philosophy of Mathematics

The Pythagorean school was the great early Greek school of mathematics. Their underlying philosophy seems to have held that all measurements could be expressed in terms either of whole numbers[^1] or of ratios of whole numbers, that is to say, in terms of fractions. They thought in terms of geometry. While we still speak of the *square* of a number, the term *square* no longer has geometric overtones for us in this context, but it did for them. The famous Pythagorean Theorem for the sides of a right triangle, $a^2 + b^2 = c^2$, was for them a statement about the literal squares one could draw along each side of the triangle.

The idea that measurements could always be expressed in terms of whole numbers and ratios of whole numbers did not last long. Legend has it that the Pythagoreans drowned the man who proved that it was not true. Since the method of disproof will reoccur in this text, it's helpful to look at the proof now. It deals with the length of the hypotenuse of a right triangle whose length and height are both 1.

1. Apply the Pythagorean Theorem. The length and height, *a* and *b*, are both 1, giving $1^2 + 1^2 = c^2$, where c is the length of the hypotenuse. So
$1 + 1 = 2 = c^2$, and $2 = c^2$, so $c = \sqrt{2}$. Is the square root of 2 rational?
2. Assume that the square root of two is rational, the ratio of two whole numbers, like this: $i/j$, where $i$ and $j$ are whole numbers. The fraction should be expressed in lowest terms, so that there is no number other than 1 which evenly divides $i$ and $j$.
3. By assumption, $\frac{i}{j} = \sqrt{2}. Square both sides of the equation, giving $\frac{i^2}{j^2} = 2$.
4. Multiply both sides of the equation by $j^2$, giving $i^2 = 2j^2$.
5. $i^2$ is the square of a whole number. Because it is equal to $2j^2$, it must also be a multiple of two and therefore an even number. All even squares of integers are multiples of 4, so $i^2$ is a multiple of 4.
6. Since $i^2$ is a multiple of 4, $j^2$ must be a multiple of 2.
7. But this means that $i$ and $j$ are both multiples of 2, which contradicts our assumption that the original fraction $\frac{i}{j} is in lowest terms.
8. The assumption that $\sqrt{2}$ is rational leads to a contradiction, so it must be false. Therefore $\sqrt{2}$ cannot be expressed as the ratio of two whole numbers.

Legend has it that the Pythagoreans drowned the man who discovered this proof.

A proof which works by showing that its assumption leads to a contradiction is known as a *reductio ad absurdum*, reduction to an absurdity.

The Pythagoreans had discovered that their original philosophy of mathematics was incomplete, since it had no room for irrational numbers. The concept of "number" had to be expanded to include irrationals.

[^1]: I.e., non-negative integers.
