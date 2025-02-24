Download link :https://programming.engineering/product/homework-10-electronic/

# Homework-10-Electronic
Homework 10 Electronic
Propositional Logic 1

We ask a logician (who only tells the truth) about his sentimental life, and he answers the following two statements:

I love Ann or I love Beth.

If I love Ann, then I love Beth.

What can we conclude? Answer the following questions by “yes”, “no”, “unsure”.

Does he love Ann?

Does he love Beth?

Does he love both?

Sample Answer:

no,no,no

2 Propositional Logic 2

Which of the following are correct?

F alse j= T rue.

T rue j= F alse.

(A ^ B) j= (A , B).

A , B j= A _ B.

A , B j= :A _ B.

(A ^ B) ) C j= (A ) C) _ (B ) C).

(C _ (:A ^ :B)) ((A ) C) ^ (B ) C).

(A _ B) ^ (:C _ :D _ E) j= (A _ B).

(A _ B) ^ (:C _ :D _ E) j= (A _ B) ^ (:D _ E).

(A _ B) ^ :(A ) B) is satis able.

(A , B) ^ (:A _ B) is satis able.

(A , B) , C has the same number of models as A , B for any xed set of proposition symbols that includes A; B; C.

VE 492 : Electronic #10 (Due July 31st, 2020 at 11:59pm)

Sample Answer:

a,b,c,d

3 Propositional Logic 3

We denote L0 the set of propositional logic sentences built from a set X of n propositional symbols.

we consider the following new formal languages, where some logical connectives are not allowed:

L1 is de ned as follows:

True and False are sentences of L1. All symbols of X are sentences of L1. If s; s0 are two sentences of L1, then :s, (s ^ s0 ), (s _ s0 ), and (s ) s0 ) are four sentences of L1.

L2 is de ned as follows:

True and False are sentences of L2. All symbols of X are sentences of L2. If s; s0 are two sentences of L2, then :s, (s ^ s0 ), and (s _ s0 ) are three sentences of L2.

L3 is de ned as follows:

True and False are sentences of L3. All symbols of X are sentences of L3. If s; s0 are two sentences of L3, then :s and (s ^ s0 ) are two sentences of L3.

L4 is de ned as follows:

True and False are sentences of L4. All symbols of X are sentences of L4. If s are two sentences of L4, then :s is a sentence of L4.

We consider the following binary relation between languages: L L’ i any sentences that can be expressed in L can equivalently be expressed in L’.

Answer “yes” or “no” the following questions.

L1 L0

L2 L0

L3 L0

L4 L0

L0 L1

L0 L2

L0 L3

L0 L4

Sample Answer:

no,no,no,no,no,no,no,no

First-Order Logic 1

Are the following are valid (necessarily true) sentences?

(9x x = x) ) (8y9z y = z).

8x P (x) _ :P (x).

8x Smart(x) _ (x = x).

Answer “Valid” or “Invalid” the following questions.

VE 492 : Electronic #10 (Due July 31st, 2020 at 11:59pm)

Sample Answer:

Valid,Valid,Valid

First-Order Logic 2

This exercise uses the function M ap Color and predicates In(T; y), Borders(x; y), and Country(x), whose arguments are geographical regions, along with constant symbols for various regions. In each of the following we give an English sentence and a number of candidate logical expressions.

Paris and Marseilles are both in France.

In(P aris ^ M arseilles; F rance).

In(P aris; F rance) ^ In(M arseilles; F rance).

In(P aris; F rance) _ In(M arseilles; F rance).

There is a country that borders both Iraq and Pakistan.

9c Country(c) ^ Border(c; Iraq) ^ Border(c; P akistan).

9c Country(c) ) [Border(c; Iraq) ^ Border(c; P akistan)].

[9c Country(c)] ) [Border(c; Iraq) ^ Border(c; P akistan)].

9c Border(Country(c); Iraq ^ P akistan).

All countries that border Ecuador are in South America.

8c Country(c) ^ Border(c; Ecuador) ) In(c; SouthAmerica).

8c Country(c) ) [Border(c; Ecuador) ) In(c; SouthAmerica)].

8c [Country(c) ) Border(c; Ecuador)] ) In(c; SouthAmerica).

8c Country(c) ^ Border(c; Ecuador) ^ In(c; SouthAmerica).

No region in South America borders any region in Europe.

:[9c; d In(c; SouthAmerica) ^ In(d; Europe) ^ Borders(c; d)].

8c; d [In(c; SouthAmerica) ^ In(d; Europe)] ) :Borders(c; d)].

:8c In(c; SouthAmerica) ) 9d In(d; Europe) ^ :Borders(c; d).

8c In(c; SouthAmerica) ) 8d In(d; Europe) ) :Borders(c; d).

No two adjacent countries have the same map color.

8x; y :Country(x) _ :Country(y) _ :Borders(x; y) _ :(M apColor(x) = M apColor(y)).

8x; y (Country(x)^Country(y)^Borders(x; y)^:(x = y)) ) :(M apColor(x) = M apColor(y)).

8x; y Country(x) ^ Country(y) ^ Borders(x; y) ^ :(M apColor(x) = M apColor(y)).

8x; y (Country(x) ^ Country(y) ^ Borders(x; y)) ) M apColor(x 6= y).

For each of the logical expressions, state whether it…

1 correctly expresses the English sentence;

2 is syntactically invalid and therefore meaningless;

3 is syntactically valid but does not express the meaning of the English sentence.

VE 492 : Electronic #10 (Due July 31st, 2020 at 11:59pm)
