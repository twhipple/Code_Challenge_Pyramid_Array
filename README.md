
# Code Challenge: 

![](https://raw.githubusercontent.com/twhipple/coding_challenge_consecutive_repetition/main/Images/wilhelm-gunkel-invYnIE2Mv8-unsplash.jpg)

*Counting the number of repeated letters, over and over. Source: Wilhelm Gunkel, Unsplash.com*


## Code_Challenge_Pyramid_Array

In this level 6kyu from Codewars, I solve the Pyramid Array challenge - which involves using repetitive digits to add to increasingly larger lists, all within a list and forming a sort of pyramid.

Write a function that when given a number >= 0, returns an Array of ascending length subarrays.

Note: the subarrays should be filled with 1's


![](https://raw.githubusercontent.com/twhipple/coding_challenge_consecutive_repetition/main/Images/nicole-ferzoco-nY2ksaM92co-unsplash.jpg)

*I felt like I was going around in consecutive circles with this kata! Source: Nicole Ferzoco, Unsplash.com*


## Examples:

* pyramid(0) => [ ]
* pyramid(1) => [ [1] ]
* pyramid(2) => [ [1], [1, 1] ]
* pyramid(3) => [ [1], [1, 1], [1, 1, 1] ]


## Additionally

This kata didn't take me as long as I had expected. I struggled at first with the idea of creating the individual layers of the pyramid - trying to think about how to generate consecutive 1's. When I first iterated through a list it would create a layer with either the total number of digits [1, 2, 3] or it would just return subsequent lists [1,1,1], [1,1,1], [1,1,1]. Of course I should have remembered to just multipy the basic list [1] by which ever row I wanted - as seen in the 'Other Solutions'!

This kata was written by: sahglie

Thank you to Codewars for helping me practice my Python skills.

![](https://raw.githubusercontent.com/twhipple/coding_challenge_consecutive_repetition/main/Images/letters-2-Stephen%20Tainton.jpg)

*This code challenge took a lot of time looking at strings of letters! Source: Stephen Tainton, Unsplash.com*


