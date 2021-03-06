---
slug: /geometry/area-of-simple-polygon
discussionId: /geometry/area-of-simple-polygon
title: "Finding area of simple polygon in O(N)"
thumbnail: "/img/competitive-programming.svg"
date: 2021-10-27
toc: true
draft: false
math: true
categories: ["Competitive Programming"]
tags: ["Algorithms"]
---

Let a simple polygon (i.e. without self intersection, not necessarily convex) be given. It is required to calculate its area given its vertices.

## Method 1

This is easy to do if we go through all edges and add trapezoid areas bounded by each edge and x-axis. The area needs to be taken with sign so that the extra area will be reduced. Hence, the formula is as follows:

$$A = \sum_{(p,q)\in \text{edges}} \frac{(p_x - q_x) \cdot (p_y + q_y)}{2}$$

Code:

```cpp
double area(const vector<point>& fig) {
    double res = 0;
    for (unsigned i = 0; i < fig.size(); i++) {
        point p = i ? fig[i - 1] : fig.back();
        point q = fig[i];
        res += (p.x - q.x) * (p.y + q.y);
    }
    return fabs(res) / 2;
}
```

## Method 2
We can choose a point $O$ arbitrarily, iterate over all edges adding the oriented area of the triangle formed by the edge and point $O$. Again, due to the sign of area, extra area will be reduced.

This method is better as it can be generalized to more complex cases (such as when some sides are arcs instead of straight lines)
