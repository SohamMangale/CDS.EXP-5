# Experiment-5
## Aim -
To study and implement C++ decision making statements

## Theory -
Decision-making statements control the flow of a program based on conditions. Key types include:

### 1. If-Else Statement:
Executes one block if the condition is true, another if false.

### 2.Nested if-else statements:
these are used when you need to check multiple conditions in a hierarchical manner. An if or else block can contain another if-else statement inside it. This is useful for more complex decision-making processes.

### 3. calculator statement:
it is used for doing mathematical calculations among some given values.

### 4. Switch Case Statement:
Used in some languages to handle multiple conditions, mimicked in Python using dictionaries.

## code -
### 1. If-Else
```
//Soham
//23070123084
// entc b1
//experiment 5
#include <iostream>
using namespace std;
int main() 
{
    double n1, n2, n3;
    cout << "Enter three numbers: ";
    cin >> n1 >> n2 >> n3;
    if(n1 >= n2 && n1 >= n3)
        cout << "Largest number: " << n1;
    else if(n2 >= n1 && n2 >= n3)
        cout << "Largest number: " << n2;
    else 
        cout << "Largest number: " << n3;
        return 0;
}
```
### 2. Nested if else
```
//Soham
//23070123084
// entc B1
//experiment 5B
#include <iostream>
using namespace std;
int main() 
{
    double n1, n2, n3;
    cout << "Enter three numbers: ";
    cin >> n1 >> n2 >> n3;
    if (n1 >= n2) 
    {
        if (n1 >= n3)
            cout << "Largest number: " << n1;
        else
            cout << "Largest number: " << n3;
    }
    else {
        if (n2 >= n3)
            cout << "Largest number: " << n2;
        else
            cout << "Largest number: " << n3;
    }
    return 0;
}
```
### 3. Calculator
```
//Soham
//23070123084
// entc B1
//experiment 5C
#include<iostream>
using namespace std;

int main() {
    char oper;
    float num1, num2;

    cout << "Enter an operator (+, -, *, /): ";
    cin >> oper;
    cout << "Enter two numbers: " << endl;
    cin >> num1 >> num2;

    switch (oper) {
        case '+':
            cout << num1 << " + " << num2 << " = " << num1 + num2 << endl;
            break;
        case '-':
            cout << num1 << " - " << num2 << " = " << num1 - num2 << endl;
            break;
        case '*':
            cout << num1 << " * " << num2 << " = " << num1 * num2 << endl;
            break;
        case '/':
            if (num2 != 0)
                cout << num1 << " / " << num2 << " = " << num1 / num2 << endl;
            else
                cout << "Error! Division by zero." << endl;
            break;
        default:
            cout << "Error! The operator is not correct" << endl;
            break;
    }

    return 0;
}
```
### 4. Switch case
```
//Soham
//23070123084
// entc B1
//experiment 5D
#include<iostream>
using namespace std;

int main()
{
    int choice;
    cout << "1. Monday" << endl
         << "2. Tuesday" << endl
         << "3. Wednesday" << endl
         << "4. Thursday" << endl
         << "5. Friday" << endl
         << "6. Saturday" << endl
         << "7. Sunday" << endl;
    cout << "Enter your choice: ";
    cin >> choice;
    
    switch(choice) {
        case 1:
            cout << "Monday" << endl;
            break;
        case 2:
            cout << "Tuesday" << endl;
            break;
        case 3:
            cout << "Wednesday" << endl;
            break;
        case 4:
            cout << "Thursday" << endl;
            break;
        case 5:
            cout << "Friday" << endl;
            break;
        case 6:
            cout << "Saturday" << endl;
            break;
        case 7:
            cout << "Sunday" << endl;
            break;
        default:
            cout << "Wrong Input" << endl;
            break;
    }
    
    return 0;
}
```
## Explanation:-
#### if else : statement for executing a block if it is true otherwise for false.

#### nested if else : are used when you need to check multiple conditions in a hierarchical manner.

#### calculator statement : is used for doing mathematical calculations among some given values.

#### Switch Case Statement : Used in some languages to handle multiple conditions, mimicked in Python using dictionaries.

## Output:-
1. If else
![image](https://github.com/user-attachments/assets/fe24bbfb-9a0e-4733-ac33-c546e043ec86)


2. Nested if else
![image](https://github.com/user-attachments/assets/f15c9fd5-551b-4b56-958a-7dfe598be3dc)


3. Switch
![image](https://github.com/user-attachments/assets/9718062e-f4fd-4528-bf0a-bf2618ddafd5)


4. Calculator
![image](https://github.com/user-attachments/assets/eab5a2f3-66fd-40bd-be25-4256df6715c0)


## Conclusion:-
Decision-making statements in programming control the flow of execution based on conditions. The if-else statement executes different code blocks depending on whether a condition is true or false, while the nested if else statement allows for multiple conditions to be checked in sequence. The switch statement provides a way to select one of many code blocks to execute based on the value of an expression, ideal for handling discrete values. calculator helps in doing mathematical opera
