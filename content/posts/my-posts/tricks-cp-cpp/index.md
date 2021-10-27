---
title: "Tricks for competitive programming C++"
discussionId: "/tricks-cp-cpp/"
thumbnail: "/img/competitive-programming.svg"
date: 2021-10-04
toc: true
draft: false
math: true
slug: "/tricks-cp-cpp/"
categories: ["Competitive Programming"]
tags: ["Tricks"]
description: "Must-Known tricks for competitive programming in C++. Solve problems quickly and correctly." 
---

This post introduce some tricks used in competitive programming to optimize writting and execution speed. **Warning:** This may not be the best practices for clean and efficient code in a real project.

## 1. Speed up writing code 

### A single header for a lot of things

```cpp
#include <bits/stdc++.h>
```

This header line contains `algorithm`, `iostream`, `vector`, ... to save time writing include code.

### *auto* keyword

`auto` may save a lot of time writing code (C++11).

```cpp
auto a = 1 + 2;  // type of a is int
auto d = {1, 2}; // type of d is std::initializer_list<int>
auto n = {5};    // type of n is std::initializer_list<int>
```

### Range-based for loop

Traditional iteration loop:

```cpp
vector<int> s = {1, 2, 3, 4, 5};  

// Traverse and print
for (vector<int>::iterator it = s.begin(); it != s.end(); ++it)
    cout << *it << ' ';

// Another way
for (size_t i = 0; i < s.size(); ++i) {
    cout << s[i] << ' ';
}
```

C++11 range-based style:

```cpp
for (auto it: s)
    cout << it << ' ';
```

### Shorten types and functions with typedef and #define

Use `typedef` for short type names

```cpp
typedef long long ll;
typedef pair pp;
typedef vector vec;
```

Define short function names

```cpp
#define pb push_back;
#define mp make_pair;
```

## 2. Use convenient built-in functions

- GCD function: `__gcd(x, y);`.
- Sort: `sort(startaddress, endaddress)`. Example: `sort(vec.begin(), vec.end());`.
- Set memory by memset: `int a[5][5]; memset(a, 0, sizeof(a));`.
- `all_of`, `any_of`, `none_of`:

```cpp
all_of(ar, ar+6, [](int x) { return x>0; })
```

- Copy with `copy_n`:

```cpp
int source[5] = {1, 2, 3, 4, 5};
int target[5];
copy_n(source, 5, target);
```