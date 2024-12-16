This repository demonstrates an uncommon error in Perl related to unordered hash iteration.  The `keys` function does not guarantee a specific order when iterating through a hash.  This can lead to unexpected behavior in your code if you assume a particular order.

The `bug.pl` file shows the problem, and `bugSolution.pl` demonstrates a solution using `sort` to ensure a consistent order.