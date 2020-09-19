# Bug 1

1. **The incorrect original code or code snippit that you wrote:**

``` c++
#include <iostream>

using namespace std;

int main() {
    
    cout << "Hello, welcome to Jone's BBQ and Foot Massage" << endl;
    
    int amount_bbq {0};
    cout << "\nHow much bbq would you like? ";
    cin >> amount_bbq;
    
    int amount_massages {0};
    cout << "How many foot massage's would you like? ";
    cin >> amount_massages;
    
    const int  price_bbq {5.99};
    const int  price_per_massage {20.99};
    const int sales_tax {0.06};
   
    
    cout << "\nTotal" << endl;
    cout << "Number of barbeque: " << amount_bbq << endl;
    cout << "Number of massages: " << amount_massages << endl;
    
    cout << "Price per barbeque: $" << price_bbq << endl;
    cout << "Price per massages: $" << price_per_massage << endl;
    
    cout << "Cost : $" 
            << (price_bbq * amount_bbq) + 
                  (price_per_massage * amount_massages)
            << endl;
            
    cout << "Tax: $" 
            << ((price_bbq * amount_bbq) +
                   (price_per_massage * amount_massages)) * sales_tax
            << endl;
            
    cout << "===============================" << endl;
    cout << "Total estimate: $" 
        << ((price_bbq * amount_bbq) + (price_per_massage * amount_massages)) +
              (((price_bbq * amount_bbq) + (price_per_massage * amount_massages)) * sales_tax)
        << endl;
   
     
    cout << endl;
    return 0;
}

```

2. **What bug does the original code have?**
    
  Wrong use of data type

3. **What misunderstanding of C++ concepts lead you to this incorrect code?**


4. **How to correct the bug?**
    
    Apply the appropriate data type that can use decimals, apply the double precision data type
    
5. **The corresponding bug-free code or code snippet is:**

```c++
#include <iostream>

using namespace std;

int main() {
    
    cout << "Hello, welcome to Jone's BBQ and Foot Massage" << endl;
    
    int amount_bbq {0};
    cout << "\nHow much bbq would you like? ";
    cin >> amount_bbq;
    
    int amount_massages {0};
    cout << "How many foot massage's would you like? ";
    cin >> amount_massages;
    
    const double  price_bbq {5.99};
    const double  price_per_massage {20.99};
    const double sales_tax {0.06};
   
    
    cout << "\nTotal" << endl;
    cout << "Number of barbeque: " << amount_bbq << endl;
    cout << "Number of massages: " << amount_massages << endl;
    
    cout << "Price per barbeque: $" << price_bbq << endl;
    cout << "Price per massages: $" << price_per_massage << endl;
    
    cout << "Cost : $" 
            << (price_bbq * amount_bbq) + 
                  (price_per_massage * amount_massages)
            << endl;
            
    cout << "Tax: $" 
            << ((price_bbq * amount_bbq) +
                   (price_per_massage * amount_massages)) * sales_tax
            << endl;
            
    cout << "===============================" << endl;
    cout << "Total estimate: $" 
        << ((price_bbq * amount_bbq) + (price_per_massage * amount_massages)) +
              (((price_bbq * amount_bbq) + (price_per_massage * amount_massages)) * sales_tax)
        << endl;
   
     
    cout << endl;
    return 0;
}

```

6. **What is the take-away message from this bug?**

---

# Bug 2

1. **The incorrect original code or code snippit that you wrote:**

```
code with bugs or code snippet with bug goes here

```

2. **What bug does the original code have?**

  

3. **What misunderstanding of C++ concepts lead you to this incorrect code?**

4. **How to correct the bug?**

5. **The corresponding bug-free code or code snippet is:**

```
bug-free code or code snippet goes here

```

6. **What is the take-away message from this bug?**

---

# Bug 3

1. **The incorrect original code or code snippit that you wrote:**

```
code with bugs or code snippet with bug goes here

```

2. **What bug does the original code have?**

  

3. **What misunderstanding of C++ concepts lead you to this incorrect code?**

4. **How to correct the bug?**

5. **The corresponding bug-free code or code snippet is:**

```
bug-free code or code snippet goes here

```

6. **What is the take-away message from this bug?**
