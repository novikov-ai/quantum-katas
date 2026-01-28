# Sign Flip On Zero

Goal: use sever Pauli gates to change the qubit state
    from a|0> + b|1> 
    to -a|0> + b|1>

~~~qsharp
namespace Kata {
    operation SignFlipOnZero (q : Qubit) : Unit is Adj + Ctl {
        X(q);
        Z(q);
        X(q);
    }
}
~~~