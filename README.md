Download Link: https://assignmentchef.com/product/solved-cse311-homework-1
<br>
<h1>1.     I Can’t Blab Such Blibber Blubber!</h1>

Translate these English statements into logic, making the atomic propositions as small as possible.

<ul>

 <li>Only if the stadium is full and the crowd is not subdued will we win the game.</li>

 <li>Define a set of <em>at most three </em>atomic propositions. Then, use them to translate all of these sentences about my plan to buy a watch into logic:

  <ol>

   <li>If the watch is no more than $25, then I will buy it.</li>

   <li>Unless it is on sale, I will not buy the watch. iii) I will buy the watch only if it is on sale and not more than $25.</li>

  </ol></li>

 <li>Define a set of <em>at most four </em>atomic propositions. Then, use them to translate all of these sentences about how a stack data structure can be used into logic:

  <ol>

   <li>You can push onto but not pop from the stack if it is empty. ii) Only if the stack is full can you pop from but not push onto it. iii) The stack is neither empty nor full unless you cannot pop from it or cannot push onto it.</li>

  </ol></li>

</ul>

<h1>2.     One, Two Three… How Many Fingers Do I See?</h1>

Find a compound proposition involving the propositional variables <em>p</em>, <em>q</em>, and <em>r </em>that is true precisely when a majority of <em>p</em>, <em>q</em>, and <em>r </em>are true. Explain why your answer works.

<h1>3.     Would You, Could You, With a Gate?</h1>

Using only…

<strong>AND </strong>Gates,       <strong>OR </strong>Gates,      and       Inverters (<strong>NOT </strong>Gates),

draw the diagram of a circuit with <strong>three inputs </strong>that computes the function <em>B</em><sub>(<em>p,q,r</em>)</sub>, defined as follows: If both <em>p </em>and <em>q </em>are true, then <em>B</em><sub>(<em>p,q,r</em>) = </sub>¬<em><sub>r</sub></em>. If exactly one of <em>p </em>and <em>q </em>is true, then <em>B</em><sub>(<em>p,q,r</em>) = <em>r</em></sub>. Otherwise, we have <em>B</em>(<em>p,q,r</em>) = F.

<h1>4.     Aunt Annie’s Alligator</h1>

Define the “<em>A</em>” gate by the rule <em>A</em><sub>(<em>r,s</em>) </sub>:<sub>= <em>r </em></sub>∨¬<em><sub>s </sub></em>.

Show how to implement the following gates using only <em>A</em>’s. You are allowed to use the constants T and F and the inputs <em>p </em>and <em>q</em>. You are allowed to use inputs multiple times. You must <em>justify your answers</em>.

<ul>

 <li>¬<em><sub>p</sub></em>, using only <strong>one </strong><em><sub>A </sub></em>gate</li>

 <li><em>p </em>∨ <em><sub>q</sub></em>, using at most <strong>two </strong><em><sub>A </sub></em>gates</li>

 <li>¬<sub>(<em>p </em></sub>∧ <em><sub>q</sub></em><sub>)</sub>, using at most <strong>two </strong><em><sub>A </sub></em>gates</li>

 <li><em>p </em>∧ <em><sub>q</sub></em>, using at most <strong>three </strong><em><sub>A </sub></em>gates</li>

</ul>

<h1>5.     Thing One and Thing Two</h1>

Use truth assignments (i.e., an assignment of a truth value to each variable) to demonstrate that the two propositions in each part are not logically equivalent. Explain why your assignment demonstrates this.

<ul>

 <li><em>p </em>∨ (<em>p </em>∧ <em>q</em>) <em>q </em>∨ (<em>p </em>∧ <em>q</em>)</li>

 <li>¬(<em>p </em>⊕ <em>q</em>) ¬<em>p </em>⊕¬<em>q</em></li>

 <li><em>p </em>→ (<em>q </em>→ <em>r</em>) (<em>p </em>→ <em>q</em>) → <em>r</em></li>

 <li>(<em>p </em>→ <em>q</em>) → (<em>q </em>→ <em>p</em>) (<em>q </em>→ <em>p</em>) → (<em>p </em>→ <em>q</em>)</li>

</ul>

<h1>6.     The Curious Case of The Lying TAs</h1>

A new UW CSE student wandered around the Paul Allen building on their first day in the major. They found (as many do) that there is a secret room in its basements. On the door of this secret room is a sign that says:

All ye who enter, beware! Every inhabitant of this room is either a TA who always lies or a student who always tells the truth!

<ul>

 <li>The CSE student walked into the room, and two inhabitants walked up to the student. One of them said “at least one of us is a TA.” Determine (with justification) all the possibilities for each of the two inhabitants.</li>

 <li>Three inhabitants walk up to the CSE student and surround the UW CSE student. One of them says “every TA in this circle has a TA to his immediate right.” Determine (with justification) all the possibilities for each of the three inhabitants.</li>

</ul>

<h1>7.     EXTRA CREDIT: XNORing</h1>

Imagine a computer with a fixed amount of memory. We give names, <em>R</em><sub>1</sub><em><sub>,R</sub></em><sub>2</sub><em><sub>,R</sub></em><sub>3</sub><em><sub>,… </sub></em>, to each of the locations where we can store data and call these “registers.” The machine can execute instructions, each of which reads the values from some register(s), applies some operation to those values to calculate a new value, and then stores the result in another register. For example, the instruction <em>R</em><sub>4 </sub>:<sub>= </sub><sub>AND</sub><sub>(<em>R</em></sub><sub>1</sub><em><sub>,R</sub></em><sub>2</sub><sub>) </sub>would read the values stored in <em>R</em><sub>1 </sub>and <em>R</em><sub>2</sub>, compute the logical and of those values, and store the result in register <em>R</em><sub>4</sub>.

We can perform more complex computations by using a sequence of instructions. For example, if we start with register <em>R</em><sub>1 </sub>containing the value of the proposition <em>p </em>and <em>R</em><sub>2 </sub>containing the value of the proposition <em>q</em>, then the following instructions:

<ol>

 <li><em>R</em><sub>3 </sub>:= NOT(<em>R</em><sub>1</sub>)</li>

 <li><em>R</em><sub>4 </sub>:= AND(<em>R</em><sub>1</sub><em>,R</em><sub>2</sub>)</li>

 <li><em>R</em><sub>4 </sub>:= OR(<em>R</em><sub>3</sub><em>,R</em><sub>4</sub>)</li>

</ol>

would leave <em>R</em><sub>4 </sub>containing the value of the expression ¬<em><sub>p </sub></em><sub>∨ (<em>p </em>∧ <em>q</em>)</sub>. Note that this last instruction reads from <em>R</em><sub>4 </sub>and also stores the result into <em>R</em><sub>4</sub>. This is allowed.

Now, assuming <em>p </em>is stored in register <em>R</em><sub>1 </sub>and <em>q </em>is stored in register <em>R</em><sub>2</sub>, give a sequence of instructions that

<ul>

 <li>only uses the <sub>XNOR </sub>operation (no <sub>AND</sub>, <sub>OR</sub>, etc.),</li>

 <li>only uses registers <em>R</em><sub>1 </sub>and <em>R</em><sub>2 </sub>(no extra space), and</li>

 <li>ends with <em>q </em>stored in <em>R</em><sub>1 </sub>and <em>p </em>stored in <em>R</em><sub>2 </sub>(i.e., with the original values in <em>R</em><sub>1 </sub>and <em>R</em><sub>2 </sub>swapped).</li>

</ul>