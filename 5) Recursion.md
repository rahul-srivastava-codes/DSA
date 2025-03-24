(1) If you get stuck, remember i also got stuck and now i have good rank on leetcode.
(2) If its easy for you congrats you smart boy, honestly i was dumb at your level. 
<b> But i believed level sbke niklenge </b>
3) once done bro rest of dsa is done quickly, just twice time it takes to get over trees , graph and other stuff


Example -> print hello world five time
1) Using for loop
2) using while/do while loop
3)Its new guess it looping function over function

(* Note: When function stops running, it is removed from stack so , stack memory is freed up.
Now since memory is freed,and also return to program from where it started. *)
 i am still thinking about example, visit playlist at 16.13 
 as you thought it can print  1 2 3 4 5 or 5 4 3 2 1


 Recursion is writing the same function again and again with body also refering to same content.
space complexity is not constant and space efficicent due to call of functions
Helpful in bigger problem into small problems.


What is recursion?
Function calling itself is called recursion and inside loop there whill be condition.
It runs in form of tree.
if any instruction given before recursion function,and if it is called and order is 123
else order is 321

Lecture 47: Generalising the function
if any instruction is before recursion function it is executed during calling time
else if any instruction is after recursion function it is executed during returning time

Lecture 48: How recursion uses stack
Once  function is done ,it is deleted.side by side.
No of call depends on the argument we pass.
It is order of O(n) when it have n+1 calls

Lecture 49: Time complexity

T(n) = {1               n=0}
       {T(n-1) + 1               n>1}


Lecture 53 : Types of recursion:
Tail recursion-> if recursive call is last then it is called tail recursion.

So for n > 1 we have time taken as t(n) = t(n-k) + n
