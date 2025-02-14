# EXP6
## AIM:
To study and implement C++ decision making statements Loops
### THEORY:
## FOR LOOP
The for loop is a control flow statement used to repeat a block of code a specified number of times. It is commonly used when the number of iterations is known beforehand.

### CODE 1:
```
//Sai sankar jena
//23070123112

#include<iostream>
using namespace std;
int main()
{
    int i;
    for (i=0;i<10;i++)
    {
        cout<<"Hello sir"<<endl;
    }
    return 0;
}
```
## WHILE LOOP:
The while loop is a control flow statement that executes a block of code as long as a specified condition is true. It is used when the number of iterations is not known beforehand and depends on dynamic conditions.
### CODE 2:
```
//SAI SANKAR JENA
//23070123112
#include <iostream>
using namespace std;

int main() {
    int i = 1;
    while (i <= 10) {
        cout << i << " ";
        ++i;
    }
    cout << endl; // Print a newline after the loop

    return 0;
}
```
### DO-WHILE
The do-while loop is similar to the while loop, but it guarantees that the loop body executes at least once. The condition is checked after the execution of the loop body.
### CODE 3:
```

//SAI SANKAR JENA
//23070123112
#include<iostream>
using namespace std;
int main()
{
    int i=1;
    do
    {
       cout<<i<<endl;
       i++;
    } while (i<=10);
    return 0;
}
```
### NESTED FOR LOOPS
Nested for loops involve placing one for loop inside another. This is useful for iterating over multi-dimensional data structures, like matrices.
### CODE 4:
```
//SAI SANKAR JENA
//23070123112
#include<iostream>
using namespace std;
int main()
{
    int a[3][3],s=0,i,j;
    for(i=0;i<3;i++)
    {
        for(j=0;j<3;j++)
        {
            cout<<"Enter any number for index number: "<<i<<j;
            cin>>a[i][j];
            s=s+a[i][j];
        }
    }
    cout<<"The sum of elements of matrix is:"<<s;
    return 0;
}
```
### NESTED WHILE LOOPS
Nested while loops involve placing one while loop inside another. This structure is useful for more complex data traversal and processing.
### CODE 5:
```
//SAI SANKAR JENA
//23070123112
#include <iostream>
using namespace std;

int main() {
    int i = 1;
    while (i <= 5) {
        int j = 1;
        while (j <= 5) {
            cout << "* ";
            ++j;
        }
        cout << endl;
        ++i;
    }

    return 0;
}
```
### NESTED DO WHILE LOOPS
Nested do-while loops involve placing one do-while loop inside another. They ensure that the inner loop executes at least once per outer loop iteration.

### CODE 6:
```
//SAI SANKAR JENA
//23070123112
#include <iostream>
using namespace std;

int main() {
    int i = 1;
    do {
        int j = 1;
        do {
            cout << "* ";
            ++j;
        } while (j <= 8);
        cout << endl;
        ++i;
    } while (i <= 8);

    return 0;
}
```
### NESTED FOR WITH A WHILE LOOP
Combining for loops with while loops can be useful for more complex iteration scenarios, allowing for flexible loop control within a nested structure.

### CODE 7:
```
//SAI SANKAR JENA
//23070123112
#include<iostream>
using namespace std;
int main()
{
   int i,j,k=0,n;
   cout<<"Enter number of rows: ";
   cin>>n;
   for(i=1;i<=n;i++)
   {
    for(j=1;j<(n-i);j++)
    {
        cout<<"  ";
    }
    while (k!=(2*i-1))
    {
        cout<<" * ";
        k++;
    }
    k=0;
    cout<<endl;
   } 
   return 0;

}
```


## Conclusion

- **For Loops**: Ideal for counting and iterating over a known number of iterations, offering a compact and readable syntax.
- **While Loops**: Best used when the number of iterations is not predetermined, with the loop executing as long as a condition remains `true`.
- **Do-While Loops**: Ensures that the loop body executes at least once, useful for scenarios where the initial execution is necessary regardless of the condition.
- **Nested Loops**: Provides powerful mechanisms for handling complex data structures, such as multi-dimensional arrays, by nesting one loop inside another.
## OUTPUTS:

### CODE1:
![Screenshot 2024-08-02 120156](https://github.com/user-attachments/assets/f9eb005c-38a5-4d00-9f91-a69fbc172b62)
### CODE 2:


![Screenshot 2024-08-02 120220](https://github.com/user-attachments/assets/c723388d-3da9-49eb-94f9-77a6e93686cc)
### CODE 3:

![Screenshot 2024-08-02 120249](https://github.com/user-attachments/assets/3ac98377-fd61-4ad7-a1a6-ccdbf4debf70)
### CODE 4:
![Screenshot 2024-08-02 120544](https://github.com/user-attachments/assets/60d081bc-80f5-47b1-b4ba-3288d6689819)
### CODE 5:
![Screenshot 2024-08-02 120613](https://github.com/user-attachments/assets/fbd1056f-e5ea-4bd3-9dc7-2517f239e194)
### CODE 6:

![Screenshot 2024-08-02 120815](https://github.com/user-attachments/assets/1434e013-afc2-4caa-89ed-4f6f600d3df4)
### CODE 7:
![Screenshot 2024-08-02 120852](https://github.com/user-attachments/assets/5bc45b00-b916-4877-b164-ee4d287d9eef)







