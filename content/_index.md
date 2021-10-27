---
title: "Competitive Programming - Lập trình thi đấu"
---

Giải thuật, cấu trúc dữ liệu cho competitive programming bằng tiếng Việt. Mục tiêu của dự án này là dịch nguồn tài liệu tuyệt vời **[cp-algorithms.com](https://cp-algorithms.com/)**, cung cấp các kiến thức về giải thuật và cấu trúc dữ liệu, đặc biệt dùng cho lĩnh vực lập trình thi đấu. Chúng tôi cũng sẽ bổ sung các kiến thức mới vào bộ sưu tập này. Trong lúc biên soạn lại, tôi sẽ bổ sung mã nguồn và giải các ví dụ để luyện tập.

Để cho tiện trong việc chỉnh sửa, các bài viết trong trang này đang được sao chép từ **cp-algorithms.com** và sẽ được dịch sang tiếng Việt theo thời gian. Tuy vậy, tôi không có nhiều thời gian dành cho dự án, nên có thể việc dịch thuật sẽ có chút chậm trễ. Nếu bạn muốn tham gia cũng tôi, vui lòng gửi cho tôi một tin nhắn thông qua **[trang liên hệ](/contact/)**.

**Các dự án với ngôn ngữ khác:**

- Tiếng Nga: <http://e-maxx.ru/algo/>.
- Tiếng Anh: <https://cp-algorithms.com/>.

**Bản quyền:** [Attribution-ShareAlike 4.0 International. Nhấp để mở](/cp/LICENSE).

## Đại số

- **Fundamentals**
    - [Binary Exponentiation](/algebra/binary-exp)
    - [Euclidean algorithm for computing the greatest common divisor](/algebra/euclid-algorithm)
    - [Extended Euclidean Algorithm](/algebra/extended-euclid-algorithm)
    - [Linear Diophantine Equations](/algebra/linear-diophantine-equation)
    - [Fibonacci Numbers](/algebra/fibonacci-numbers)
- **Prime numbers**
    - [Sieve of Eratosthenes](/algebra/sieve-of-eratosthenes)
    - [Sieve of Eratosthenes With Linear Time Complexity](/algebra/prime-sieve-linear)
    - [Primality tests](/algebra/primality-tests)
    - [Integer factorization](/algebra/factorization)
- **Number-theoretic functions**
    - [Euler's totient function](/algebra/phi-function)
    - [Number of divisors / sum of divisors](/algebra/divisors)
- **Modular arithmetic**
    - [Modular Inverse](/algebra/module-inverse)
    - [Linear Congruence Equation](/algebra/linear-congruence-equation)
    - [Chinese Remainder Theorem](/algebra/chinese-remainder-theorem)
    - [Factorial modulo $p$](/algebra/factorial-modulo)
    - [Discrete Log](/algebra/discrete-log)
    - [Primitive Root](/algebra/primitive-root)
    - [Discrete Root](/algebra/discrete-root)
    - [Montgomery Multiplication](/algebra/montgomery-multiplication)
- **Number systems**
    - [Balanced Ternary](/algebra/balanced-ternary)
    - [Gray code](/algebra/gray-code)
- **Miscellaneous**
    - [Enumerating submasks of a bitmask](/algebra/all-submasks)
    - [Arbitrary-Precision Arithmetic](/algebra/big-integer)
    - [Fast Fourier transform](/algebra/fft)
    - [Operations on polynomials and series](/algebra/polynomial)

## Cấu Trúc Dữ Liệu

- **Fundamentals**
    - [Minimum Stack / Minimum Queue](/data-structures/stack-queue-modification)
    - [Sparse Table](/data-structures/sparse-table)
- **Trees**
    - [Disjoint Set Union](/data-structures/disjoint-set-union)
    - [Fenwick Tree](/data-structures/fenwick)
    - [Sqrt Decomposition](/data-structures/sqrt-decomposition)
    - [Segment Tree](/data-structures/segment-tree)
    - [Treap](/data-structures/treap)
    - [Sqrt Tree](/data-structures/sqrt-tree)
    - [Randomized Heap](/data-structures/randomized-heap)
- **Advanced**
    - [Deleting from a data structure in O(T(n)log n)](/data-structures/deleting-in-log-n)

## Quy Hoạch Động

- **DP optimizations**
    - [Divide and Conquer DP](/dynamic-programming/divide-and-conquer-dp)
- **Tasks**
    - [Dynamic Programming on Broken Profile. Problem "Parquet"](/dynamic-programming/profile-dynamics)
    - [Finding the largest zero submatrix](/dynamic-programming/zero-matrix)

## Xử Lý Chuỗi

- **Fundamentals**
    - [String Hashing](/string/string-hashing)
    - [Rabin-Karp for String Matching](/string/rabin-karp)
    - [Prefix function - Knuth-Morris-Pratt](/string/prefix-function)
    - [Z-function](/string/z-function)
    - [Suffix Array](/string/suffix-array)
    - [Aho-Corasick algorithm](/string/aho-corasick)
- **Advanced**
    - [Suffix Tree](/string/suffix-tree-ukkonen)
    - [Suffix Automaton](/string/suffix-automaton)
    - [Lyndon factorization](/string/lyndon-factorization)
- **Tasks**
    - [Expression parsing](/string/expression-parsing)
    - [Manacher's Algorithm - Finding all sub-palindromes in O(N)](/string/manacher)
    - [Finding repetitions](/string/main-lorentz)

## Đại Số Tuyến Tính

- **Matrices**
    - [Gauss & System of Linear Equations](/linear-algebra/linear-system-gauss)
    - [Gauss & Determinant](/linear-algebra/determinant-gauss)
    - [Kraut & Determinant](/linear-algebra/determinant-kraut)
    - [Rank of a matrix](/linear-algebra/rank-matrix)

## Tổ Hợp

- **Fundamentals**
    - [Finding Power of Factorial Divisor](/algebra/factorial-divisors)
    - [Binomial Coefficients](/combinatorics/binomial-coefficients)
    - [Catalan Numbers](/combinatorics/catalan-numbers)
- **Techniques**
    - [The Inclusion-Exclusion Principle](/combinatorics/inclusion-exclusion)
    - [Burnside's lemma / Pólya enumeration theorem](/combinatorics/burnside)
    - [Stars and bars](/combinatorics/stars-and-bars)
    - [Generating all $K$-combinations](/combinatorics/generating-combinations)
- **Tasks**
    - [Placing Bishops on a Chessboard](/combinatorics/bishops-on-chessboard)
    - [Balanced bracket sequences](/combinatorics/bracket-sequences)
    - [Counting labeled graphs](/combinatorics/counting-labeled-graphs)

## Các Phương Pháp Số Học

- **Search**
    - [Ternary Search](/num-methods/ternary-search)
    - [Newton's method for finding roots](/num-methods/roots-newton)
- **Integration**
    - [Integration by Simpson's formula](/num-methods/simpson-integration)

## Hình Học

- **Elementary operations**
    - [Basic Geometry](/geometry/basic-geometry)
    - [Finding the equation of a line for a segment](/geometry/segment-to-line)
    - [Intersection Point of Lines](/geometry/lines-intersection)
    - [Check if two segments intersect](/geometry/check-segments-intersection)
    - [Intersection of Segments](/geometry/segments-intersection)
    - [Circle-Line Intersection](/geometry/circle-line-intersection)
    - [Circle-Circle Intersection](/geometry/circle-circle-intersection)
    - [Common tangents to two circles](/geometry/tangents-to-two-circles)
    - [Length of the union of segments](/geometry/length-of-segments-union)
- **Polygons**
    - [Oriented area of a triangle](/geometry/oriented-triangle-area)
    - [Area of simple polygon](/geometry/area-of-simple-polygon)
    - [Check if points belong to the convex polygon in O(log N)](/geometry/point-in-convex-polygon)
    - [Minkowski sum of convex polygons](/geometry/minkowski)
    - [Pick's Theorem - area of lattice polygons](/geometry/picks-theorem)
    - [Lattice points of non-lattice polygon](/geometry/lattice-points)
- **Convex hull**
    - [Convex hull construction](/geometry/convex-hull)
    - [Convex hull trick and Li Chao tree](/geometry/convex-hull-trick)
- **Sweep-line**
    - [Search for a pair of intersecting segments](/geometry/intersecting-segments)
    - [Point location in O(log N)](/geometry/point-location)
- **Miscellaneous**
    - [Finding the nearest pair of points](/geometry/nearest-points)
    - [Delaunay triangulation and Voronoi diagram](/geometry/delaunay)
    - [Vertical decomposition](/geometry/vertical-decomposition)
    - [Half-plane intersection - S&I Algorithm in O(Nlog N)](/geometry/halfplane-intersection)

## Đồ Thị

- **Graph traversal**
    - [Breadth First Search](/graph/breadth-first-search)
    - [Depth First Search](/graph/depth-first-search)
- **Connected components, bridges, articulations points**
    - [Finding Connected Components](/graph/search-for-connected-components)
    - [Finding Bridges in O(N+M)](/graph/bridge-searching)
    - [Finding Bridges Online](/graph/bridge-searching-online)
    - [Finding Articulation Points in O(N+M)](/graph/cutpoints)
    - [Strongly Connected Components and Condensation Graph](/graph/strongly-connected-components)
    - [Strong Orientation](/graph/strong-orientation)
- **Single-source shortest paths**
    - [Dijkstra - finding shortest paths from given vertex](/graph/dijkstra)
    - [Dijkstra on sparse graphs](/graph/dijkstra-sparse)
    - [Bellman-Ford - finding shortest paths with negative weights](/graph/bellman-ford)
    - [0-1 BFS](/graph/01-bfs)
    - [D´Esopo-Pape algorithm](/graph/desopo-pape)
- **All-pairs shortest paths**
    - [Floyd-Warshall - finding all shortest paths](/graph/all-pair-shortest-path-floyd-warshall)
    - [Number of paths of fixed length / Shortest paths of fixed length](/graph/fixed-length-paths)
- **Spanning trees**
    - [Minimum Spanning Tree - Prim's Algorithm](/graph/mst-prim)
    - [Minimum Spanning Tree - Kruskal](/graph/mst-kruskal)
    - [Minimum Spanning Tree - Kruskal with Disjoint Set Union](/graph/mst-kruskal-with-dsu)
    - [Second best Minimum Spanning Tree - Using Kruskal and Lowest Common Ancestor](/graph/second-best-mst)
    - [Kirchhoff Theorem](/graph/kirchhoff-theorem)
    - [Prüfer code](/graph/pruefer-code)
- **Cycles**
    - [Checking a graph for acyclicity and finding a cycle in O(M)](/graph/finding-cycle)
    - [Finding a Negative Cycle in the Graph](/graph/finding-negative-cycle-in-graph)
    - [Eulerian Path](/graph/euler-path)
- **Lowest common ancestor**
    - [Lowest Common Ancestor](/graph/lca)
    - [Lowest Common Ancestor - Binary Lifting](/graph/lca-binary-lifting)
    - [Lowest Common Ancestor - Farach-Colton and Bender algorithm](/graph/lca-farachcoltonbender)
    - [Solve RMQ by finding LCA](/graph/rmq-linear)
    - [Lowest Common Ancestor - Tarjan's off-line algorithm](/graph/lca-tarjan)
- **Flows and related problems**
    - [Maximum flow - Ford-Fulkerson and Edmonds-Karp](/graph/edmonds-karp)
    - [Maximum flow - Push-relabel algorithm](/graph/push-relabel)
    - [Maximum flow - Push-relabel algorithm improved](/graph/push-relabel-faster)
    - [Maximum flow - Dinic's algorithm](/graph/dinic)
    - [Maximum flow - MPM algorithm](/graph/mpm)
    - [Flows with demands](/graph/flow-with-demands)
    - [Minimum-cost flow](/graph/min-cost-flow)
    - [Assignment problem. Solution using min-cost-flow in O (N^5)](/graph/Assignment-problem-min-flow)
- **Matchings and related problems**
    - [Bipartite Graph Check](/graph/bipartite-check)
    - [Kuhn' Algorithm - Maximum Bipartite Matching](/graph/kuhn-maximum-bipartite-matching)
- **Miscellaneous**
    - [Topological Sorting](/graph/topological-sort)
    - [Edge connectivity / Vertex connectivity](/graph/edge-vertex-connectivity)
    - [Tree painting](/graph/tree-painting)
    - [2-SAT](/graph/2sat)
    - [Heavy-light decomposition](/graph/hld)

## Các Lĩnh Vực Khác

- **Sequences**
    - [RMQ task (Range Minimum Query - the smallest element in an interval)](/sequences/rmq)
    - [Longest increasing subsequence](/sequences/longest-increasing-subsequence)
    - [Search the subsegment with the maximum/minimum sum](/others/maximum-average-segment)
    - [K-th order statistic in O(N)](/sequences/k-th)
- **Game Theory**
    - [Games on arbitrary graphs](/game-theory/games-on-graphs)
    - [Sprague-Grundy theorem. Nim](/game-theory/sprague-grundy-nim)
- **Schedules**
    - [Scheduling jobs on one machine](/schedules/schedule-one-machine)
    - [Scheduling jobs on two machines](/schedules/schedule-two-machines)
    - [Optimal schedule of jobs given their deadlines and durations](/schedules/schedule-with-completion-duration)
- **Miscellaneous**
    - [Josephus problem](/others/josephus-problem)
    - [15 Puzzle Game: Existence Of The Solution](/others/15-puzzle)
    - [The Stern-Brocot Tree and Farey Sequences](/others/stern-brocot-tree-farey-sequences)


<style>
main > .content > div > ul {
    list-style: disc;
    margin-left: 2rem;
}
main > .content > div > ul li ul li {
    list-style: decimal;
    margin-left: 2rem;
}
</style>
