# cmpt135-assignment-2-an-object-oriented-dynamic-string-array-solved
**TO GET THIS SOLUTION VISIT:** [CMPT135 Assignment 2-An Object-oriented Dynamic String Array Solved](https://www.ankitcodinghub.com/product/cmpt135-assignment-2-an-object-oriented-dynamic-string-array-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120266&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPT135  Assignment 2-An Object-oriented Dynamic String Array Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Your task is to use object-oriented programming to implement a vector-like class called str_vec. One of it’s major features is that it completely (and correctly!) manages its own memory, similar to a vector&lt;string&gt;.

Getting Started

Put all your code for this assignment into a2.cpp. Implement all the requested methods and functions using the exact name and parameters. You can add other helper functions/methods if you need them.

Write a test function to automatically test each major method/function to ensure it is correct. Use either if-statements or assertions for the testing. Each test function should have approximately 5 tests (more complex/input code should probably have more).

Questions

Implement each of the following methods and functions. Use const, public, and private whenever possible.

1. Implement a default constructor for str_vec() that creates a new str_vec of size 0 and capacity 10.

Example: cpp str_vec arr; // arr is an empty str_vec of size 0 and capacity 10

The capacity of str_vec is the size of its underlying array. The size is the number of items in the str_vec from the point of view of the user.

1. Implement a destructor ~str_vec() that deletes the dynamic memory used by the str_vec.

Be sure your program has no memory leaks by testing it with valgrind!

1. Implement a constructor str_vec(n, s) that creates a new str_vec of size n where each element is a copy of the string s. The capacity should be at least n. If n is less than 1, use cmpt::error to throw a helpful error message.

Example: cpp str_vec arr(5, “cat”); // arr is str_vec of size 5, each entry containing the string “cat”

1. Implement a copy constructor str_vec(other) that creates a new str_vec that is a copy of the str_vec other.

Example:

cpp str_vec a(5, “&lt;empty&gt;”); str_vec b(a); // b is a str_vec of size 5 with each entry equal to the string ”

&lt;empty&gt;”

The capacity of b should be at least the size of a.

Both a and b should have their own underlying array.

1. Implement an array constructor str_vec(arr, n) that creates a new str_vec that is a copy of the array of strings named arr, with size n. The type of arr in the constructor is const char*[].

Example:

cpp const char* arr[] = {“red”, “white”, “yellow”}; str_vec a(arr, 3); // 3 is the length of arr // a is a str_vec of size 3 with entires “red”, “white”, “yellow”

The passed-in array should not be changed in any way. a should have its own copy of arr.

1. Implement these getters:

2. size() and length(): both return the number of strings in the str_vec. Two methods are provided for returning the size as a convenience: length() is an alias for size().

3. capacity(): returns the capacity of the str_vec, i.e. the size of the underlying array.

4. pct_used(): returns the percentage (from 0.0 to 1.0) of the underlying array that is in use, i.e. the size divided by the capacity.

Make sure that these are all const methods!

Example:

“`cpp str_vec empty; cout &lt;&lt; empty.size() &lt;&lt; ‘ ‘ // 0 &lt;&lt; empty.capacity() &lt;&lt; ‘ ‘ // 10 &lt;&lt; empty.pct_used() &lt;&lt; ‘ ‘; // 0 “`

Write three test functions, one for each method.

1. Implement these non-mutating methods:

2. to_str(): returns a string representation of the str_vec. Each string should be printed in “-quotes, and wrapped in {}-braces as shown in the example below.

3. print(): a void method that prints the string representation of the str_vec to cout without a at the end. 4. println(): a void method that does the same thing as print(), but also prints a at the end

Make sure these are all const!

Example:

“`cpp str_vec arr(3, “cat”); string s = arr.to_str(); // s is the string {“cat”, “cat”, “cat”} arr.print(); // prints {“cat”, “cat”, “cat”} on cout (no at end) arr.println(); // prints {“cat”, “cat”, “cat”} on cout ( at end) “`

For this question you only need to make a test function for to_str(). For this assignment, it’s okay if you check the results of print and println manually.

1. Implement these methods:

2. get(i) is a getter that returns the string at index location i of the str_vec. Just as with arrays, the first index location is 0. Make sure this is const!

3. set(i, s) is a setter that sets index location i to be a copy of string s.

Both methods should do bounds checking: use cmpt::error to throw a helpful error message if the passed-in index i is less than 0, or greater than size() – 1.

Example:

“`cpp str_vec arr(3, “cat”); arr.set(1, “dog”); // arr is now {“cat”, “dog”, “cat”} string s1 = arr.get(1); // s1 is “dog” string s2 = arr.get(2); // s2 is “cat” “`

Write test functions for both set and get.

1. Implement these mutating methods:

2. append(s) is a void method that adds the string s to the right end (the back) of the str_vec, increasing the size by 1.

3. append(sv) is a void method that appends all the strings in the str_vec sv to the right end (the back) of the str_vec, increasing the size by the size of sv.

For both methods, the underlying capacity should only be increased if necessary. When the capacity is increased, it should be doubled.

Example:

“`cpp str_vec arr; // {} arr.append(“apple”); // {“apple”} arr.append(“orange”); // {“apple”, “orange”} str_vec fruit; // {} fruit.append(“pear”); // {“pear”} fruit.append(“banana”); // {“pear”, “banana”} arr.append(fruit); // {“apple”, “orange”, “pear”, “banana”} arr.append(arr); // {“apple”, “orange”, “pear”, “banana”, // “apple”, “orange”, “pear”, “banana”} “`

Write two test functions, once for each version of append.

1. Implement the void mutating method capitalize_all() that capitalizes all the strings in str_vec that can be capitalized. A string can be capitalized if it is not empty, and the first character is one of the 25 lowercase letters a to z. Strings that can’t be capitalized are left unchanged.

For example, if the str_vec a is {“hat”, ” dog”, “house boat”, “Wall”}, then after calling a.capitalize_all() it will be {“Hat”, ” dog”, “House boat”, “Wall”}.

This is a mutating method, so the str_vec itself should be changed (no copies made).

2. Implement the void mutating method remove_first(const string&amp; s) that removes the first occurrence of s in the str_vec. All the strings to the right are moved left one position to fill in the gap, and the size of the str_vec is decreased by 1. If s is not in the str_vec, then the str_vec is unchanged.

For example, if str_vec a is {“hat”, “shoe”, “hat”}, then after calling a.remove_first(“hat”), it will be {“shoe”, “hat”}.

3. Implement the void mutating method keep_all_starts_with(char c) that keeps only strings that start with c, and removes any others.

For example, if the str_vec a is {“hat”, “book”, “horse”, “house”, “Hot!”}, then after calling a.keep_all_starts_with(‘h’) it will be {“hat”, “horse”, “house”}.

The order of the strings after calling keep_all_starts_with should be the same as before calling it.

If none of the strings start with c, or the str_vec is empty, then then the str_vec is empty after calling keep_all_starts_with.

4. Implement these mutating methods:

clear() is a void method that removes all elements from the str_vec so its size is 0. Make this method as efficient as possible. The capacity can stay the same.

squish() is a void method that will, if necessary, re-size the underlying array so that the size and capacity are the same. The elements in the array are the same (and in the same order) after squishing as before.

Example:

“`cpp str_vec arr; // {}, size 0, capacity 10 arr.append(“a”); // {“a”}, size 1, capacity 10 arr.append(“b”); // {“a”, “b”}, size 2, capacity 10 arr.squish(); // {“a”, “b”}, size 2, capacity 2 arr.clear(); // {}, size 0, capacity 2 “`

Write test functions for both squish and clear.

5. Implement these functions (not methods!):

operator==(a, b) is a bool function that returns true if the str_vec a and the str_vec b have the same elements in the same order, and false otherwise

operator!=(a, b) is a bool function that returns true if the str_vec a and the str_vec b don’t have the same elements in the same order, and false otherwise

Example:

“`cpp str_vec a(3, “cat”); str_vec b(3, “cat”); if (a == b) cout &lt;&lt; “same “; // prints “same” if (a != b) cout &lt;&lt; “different “; // prints nothing a.set(0, “feline”); if (a == b) cout &lt;&lt; “same “; // prints nothing if (a != b) cout &lt;&lt; “different “; // prints “different” “`

Write test functions for both operator== and operator!=.

6. Implement a mutating method sort() that re-arranges the elements of a str_vec into alphabetical order.

For example:

“`cpp str_vec a; a.append(“hat”); a.append(“dog”); a.append(“cat”); a.append(“house”); cout &lt;&lt; a.to_str() // {“hat”, “dog”, “cat”, “house”} &lt;&lt; ” “; a.sort(); cout &lt;&lt; a.to_str() // {“cat”, “dog”, “hat”, “house”} &lt;&lt; ” “; “`

This is a mutating method, so the str_vec itself should be changed (no copies made).

Submit Your Work

Please put all your code into a2.cpp, and submit it on Canvas. Implement all the methods and functions exactly as described, otherwise the marking software will probably give you 0!

Submit only a2.cpp, and no other files. The marker will use the standard makefile to compile it, and a copy of cmpt_error.h will be in the same folder as a2.cpp when it’s tested.

Basic Requirements

It must compile on Ubuntu Linux using the standard course makefile:

$ make a2 g++ -std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g a2.cpp o a2

If your program fails to compile, your mark for this assignment will be 0.

A copy of cmpt_error.h will be in the same folder as a2.cpp when it’s compiled, so your program can use cmpt::error if necessary.

It must have no memory leaks or memory errors, according to valgrind, e.g.:

“` $ valgrind ./a2

// … lots of output … “`

A program is considered to have no memory error if:

In the LEAK SUMMARY, definitely lost, indirectly lost, and possibly lost must all be 0.

The ERROR SUMMARY reports 0 errors.

It is usually okay if still reachable reports a non- zero number of bytes.

You must include the large comment section with student info and the statement of originality. If your submitted file does not have this, then we will assume your work is not original and it will not be marked.

If your program meets all these basic requirements, then it will graded using the marking scheme on Canvas.

Hints

Marking Scheme

All code is sensibly and consistently indented, and all lines are 100 characters in length, or less.

Whitespace is used to group related pieces of a code to make it easier for humans to read. All whitespace should have a purpose.

Variable and function names are self-descriptive.

Appropriate features of C++ are used, as discussed in class and in the notes. Note If you use a feature that we haven’t discussed in class, you must explain it in a comment, even if you think it’s obvious.

Comments are used when needed to explain chunks of code whose purpose is not obvious from the code itself. There should be no commented-out code from previous versions.

No unnecessary work is done.

No unnecessary memory is used.

Source code correctness

A few of the questions have more than one function/method, and you should write a test function for each.

Deductions

a score of 0 if you don’t include the “statement of originality in the header of your file.
