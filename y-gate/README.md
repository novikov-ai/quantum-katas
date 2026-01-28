# Y Gate

Goal: apply the Y gate to the qubit, that is transform
    from a|0> + b|1> 
    to ia|1> - ib|0>

~~~qsharp
namespace Kata {
    operation StateFlip (q : Qubit) : Unit is Adj + Ctl {
        X(q)
    }
}
~~~