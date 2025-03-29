# cpp-practice
practice programs to learn cpp
c++ programs

#include<iostream>
using namespace std;

   
 int main(){
     cout<<"i am satish"<<"\n"<<"student of opju";
     return 0;
 } // namespace name





#include <iostream>
using namespace std;

int main() {
    int age;
    cout << "enter age :";
    cin >> age;

    if (age <= 18) {
        cout << "you can vote\n";
    } else {
        cout << "you cant vote\n";
    }
    return 0;
}





#include <iostream>
using namespace std;

int main() {
    int x;
    cout << "enter number  :";
    cin >> x;

    if(x%2==0){
        cout << "number is even";

    } else{
        cout << "number is odd";
    }
}










#include <iostream>
using namespace std;

int main() {
    char ch;
    cout << "enter character";
    cin >> ch;
    
    if(ch >= 'a' && ch <= 'z'){
        cout << "lowercase";
    } else {
        cout << "uppercase";
    }

    return 0;
}




#include <iostream>
using namespace std;

int main()
{
     char ch;
    cout << "enter character";
    cin >> ch;
    
    if(ch >= 65 && ch <= 90){
        cout << "uppercase";
    } else {
        cout << "lowercase";
    }


    return 0;
}





#include <iostream>
using namespace std;

int main()
{
     int n = -5;
     
     cout << (n >= 0 ? "positive" : "negative") << endl;
     


    return 0;
}



loops



#include <iostream>
using namespace std;

int main()
{
     int count = 1;
     
     while(count <= 5) {
         cout << count;
         count++;
     }


#include <iostream>
using namespace std;

int main()
{
    int n = 5;
    for( int i = 1; i <= 5; i++){
        cout << i;
    }
     
         return 0;
}




#include <iostream>
using namespace std;

int main()
{
    int sum = 0;
    int n = 3;
    
    for( int i = 1; i <= n; i++){
        sum += i;
       }
       cout << "sum = " << sum << endl;
    
    return 0;
}



#include <iostream>
using namespace std;

int main() {
    int n;

    // Taking input from the user
    cout << "Enter a positive integer: ";
    cin >> n;

    cout << "Odd numbers from 1 to " << n << " are: ";

    // For loop to print odd numbers
    for (int i = 1; i <= n; i++) {
        if (i % 2 != 0) { // Check if the number is odd
            cout << i << " ";
        }
    }

    cout << endl;

    return 0;
}




#include <iostream>
using namespace std;

int main()
{
    int i = 1;
    int sum = 0;
    
    while(i <= 50){
        sum = sum +i;
        cout << "sum is: " << sum << endl;
        i++;
    }
    return 0;
}


or 


#include <iostream>
using namespace std;

int main() {
    int n, sum = 0, i = 1;

    // Taking input from the user
    cout << "Enter a positive integer: ";
    cin >> n;

    // While loop to calculate the sum
    while (i <= n) {
        sum += i;  // Adding the current number to sum
        i++;       // Incrementing the counter
    }

    // Displaying the result
    cout << "Sum of all numbers from 1 to " << n << " is: " << sum << endl;

    return 0;
}





