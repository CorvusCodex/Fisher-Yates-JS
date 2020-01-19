# Fisher-Yates-JS
The Fisher–Yates shuffle is an algorithm for generating a random permutation of a finite sequence—in plain terms, the algorithm shuffles the sequence. The algorithm effectively puts all the elements into a hat; it continually determines the next element by randomly drawing an element from the hat until no elements remain. The algorithm produces an unbiased permutation: every permutation is equally likely. The modern version of the algorithm is efficient: it takes time proportional to the number of items being shuffled and shuffles them in place.

How to use: 

ADD SCRIPT TO HEAD OF YOUR WEBSITE:

<script src="fisher-yates.js"></script>

Create array:
var newarray = [1,2,3,4,5,6,7,8,9,10];

The simply call shuffle function:

newarray = shuffle(newarray);

That's it!
