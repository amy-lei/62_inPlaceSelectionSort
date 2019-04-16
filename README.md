# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by 3. The loop has to iterate through every element to find the reigning champ, so if the number of elements triples, the number of elements the loop much check triples.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by 3.
Reigning champ is invoked for every filled index of the list, so if the number of elements triples, then the number of times reigning champ is invoked triples. 
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by 9. If each invocation of reigning champ triples, and the algorithm is invoked 3 more times, then the resulting time should be the product of the two multipliers. 
[Justify, in about 2 sentences.]
