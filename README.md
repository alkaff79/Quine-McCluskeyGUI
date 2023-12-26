# Quine-McCluskeyGUI
During the course of electrical engineering studies, particularly in the field of electronics and communications, there's an important subject called Digital Electronics (EE411). We were tasked with a project that applies the Quine-McCluskey method.
The Quine-McCluskey method is a technique used in digital logic design and Boolean algebra for minimizing Boolean functions. It's named after Willard V. Quine and Edward J. McCluskey, who independently developed the method in the 1950s.
Boolean functions can be represented in truth tables or algebraic forms, such as Sum of Products (SOP) or Product of Sums (POS). The goal of the Quine-McCluskey method is to simplify these functions to their minimal form, reducing the number of terms and variables without changing the function's behavior.
- Steps:

1.Implicant Generation: Start by listing all the minterms (or maxterms) for the given function in binary form.
  
2.Grouping: Group the minterms based on the number of 1s in their binary representations. This step creates groups of minterms having similar patterns with differing only in one variable position.

3.Finding Prime Implicants: Compare the groups and identify pairs that differ by only one variable. Combine these pairs to form new groups. Repeat this process until no further combinations can be made.

4.Essential Prime Implicants: Identify the prime implicants that cover all the minterms in the function. These are the essential prime implicants necessary to represent the function.

5.Selecting Minimum Terms: Choose a combination of essential prime implicants that cover all the minterms. This combination represents the simplified form of the Boolean function.

- Advantages:

Systematic Approach: It offers a systematic way to minimize Boolean functions, ensuring that the simplified form is accurate.

Optimization: It helps reduce the number of terms and variables, which is crucial in digital circuit design for minimizing hardware complexity and optimizing circuit performance.

- Challenges:

Complexity: Handling larger functions with many variables can become computationally intensive.

Optimality: While Quine-McCluskey provides a minimal solution, for extremely large problems, finding the absolute minimum solution may still be challenging due to computational limitations.


However,the project involved writing code using MATLAB to provide the simplest Boolean expression for 4 variables. The team designed a graphical interface using MATLAB to allow users to input the required data for calculation. One of the notable features of our project is its capability to handle 26 variables and more!


![image](https://github.com/alkaff79/Quine-McCluskeyGUI/assets/130121869/deaf43fa-5016-4008-9944-fa08aa48eacb)


- Test the code with solved example:
f(A,B,C,D)= m(4,8,10,11,12,15)+d(9,14).
the answer is:
![image](https://github.com/alkaff79/Quine-McCluskeyGUI/assets/130121869/9a01f611-3e50-4909-9de7-38394bc2525a)
  from  matlab:

![image](https://github.com/alkaff79/Quine-McCluskeyGUI/assets/130121869/71af7fe3-b423-468d-9e33-dc9c5057fb3d)


![image](https://github.com/alkaff79/Quine-McCluskeyGUI/assets/130121869/2bbce7c6-03fa-4896-9c18-0baa64255138)

From the command window:
![image](https://github.com/alkaff79/Quine-McCluskeyGUI/assets/130121869/3f94920a-8d57-441f-b7fb-79d1e7d2e1a7)





