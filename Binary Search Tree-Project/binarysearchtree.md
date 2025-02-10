# Binary Project Tree Project 3

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Write the Binary-Search-Tree stages of the sequence.

#### Example: root is x. y is found to the right of the root. To the left of it is z, etc.

```
 Step 1: 7 becomes the root of the tree.

                       7


Step 2: 5 is less than 7, so it is placed to the left of 7.


                       7
                      /
                     5


Step 3: 1 is less than 7 and less than 5, so it is placed to the left of 5.

                      7
                     /
                    5
                   /
                  1

Step 4: 8 is greater than 7, so it is placed to the right of 7.

                      7
                     / \
                    5   8
                   /
                  1

 Step 5: 3 is less than 7 and less than 5, but greater than 1, so it is placed to the right of 1.

                       7
                     /  \
                    5    8
                   /
                  1
                   \
                    3

Step 6: 6 is less than 7 but greater than 5, so it is placed to the right of 5.

                       7
                     /  \
                    5    8
                   / \
                  1   6
                   \
                    3

Step 7: 0 is less than 7,5 and 1, so it is placed to the left of 1.

                       7
                     /  \
                    5    8
                   / \
                  1   6
                /  \
               0    3

Step 8: 9 is greater than 7 and 8, so it is placed to the right of 8.

                       7
                     /  \
                    5    8
                   / \    \
                  1   6    9
                /  \
               0    3

Step 9: 4 is less than 7 and 5 but greater than 1 and 3, so it is placed to the right of 3.

                       7
                     /  \
                    5    8
                   / \    \
                  1   6    9
                /  \
               0    3
                     \
                      4

 Step 10: 2 is less than 7,5,4 and 3 but greater than 1 and 3, so it is placed to the left of 3.

                       7
                     /  \
                    5    8
                   / \    \
                  1   6    9
                /  \
               0    3
                   / \
                  2   4

```
