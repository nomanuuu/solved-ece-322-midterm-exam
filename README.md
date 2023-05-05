Download Link: https://assignmentchef.com/product/solved-ece-322-midterm-exam
<br>
(a)  Is it possible to have high-quality and low reliability software? What might be a possible example of such software?  Provide an illustrative example.

(b)  Give some reasons why you would <strong><em><u>not</u></em></strong> recommend the use of operational profiles.

(c)  Why would you consider the use constraints in the development of cause-effect graphs. In which sense are they useful?

(d)  What is the difference between software validation and software verification?

(e)  Explain a concept of coincidental correctness

(g) What is the relationship between Petri nets and finite state machines? Under which condition Petri net becomes a finite state machine

(h) In realizing testing for a given configuration problem considered are the following  components:  printers -2,   plug ins -3, browsers -3, operating systems -3, servers -3, monitors -2, e-mail systems-3, software packages of numeric optimization-3.

How much improvement is achieved when running combinatorial testing over testing all possible combinations?

<strong>2</strong><strong> </strong>Given is the following psuedocode

begin  program domain_test

var  a, b, x, y: real;

read(x,y)

if y&lt;=5 then       (P1)

a:= x-y-2

else

a:=x+y-2;

if a&lt;-3.0 then      (P2)

b:=a+x+2y+3;

else

b:=a-7y+3;

if b &gt;7  then      (P3)

print(x);

else

print (y);

end program




Draw a control flow graph for this pseudocode and determine its cyclomatic complexity.

<ol start="3">

 <li><strong> </strong>Consider a program that solves the following system of linear equations with a vector of unknown variables <strong><em>x</em></strong></li>

</ol>

<strong>A<em>x</em></strong> = <strong>b</strong>

where <strong>A</strong> =[<em>a</em><sub>ij</sub>], i=1,2,.., <em>n</em>, j=1, 2,…, <em>n</em>,   <strong>b</strong>    and <strong><em>x</em></strong>

(a) Discuss a testing strategy using equivalence classes. Elaborate on the valid and invalid equivalence classes.

(b) how can you proceed with testing when the number of equations is larger than the number of variables, namely dim(<strong><em>b</em></strong>) =<em>n</em> and dim(<strong><em>x</em></strong>) =<em>m</em> and  <em>m&lt;n</em>.

<ol start="4">

 <li>The subdomain is described by the following relationships</li>

</ol>

where 0  &lt; <em>K</em><sub>1</sub>&lt; <em>K</em><sub>2</sub>.

(a) plot the subdomain

<ul>

 <li>is the subdomain open or closed</li>

 <li>Propose an EPC strategy to complete testing here; show the test cases on the plot</li>

 <li>Show test cases produced by the weak <em>n</em> x 1 strategy</li>

</ul>


