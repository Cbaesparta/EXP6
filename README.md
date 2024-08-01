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
### CODE 5:
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
### CODE 6:
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
### CODE 7:
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
        } while (j <= 5);
        cout << endl;
        ++i;
    } while (i <= 5);

    return 0;
}
```
### CODE 3:
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


