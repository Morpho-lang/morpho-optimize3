# Optimize3 todo list

* Alternative linesearch algorithms [exact, wolfe, others] [x]

* Refactor so that Newton and Quasinewton methods can use arbitrary linesearch controllers [perhaps a common base class for this?] 

* BarrierAdapter

* FIREController

* Inequality constraints

* Local constraints 

* Matrices in constraint 

* May be a memory issue in number.format() with c=0.375

* Common standard for reporting beyond quiet, maybe ["silent", "quiet", "verbose"] ?
             Warnings Iteration reports Information
    silent =    X              X             X
    quiet  =    Y              X             X
    normal =    Y              Y             X
    verbose =   Y              Y             Y
