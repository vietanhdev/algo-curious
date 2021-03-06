---
slug: /geometry/circle-circle-intersection
discussionId: /geometry/circle-circle-intersection
title: "Circle-Circle Intersection"
thumbnail: "/img/competitive-programming.svg"
date: 2021-10-27
toc: true
draft: false
math: true
categories: ["Competitive Programming"]
tags: ["Algorithms"]
---

You are given two circles on a 2D plane, each one described as coordinates of its center and its radius. Find the points of their intersection (possible cases: one or two points, no intersection or circles coincide).

## Solution

Let's reduce this problem to the [circle-line intersection problem](./geometry/circle-line-intersection).

Assume without loss of generality that the first circle is centered at the origin (if this is not true, we can move the origin to the center of the first circle and adjust the coordinates of intersection points accordingly at output time). We have a system of two equations:

$$x^2+y^2=r_1^2$$
$$(x - x_2)^2 + (y - y_2)^2 = r_2^2$$

Subtract the first equation from the second one to get rid of the second powers of variables:

$$x^2+y^2=r_1^2$$
$$x \cdot (-2x_2) + y \cdot (-2y_2) + (x_2^2+y_2^2+r_1^2-r_2^2) = 0$$

Thus, we've reduced the original problem to the problem of finding intersections of the first circle and a line:

$$Ax + By + C = 0$$
$$A = -2x_2$$
$$B = -2y_2$$
$$C = x_2^2+y_2^2+r_1^2-r_2^2$$

And this problem can be solved as described in the [corresponding article](./geometry/circle-line-intersection).

The only degenerate case we need to consider separately is when the centers of the circles coincide. In this case $x_2=y_2=0$, and the line equation will be $C = r_1^2-r_2^2 = 0$. If the radii of the circles are the same, there are infinitely many intersection points, if they differ, there are no intersections.

## Practice Problems

- [RadarFinder](https://community.topcoder.com/stat?c=problem_statement&pm=7766)

- [Runaway to a shadow - Codeforces Round #357](http://codeforces.com/problemset/problem/681/E)

- [ASC 1 Problem F "Get out!"](http://codeforces.com/gym/100199/problem/F)

- [SPOJ: CIRCINT](http://www.spoj.com/problems/CIRCINT/)

- [UVA - 10301 - Rings and Glue](https://uva.onlinejudge.org/index.php?option=onlinejudge&page=show_problem&problem=1242)

- [Codeforces 933C A Colorful Prospect](https://codeforces.com/problemset/problem/933/C)

- [TIMUS 1429 Biscuits](https://acm.timus.ru/problem.aspx?space=1&num=1429)
