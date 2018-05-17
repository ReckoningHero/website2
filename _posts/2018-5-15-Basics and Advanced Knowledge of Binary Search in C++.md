---
layout: post
title: Basics and Advanced Knowledge of Binary Search in C++
featured-img: Data_Structure

---
C++ offers the ability to demonstrate the search for algorithm that requires any pariticular array to be sorted out before any 
search is applied from the user. What you learned in your introductory classes in college or maybe (hopefully) teach yourself is 
the ability to understand how algorithm itself is sorted to find an item in an ordered list. The objective to demostrate the algorithm 
is to be able to discard half of the array within each iterationand leave the final value output of the code. 

For example, we can take this example for instance:


```yaml

---
int array[] = 
{ 
    1, 3, 5, 6, 7, 8, 10, 12, 14, 17, 19, 21, 23, 34, 40, 45, 71, 100 
};
---







In advanced learning with the C++ Standard Library. we used a particular sequence to partition the element of the array we are 
looking for. When we set the parition() methond first and uses such algorithms like binary_search(), lower_bound(), upper_bound(), and
equal_range(). Thoese sorted sequences are vectors whose contents are sorted, map, multimap, set, and multiset.

For example, this algorithm demonstrates the binary_search() method to find a matching element in logarithmic time instead of linear
time. It laters requies a star and end iterator to specify the range, a value to seach, and to callback a comparision opionally. It returns
a value of true if the value is set in the specified range, otherwise it can return a value of false.

```yaml

---
    vector<int> vec;
    cout << "Enter values:" << endl;
    populateContainer(vec);
    // Sort the container
    sort(begin(vec), end(vec));
    while (true) 
    {
        int num;
        cout << "Enter a number to find (0 to quit): ";
        cin >> num;
        if (num == 0) 
        {
            break;
        }
        if (binary_search(cbegin(vec), cend(vec), num)) 
        {
        cout << "That number is in the vector." << endl;

        }   
        else 
        {
            cout << "That number is not in the vector." << endl;
        }
    }
---

```
