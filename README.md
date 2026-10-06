The purpose of this project is a C++ command line application that calculates electrical current using Ohm's Law (I= V / R).

The program expects two numbers seperated by a space:
1. Voltage (V)
2. Resistance (Ohms)

To compile and run the automated scceptance tests, use the provided bash script: 
'bash test.sh'

To compile manually, run:
'g++ -std=c++17 -Wall -Wextra -pedantic src/main.cpp -o build/app'

Example Outputs:
if you input '12 4', the output will be 'Current: 3 A'
if you input ' 12 0', the output will be 'Invalid Input'

the limitations for this program are that it currently only computes currents it can't solve for anything else. 

For this I had a couple of issues when trying to commit this to Git within my terminal however, I simply looked up what the errors meant and then problem solved from there and got it to work!