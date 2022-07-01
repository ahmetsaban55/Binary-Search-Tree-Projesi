### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları;

1. root 7'dir.
2. 5, 7'den küçük olduğundan 7'nin soluna yazılır.

         7
        / 
       5
3. 1, 7 ve 5'ten küçük olduğundan 5'in soluna yazılır.


           7
          / 
         5
        /
       1

4.  8, 7'den büyük olduğundan 7'nin sağına yazılır.

            7
           / \
          5   8
         /
        1

5. 3; 7 ve 5'ten küçük, 1'den büyük olduğu için 1'in sağına yazılır. 

            7
           / \
          5   8
         / 
        1   
         \
          3
6. 6; 7'den küçük, 5'ten büyük olduğundan 5'in sağına yazılır.



            7
           / \
          5   8
         / \
        1   6
         \
          3

7. 0; önceki sayların tamamından küçük olduğundan sol kanadı takip ederek 1'in soluna yazılır.

             7
            / \
           5   8
          / \
         1   6
        / \
       0   3


8. 9; önceki sayların tamamından büyük olduğundan sağ kanadı takip ederek 8'in sağına yazılır.

             7
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3
9. 4; 7 ve 5'ten küçük, 1 ve 3'ten büyük olduğundan 3'ün sağına yazılır.
             
             7
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3
            \
             4

10. 2; 7 ve 5'ten küçük, 1'den büyük ve 3'ten küçük olduğundan 3'ün soluna yazılır.
             
             
              7
             / \
            5   8
           / \   \
          1   6   9
         / \
        0   3
           /  \
          2    4
