# Apricot-Linear-Library
This is the Apricot linear algebra class.
it contains classes and functions for doing linear algebra
including matrix and vector operations.



< Incoming problems with this... lol >
I've made it so,
apricotVector will represent columns.
as such,
          ApricotVector([x,y,z])
is equivalent to
                  |x|
                  |y|
                  |z|


and ApricotMatrix will handle the implementation of columns.

ApricotMatrix(ApricotVector([x,y,z]), ApricotVector([x1,y1,z1]), ApricotVector([x2,y2,z2]));

is equivalent to

                 |x   x1   x2|
                 |y   y1   y2|
                 |z   z1   z2|
