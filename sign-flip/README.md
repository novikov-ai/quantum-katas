# Sign Flip

Goal: change the qubit state 
    from a|0> + b|1> 
    to a|0> - b|1>

~~~qsharp
namespace Kata {
    operation SignFlip (q : Qubit) : Unit is Adj + Ctl {
        Z(q)
    }
}
~~~