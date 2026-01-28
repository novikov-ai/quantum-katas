# Global Phase I

Goal: use sever Pauli gates to change the qubit state
    from a|0> + b|1> 
    to ia|0> + ib|1>

~~~qsharp
namespace Kata {
    operation GlobalPhaseI(q : Qubit) : Unit is Adj + Ctl {
        Z(q);
        Y(q);
        X(q);
    }
}
~~~