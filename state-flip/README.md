# State Flip

[Source](https://quantum.microsoft.com/en-us/tools/quantum-katas)

~~~qsharp
namespace Kata {
    operation StateFlip (q : Qubit) : Unit is Adj + Ctl {
        X(q)
    }
}
~~~