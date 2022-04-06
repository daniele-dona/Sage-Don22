# Sage-Don22
SageMath code for "A sum-bracket theorem for simple Lie algebras" (Dona)

The code deposited here refers to several SageMath programs relative to the paper "A sum-bracket theorem for simple Lie algebras" (available as arXiv:2204.02018), by Daniele Dona.

The programs are written in SageMath, version 8.9.

There are 5 files, one for each of the 5 Lie algebras: g_2, f_4, e_6, e_7, e_8. Each file contains a program that constructs an extremal basis for the algebra, and then verifies that the basis satisfies the assertions of Theorem 5.2(b) in the paper. The output of each program is "True", meaning that Theorem 5.2(b) holds for each of our choices. Mind that, due to the slight methodological differences between the cases, some functions may appear with the same name inside different programs but perform slightly different tasks, or the same task with different input types.

There is generally nothing more in the code provided than there is in the paper itself. However, for the sake of transparency, in the case of e_8 we report explicitly the cumbersome basis elements that SageMath is able to provide through the "LieAlgebra" command: in this way, the reader has a concrete object to work with if they wish to do so, regardless of possible changes to the libraries that SageMath currently uses. All other commands in the 5 files are elementary enough to not be sensitive to future variations, and can be replicated in any other language the reader desires.
