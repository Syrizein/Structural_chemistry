# Structural Chemistry

## General Description

### About the Project

We aim to reform the teaching methods of *Structural Chemistry*  by introducing more advanced and powerful tools.

### A Quick Introduction to Structural Chemistry

The lecture notes for *A Quick Introduction to Structural Chemistry*, a short lecture I delivered in Nov 2021.
The lecture is intended for undergraduate students in their second year of study. Previous knowledge of high-school chemistry, calculus and linear algebra is recommended.

Notes: Using the **.tex** file is strongly recommended as the .pdf may be not updated on time.  

## Update Log

### CURRENT VERSION: 0.2 (Jun 2022)

1. Changed the title of lecture notes to "A Quick Introduction to Structural Chemistry".  The current content makes it unsuitable to name it with "Quantum Chemistry", so I decided to use "Structural Chemistry" instead.
2. Expanded the projct. Now it allows places to contain other stuffs on structural chemistry.

### CURRENT VERSION: 0.1 (Jun 2022)

1. Created the project.

## Future Development Plans

1. Create an English version of "A Quick Introduction to Structural Chemistry". 
2. Sections in "A Quick Introduction to Structural Chemistry" listed below need to be re-writed:  
   
   - Operators. Matrix notions could be introduced first, and then using function notions. I also plan to implement Dirac notation here.
   - Atomic Spectra. Need to be further expanded.
   - Variational Method. The variational method is
   $$\frac{\langle \rm{\Psi} \lvert \scr{H} \rvert \rm{\Psi} \rangle}{\langle \rm{\Psi} | \rm{\Psi} \rangle} \geq E_0 = \frac{\langle \rm{\Phi} \lvert \scr{H} \rvert \rm{\Phi} \rangle}{\langle \rm{\Phi} | \rm{\Phi} \rangle} $$ 
   We **assumed without mentioning** that  $\Psi = \Psi(\psi_1,\psi_2, ... , \alpha_1, \alpha_2, ... )$
   where $ \alpha_1, \alpha_2, ...$ are **independent**, so that to minimize the energy we need to set
   $$ \frac{\partial E}{\partial \alpha_1} = \frac{\partial E}{\partial \alpha_2} = \dots = 0$$
   This is of course not the most general case. Lagrangian multiplier method is needed as the coefficients are often dependent on each other.
   - Computational Chemistry.
   
3. A Wolfram notebook on Structural Chemistry, based on the book *Bonding through Code: Theoretical Models for Molecules and Materials* by Daniel C. Fredrickson.
