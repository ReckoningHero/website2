---
layout: post
title: Basics and Advanced Knowledge of Binary Search in C++
featured-img: Slide3
mathjax: true

---
## Basic Knowledge of C++'s Binary Search
C++ offers the ability to demonstrate the search for algorithm that requires any particular array to be sorted out before any
search is applied from the user. What you learned in your introductory classes in college or maybe (hopefully) teach yourself is
the ability to understand how algorithm itself is sorted to find an item in an ordered list. The objective to demonstrate the algorithm
is to be able to discard half of the array within each iteration and leave the final value output of the code.

For example, we can take this example for instance:



```yaml
int array[] =
{
    1, 3, 4, 6, 7, 8, 10, 13, 14, 18, 19, 21, 24, 37, 40, 45, 71
};
```
Let’s say we are trying to find the index value of the number 7 in this array. There are 17 items in total and the index values go from 0 to 16.

We can see that the index value of 7 is 4, since it’s the fifth element in the array.

But what would be the best way for the computer to find the index value of the number we are looking for?

First, we store the min and max values, such as 0 and 16.

Now the search looks like this:

```
                      1, 3, 4, 6, 7, 8, 10, 13

min = 0
max = 7
guess = 3

```

Source Code:
```


#include <iostream>
using namespace std;

int main()

{
  int number_to_find = 7;
  int array[] = { 1, 3, 4, 6, 7, 8, 10, 13, 14, 18, 19, 21, 24, 37, 40, 45, 71 };
  int min = 0;
  int max = (sizeof(array) / sizeof(*array) - 1); // last index value
  int guess;

  while (min <= max)
  {
    guess = (int)(((max + min) / 2) + 0.5);
    if (number_to_find == array[guess])
      {
        cout << "The number is at index " << guess << endl;
        break;
      } else if (array[guess] < number_to_find) {
        min = guess + 1;
      } else {
        max = guess - 1;
      }
    cout << guess << endl;
  }

  return 0;
}

```


## Advanced Knowledge of C++'s Binary Search
In advanced learning with the C++ Standard Library. we use a particular sequence to partition the element of the array we are
looking for. When we set the parition() methond first and uses such algorithms like binary_search(), lower_bound(), upper_bound(), and
equal_range(). Thoese sorted sequences are vectors whose contents are sorted, map, multimap, set, and multiset.

For example, this algorithm demonstrates the binary_search() method to find a matching element in logarithmic time instead of linear
time. It laters requires a star and end iterator to specify the range, a value to search, and to callback a comparision optionally. It returns
a value of true if the value is set in the specified range, otherwise it can return a value of false.

```yaml

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

```
## References
---
[Professional C++ (3rd Edition) by Marc Gregoire]({{ "/assets/PDFs/Professional C++ (3rd Edition) by Marc Gregoire 2014 PDF.pdf" | absolute_url }})
