Q1: Basics of Sets and Relations #1

Set A = {1,2,3,4,5,6} 
Set B = {2,3,4,5,6,7,8}
How many elements are present in A U B? 
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.

Answer--->> 8

sollution-->>

A U B ( U - or) = A + B - A and B

A and B = A + B - A U B ( U - or)

A U B = {1,2,3,4,5,6} + {2,3,4,5,6,7,8} - {1,2,3,4,5,6,7,8} = {1,2,3,4,5,6,2,3,4,5,6,7,8} - {1,2,3,4,5,6,7,8} = {2,3,4,5,6}

Q2: Basics of Sets and Relations #2

Set A = {1,2,3,4,5,6} 
Set B = {2,3,4,5,6,7,8}
How many elements are present in A and B? 
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.

Answer: 5

A U B ( U - or) = A + B - A and B
A and B = A + B - A U B ( U - or)
A U B = {1,2,3,4,5,6} + {2,3,4,5,6,7,8} - {1,2,3,4,5,6,7,8} = {1,2,3,4,5,6,2,3,4,5,6,7,8} - {1,2,3,4,5,6,7,8} = {2,3,4,5,6}

Q3: Basics of Sets and Relations #3

Set A = {1,2,3,4,5,6} 
Set B = {2,3,4,5,6,7,8}
How many elements are present in A - B? 
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.




Q1: Basics of Sets and Relations #1

Set A = {1,2,3,4,5,6} 
Set B = {2,3,4,5,6,7,8}
How many elements are present in A U B? 
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.
Answer: 8
A U B ( U - or) = A + B - A and B
A U B = {1,2,3,4,5,6} + {2,3,4,5,6,7,8} - {2,3,4,5,6} = {1,2,3,4,5,6,2,3,4,5,6,7,8}-{2,3,4,5,6}={1,2,3,4,5,6,7,8}
Q2: Basics of Sets and Relations #2

Set A = {1,2,3,4,5,6} 
Set B = {2,3,4,5,6,7,8}
How many elements are present in A and B? 
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.
Answer: 5
A U B ( U - or) = A + B - A and B
A and B = A + B - A U B ( U - or)
A U B = {1,2,3,4,5,6} + {2,3,4,5,6,7,8} - {1,2,3,4,5,6,7,8} = {1,2,3,4,5,6,2,3,4,5,6,7,8} - {1,2,3,4,5,6,7,8} = {2,3,4,5,6}
Q3: Basics of Sets and Relations #3

Set A = {1,2,3,4,5,6} 
Set B = {2,3,4,5,6,7,8}
How many elements are present in A - B? 
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.
Answer: 1
A - B = {1,2,3,4,5,6} - {2,3,4,5,6,7,8} = {1}
We substract from set A the values which are in set B if value in set A = value in set B and the result is what left in set > A.
Q4: Basics of Sets and Relations #4

Set A = {1,2,3,4,5,6} 
Set B = {2,3,4,5,6,7,8}
What is the total number of ordered PAIRS present in the Cartesian Product AxB? 
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.
Answer: 42
set A = 6 values
set B = 7 values
number pairs = 6*7 =42
(1,2) (1,3) (1,4) (1,5) (1,6) (1,7) (1,8) (2,2) (2,3) (2,4) (2,5) (2,6) (2,7) (2,8) (3,2) (3,3) (3,4) (3,5) (3,6) (3,7) (3,8)
(4,2) (4,3) (4,4) (4,5) (4,6) (4,7) (4,8) (5,2) (5,3) (5,4) (5,5) (5,6) (5,7) (5,8) (6,2) (6,3) (6,4) (6,5) (6,6) (6,7) (6,8)
(7,2) (7,3) (7,4) (7,5) (7,6) (7,7) (7,8) (8,2) (8,3) (8,4) (8,5) (8,6) (8,7) (8,8)
Q5: Basics of Sets and Relations #5

Consider the following data table named Student.
Student Name	Number	Sex
Ben	3412	M
Dan	1234	M
Nel	2341	F
σ(Number<3000)(Student)
Only enter a single integer. Do not include any extra spaces or newlines.
Answer: 2
Number 3412 < 3000 and Number 2341 < 3000
Q6: Basics of Sets and Relations #6

Consider the following data table named Student.
Name	Number	Sex
Nina	3412	F
Mike	1234	M
Nelson	2341	F
π(Name, Number)(Student)
Only enter a single integer. Do not include any extra spaces or newlines.
Answer: 2
Name, Number
Q7: Basics of Sets and Relations #7

Consider the following data table named Student.
Student Name	Number	Sex
Nina	3412	F
Mike	1234	M
Nelson	2341	F
Here is another data table named Teaching Assistants
Subject	ID
Physics	3412
Chemistry	1111
Mathematics	2341
Student ⊳⊲(Number=ID) Teaching Assistants
Only enter a single integer. Do not include any extra spaces or newlines.
Answer: 2
Number=ID=3412
Number=ID=2341
Q8: Relational Algebra - 3

Which is a join condition contains an equality operator?

Answer: Equijoins - joining against equality
FROM t1
JOIN t2
ON t1.id=t2.id
t1	t2
2 A2	5 B5
5 A5	1 B1
3 A3	3 -
1 -	6 B6
4 A4	2 B2
NAN	5 C5
2 A2 --> 2 B2
5 A5 --> 5 B5
5 A5 --> 5 C5
3 A3 --> 3 -
1 - --> 1 B1
4 A4 does not equal 6 B6
Q9: Relational Algebra - 4

In precedence of set operators the expression is evaluated from:
Answer: Left to right
Q10: Database Query Languages

Using which language can a user request information from a database ?
Answer: Query
Q11: Procedural Language

Which one of the following is a procedural language ?
Answer: Relational algebra
Q12: Relations - 1

Answer: Join
Q13: Relations - 2

Answer: Cartesian product
A × B = {(x, y) : x ∈ A, y ∈ B}
A = {7, 8} and B = {2, 4, 6}
A × B = {(7, 2); (7, 4); (7, 6); (8, 2); (8, 4); (8, 6)}
Q14: Index Architecture Types

How many index architecture type classifications are there in MS SQL Server?
Answer: 2
Clustered and non clusterd
Q15: OLAP Performance

Which of these helps OLAP speed up queries, in terms of performance?
Answer: Aggregation
Q16: OLAP Operations - 1

This OLAP operation involves computing all of the data relationships for one or more dimensions.
Answer: roll-up
Q17: Indexes - 2

Which of the following statement is true about row locators in non-clustered indexes in MS SQL Server?
Answer: If the table has a clustered index, or the index is on an indexed view, the row locator is the clustered index key for the row.
Q18: Indexes - 3

* In the first design, the fill factor is 20% and the total number of free rows per page are A.
* In the second design, the fill factor is 40% and the total number of free rows per page are B. 
Which the followings describes the relation between A and B:
Answer: A = 1.33B
Q19: OLAP Operations - 2

This OLAP Operation rotates the data, and delivers an alternative to the original presentation. 
Answer: pivot
Q20: Indexes - 4

The correct syntax for creating composite indexes in MS SQL Sever is:
Answer:
CREATE INDEX index_name

ON table_name(column1, column2);

Q21: OLAP Cube Metadata

What is the source of the cube metadata for OLAP?
Answer: Both star and snowflake schema(s)
Q22: OLAP Name(s)

Answer: Multidimensional Cube, HyperCube
Q23: The Total View

Which of these provides a total view of the organization?
Answer: Data Warehousing
Q24: OLAP Operation Types


Q1: Select D1,D2,D3,Sum(x) From DataPoints Group By D1,D2,D3

Q2: Select D1,D2,D3,Sum(x) From DataPoints Group By D1,D2,D3 WITH CUBE

Q3: Select D1,D2,D3,Sum(x) From DataPoints Group By D1,D2,D3 WITH ROLLUP

Suppose attributes D1, D2, and D3 have n1, n2, and n3 different values respectively, and assume that each possible combination of values appears at least once in the table DataPoints. The number of tuples in the result of each of the three queries above can be specified as an arithmetic formula involving n1, n2, and n3. Pick the one tuple (a,b,c,d,e,f) in the list below such that when n1=a, n2=b, and n3=c, then the result sizes of queries Q1, Q2, and Q3 are d, e, and f respectively.
Answer: (4, 7, 3, 84, 160, 117)
Q25: Database Normalization #1 - 1NF

Product-ID	Colors	Price
1	Red,Green	15.0
2	Blue	18.0
3	Yellow,Pink	2.5
Answer:
3 (1, 15.0), (2, 18.0), (3, 2.5)
5 (Red, 15.0), (Green, 15.0), (Blue, 18.0), (Yellow, 2.5), (Pink, 2.5)
2 Product-ID and Price, Colors and Price
Q26: Database Normalization #2 - 1/2/3 NF

Answer: NOT in 3NF
Q27: Database Normalization #3

Answer: 3
Q28: Database Normalization #4

Answer: 10
Q29: Database Normalization #5

R(a, b,c,d)
a,c -> b,d
a,d -> b
Also, a,b is a primary key for the above relation.
The above relation is in x NF form where x may take the following values {1,2,3,3.5} corresponding to {1NF, 2NF, 3NF and BCNF} respectively. 
What is the maximum possible value of x such that the above relation satisfies the *x*NF form? 
Your answer should only be restricted to one of these numbers:1/2/3/3.5 Do not leave any leading or trailing spaces.
Answer: 3
Q30: Database Normalization #6

Relations (The key is CAPITALIZED): customer(name,addr,MEMBERNO) movie(DESCRIPTION,director,serialno) borrow(memberno,DATE,SERIALNO)

Determinants: description->director,serialno serialno->description serialno->director name,addr -> memberno memberno -> name,addr serialno,date -> memberno

What is the maximum possible value of _x_ such that the above relation satisfies the _xNF_ form? 
Your answer should only be restricted to one of these numbers:1/2/3/3.5. Do not leave any leading or trailing spaces.
Answer: 2NF
Q31: Database Normalization #7

Relations: movie(DESCRIPTION,serialno) serial(SERIALNO,director) customer(name,addr,MEMBERNO) borrow(memberno,DATE,SERIALNO)

Determinants: description->director,serialno serialno->description serialno->director name,addr -> memberno memberno -> name,addr serialno,date -> memberno

What is the maximum possible value of _x_ such that the above relation satisfies the _xNF_ form? 
Your answer should only be restricted to one of these numbers: 1/2/3/3.5. Do not leave any leading or trailing spaces.
Answer: 3.5NF
Q32: Database Normalization #8

Relations (The key is CAPITALIZED): customer(name,addr,MEMBERNO) movie(DESCRIPTION,director,serialno) borrow(memberno,DATE,SERIALNO)

description->director,serialno
serialno->description
serialno->director
name,addr -> memberno
memberno -> name,addr
serialno,date -> memberno
In the text box, only enter the index number (1-6) of the dependency which you have identified as non-key.
Answer: 3
Q33: Database Normalization #9

R(a,b,c,d,e)
Which of these determinants is a NON-CANDIDATE key? In the text box, only enter the index number (1-3) of the dependency which you have identified as non-key.
a,c -> b,d,e
a,d -> b
a,c,e -> b,d
Answer: 2
Q34: Database Normalization #10

Restaurant	Crust	Delivery Area
X Pizza	Thick	Whitefield
X Pizza	Thick	Greenville
X Pizza	Thick	Capital
X Pizza	Stuffed	Whitefield
X Pizza	Stuffed	Greenville
X Pizza	Stuffed	Capital
Papa Pizza	Thin	Capital
Papa Pizza	Stuffed	Capital
F1 Pizza	Thick	Whitefield
F1 Pizza	Thick	Greenville
F1 Pizza	Thin	Whitefield
F1 Pizza	Thin	Greenville
In the text box below, enter the value of the integer N.
Answer: 6
Q35: Databases - Relational Calculus

For the given set S, what will be the answer? Fill up the answer box with the required integer.
S = {4,5,6,7,10,11,19,18,3}
Answer: 19
Q36: Databases - Keys

bookname	author	language
A Tale of Two Cities	Charles Dickens	English
Oliver Twist	Charles Dickens	English
Godaan	Premchand	Hindi
Chandrakanta	Devaki Nandan Khatri	Hindi
Hamlet	William Shakespeare	English
The Merchant of Venice	William Shakespeare	English
Only fill in the name of the field which may be used as the primary key. Grading is case-sensitive.
Answer: bookname
Q37: Databases - Natural Joins

Relation R(A,C) has the following tuples:
A	C
3	3
16	4
12	3
3	15
27	1
Relation S(B,C,D) has the following tuples:
B	C	D
50	1	6
1	55	8
4	3	9
27, X, Y, Z
In the answer box, fill up the values of the integers X, Y and Z in three separate lines. e.g.
10
20
30  
Answer: A=27(table 1) --> C=1 (table 1) --> C=1 (table 2) --> B=50 (table 2) and D=9 (table 2)
A	B	C	D
27	50	1	6
Q38: Databases - Differences

Relation R(A,B,C) has the following tuples:
A	B	C
1	2	3
4	2	3
4	5	6
2	5	3
1	2	6
and relation S(A,B,C) has the following tuples:
A	B	C
2	5	3
2	5	4
4	5	6
1	2	3
4, b, c
Find the integers b and c. Fill in the values in the answer box, each on a new line.
Output Format
Two integers, corresponding to b and c, each on a new line. For example:
4  
5  
Answer:
A	B	C
4	2	3
1	2	6
b=2
c=3

