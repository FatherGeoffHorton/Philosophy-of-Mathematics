## Infinite Problems

That there is no greatest number has been known probably as long as people have thought about mathematics. Euclid, around the year 300 B.C., demonstrated that there is no greatest prime number in a very simple fashion:

1. Assume that there is a greatest prime number *p*. This means there's a complete list of primes. For example, if 7 were the greatest prime, the list would be 2, 3, 5, 7.
2. Calculate the product of all the numbers in the list. For the example, this product is $2 x 3 x 5 x 7 = 420$. Then add 1, getting 421 in the example.
3. The product + 1 is not divisible by any of the known primes since it has a remainder of 1 when divided by any of them. Therefore either the number itself is prime (which 421 is) or it has a prime factor that does not appear on the list.
4. The "complete" list of prime is therefore not complete after all, and can never be complete, because the procedure above can always produce another entry in the list.
5. And therefore there is no greatest prime number.

Infinity comes in two types:

* In *potential* infinities, the infinite itself is never realized. Although the set of integers is itself infinite, any attempt to list them all will naturally end up with only a finite list. More items always can be added to the list, so it has the potential to grow without limit, but at any point in the counting process, the list remains finite.
* In *actual* infinities, the infinite is realized as a completed totality.

Ancient philosophers (e.g., Aristotle) had no difficulties talking about potential infinties, but they shyed away from actual infinities. They found the very concept of a completed infinite process to be meaningless.[^This did not stop Aristotle from thinking that the world was eternal.] This dislike for actual infinities lasted into the Christian era. Georg Cantor (who plays a prominent role in this narrative) thought that St. Augustine accepted actual infinity in *City of God*, Book XII, Chapter XVIII. Cantor may have been wrong on this point. Here's what St. Augustine wrote:

>Absit itaque ut dubitemus, quod ei notus sit omnis numerus, cuius intellegentiae, sicut in psalmo canitur, non est numerus. Infinitas itaque numeri, quamuis infinitorum numerorum nullus sit numerus, non est tamen inconprehensibilis ei, cuius intellegentiae non est numerus. Quapropter si, quidquid scientia conprehenditur, scientis conprehensione finitur: profecto et omnis infinitas quodam ineffabili modo Deo finita est, quia scientiae ipsius inconprehensibilis non est. Quare si infinitas numerorum scientiae Dei, qua conprehenditur, esse non potest infinita: qui tandem nos sumus homunculi, qui eius scientiae limites figere praesumamus, dicentes quod, nisi eisdem circuitibus temporum eadem temporalia repetantur, non potest Deus cuncta quae facit uel praescire ut faciat, uel scire cum fecerit? cuius sapientia simpliciter multiplex et uniformiter multiformis tam inconprehensibili conprehensione omnia inconprehensibilia conprehendit, ut, quaecumque noua et dissimilia consequentia praecedentibus si semper facere uellet, inordinata et inprouisa habere non posset, nec ea prouideret ex proximo tempore, sed aeterna praescientia contineret.[^http://www.thelatinlibrary.com/augustine/civ12.shtml, accessed 5/10/17]

>Far be it, then, from us to doubt that all number is known to Him whose understanding, according to the Psalmist, is infinite. The infinity of number, though there be no numbering of infinite numbers, is yet not incomprehensible by Him whose understanding is infinite. And thus, if everything which is comprehended is defined or made finite by the comprehension of him who knows it, then all infinity is in some ineffable way made finite to God, for it is comprehensible by His knowledge.[http://www.newadvent.org/fathers/120112.htm, accessed 5/10/17Source. Translated by Marcus Dods. From Nicene and Post-Nicene Fathers, First Series, Vol. 2. Edited by Philip Schaff. (Buffalo, NY: Christian Literature Publishing Co., 1887.) Revised and edited for New Advent by Kevin Knight. <http://www.newadvent.org/fathers/1201.htm>.]

Even if St. Augustine accepted actual infinity, he was very much an outlier. St. Thomas Aquinas, answering the question, "Whether it is an article of faith that the world began?," had this to say:

> Objection 6. Further, if the world always was, the consequence is that infinite days preceded this present day. But it is impossible to pass through an infinite medium. Therefore we should never have arrived at this present day; which is manifestly false.

> Reply to Objection 6. Passage is always understood as being from term to term. Whatever bygone day we choose, from it to the present day there is a finite number of days which can be passed through. The objection is founded on the idea that, given two extremes, there is an infinite number of mean terms.[^ST. I.46.2.]

St. Thomas's Reply implicitly rejects the infinite divisibility of a continuous segment; I am not sure that this rejection is well-founded. Be that as it may, his reply is stated in terms of potential infinity, rejecting the idea of an actual infinity.

Georg Cantor (1845-1914) is recognized as the man who first explored the properties of completed infinite sets. To understand the philosophical controversies that followed his discoveries[^Or inventions; this is one of the points at issue.], some understanding of his theories is necessary.

Cantor began by asking how the sizes of infinite sets can be compared. Are there different sizes of infinity?

The most basic infinite set is the natural numbers: {0, 1, 2, 3, ...} Now, as noted above, the set of prime numbers is also infinite: {2, 3, 5, 7, 11, 13, 17, ...} Is the set of prime numbers smaller than the set of natural numbers? At first glance it might appear to be smaller. After all, the prime numbers are a *proper subset* of the natural numbers: Every member of the set of prime numbers is also a member of the set of natural numbers, making the prime numbers a subset; but not every member of the set of natural numbers is a member of the set of prime numbers, making the prime numbers a *proper subset*. (The improper subset of a set is the set itself.)

Nevertheless, Cantor realized there's a very important sense in which all of these sets are the same size. For each and every natural number, there is a corresponding prime number: 1 in the natural numbers matches up with 2 in the primes, 2 in the natural numbers matches up with 3 in the primes, 3 goes with 5, 4 goes with 7, and so on. Since neither the natural numbers nor the prime numbers ever runs out, each and every member of the set of natural numbers corresponds with an element of the set of prime numbers, and each and every member of the set of prime numbers corresponds with an element of the set of natural numbers. This sort of correspondences is known as a *one-to-one correspondence*, and
