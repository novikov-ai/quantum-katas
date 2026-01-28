# State Flip

Goal: change the qubit state 
    from a|0> + b|1> 
    to a|1> + b|0>

~~~qsharp
namespace Kata {
    operation StateFlip (q : Qubit) : Unit is Adj + Ctl {
        X(q)
    }
}
~~~