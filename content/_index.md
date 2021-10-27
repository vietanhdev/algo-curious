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
    - [Binary Exponentiation](/posts/algebra/binary-exp)
    - [Euclidean algorithm for computing the greatest common divisor](/posts/algebra/euclid-algorithm)
    - [Extended Euclidean Algorithm](/posts/algebra/extended-euclid-algorithm)
    - [Linear Diophantine Equations](/posts/algebra/linear-diophantine-equation)
    - [Fibonacci Numbers](/posts/algebra/fibonacci-numbers)
- **Prime numbers**
    - [Sieve of Eratosthenes](/posts/algebra/sieve-of-eratosthenes)
    - [Sieve of Eratosthenes With Linear Time Complexity](/posts/algebra/prime-sieve-linear)
    - [Primality tests](/posts/algebra/primality-tests)
    - [Integer factorization](/posts/algebra/factorization)
- **Number-theoretic functions**
    - [Euler's totient function](/posts/algebra/phi-function)
    - [Number of divisors / sum of divisors](/posts/algebra/divisors)
- **Modular arithmetic**
    - [Modular Inverse](/posts/algebra/module-inverse)
    - [Linear Congruence Equation](/posts/algebra/linear-congruence-equation)
    - [Chinese Remainder Theorem](/posts/algebra/chinese-remainder-theorem)
    - [Factorial modulo $p$](/posts/algebra/factorial-modulo)
    - [Discrete Log](/posts/algebra/discrete-log)
    - [Primitive Root](/posts/algebra/primitive-root)
    - [Discrete Root](/posts/algebra/discrete-root)
    - [Montgomery Multiplication](/posts/algebra/montgomery-multiplication)
- **Number systems**
    - [Balanced Ternary](/posts/algebra/balanced-ternary)
    - [Gray code](/posts/algebra/gray-code)
- **Miscellaneous**
    - [Enumerating submasks of a bitmask](/posts/algebra/all-submasks)
    - [Arbitrary-Precision Arithmetic](/posts/algebra/big-integer)
    - [Fast Fourier transform](/posts/algebra/fft)
    - [Operations on polynomials and series](/posts/algebra/polynomial)

## Cấu Trúc Dữ Liệu

- **Fundamentals**
    - [Minimum Stack / Minimum Queue](/posts/data-structures/stack-queue-modification)
    - [Sparse Table](/posts/data-structures/sparse-table)
- **Trees**
    - [Disjoint Set Union](/posts/data-structures/disjoint-set-union)
    - [Fenwick Tree](/posts/data-structures/fenwick)
    - [Sqrt Decomposition](/posts/data-structures/sqrt-decomposition)
    - [Segment Tree](/posts/data-structures/segment-tree)
    - [Treap](/posts/data-structures/treap)
    - [Sqrt Tree](/posts/data-structures/sqrt-tree)
    - [Randomized Heap](/posts/data-structures/randomized-heap)
- **Advanced**
    - [Deleting from a data structure in O(T(n)log n)](/posts/data-structures/deleting-in-log-n)

## Quy Hoạch Động

- **DP optimizations**
    - [Divide and Conquer DP](/posts/dynamic-programming/divide-and-conquer-dp)
- **Tasks**
    - [Dynamic Programming on Broken Profile. Problem "Parquet"](/posts/dynamic-programming/profile-dynamics)
    - [Finding the largest zero submatrix](/posts/dynamic-programming/zero-matrix)

## Xử Lý Chuỗi

- **Fundamentals**
    - [String Hashing](/posts/string/string-hashing)
    - [Rabin-Karp for String Matching](/posts/string/rabin-karp)
    - [Prefix function - Knuth-Morris-Pratt](/posts/string/prefix-function)
    - [Z-function](/posts/string/z-function)
    - [Suffix Array](/posts/string/suffix-array)
    - [Aho-Corasick algorithm](/posts/string/aho-corasick)
- **Advanced**
    - [Suffix Tree](/posts/string/suffix-tree-ukkonen)
    - [Suffix Automaton](/posts/string/suffix-automaton)
    - [Lyndon factorization](/posts/string/lyndon-factorization)
- **Tasks**
    - [Expression parsing](/posts/string/expression-parsing)
    - [Manacher's Algorithm - Finding all sub-palindromes in O(N)](/posts/string/manacher)
    - [Finding repetitions](/posts/string/main-lorentz)

## Đại Số Tuyến Tính

- **Matrices**
    - [Gauss & System of Linear Equations](/posts/linear-algebra/linear-system-gauss)
    - [Gauss & Determinant](/posts/linear-algebra/determinant-gauss)
    - [Kraut & Determinant](/posts/linear-algebra/determinant-kraut)
    - [Rank of a matrix](/posts/linear-algebra/rank-matrix)

## Tổ Hợp

- **Fundamentals**
    - [Finding Power of Factorial Divisor](/posts/algebra/factorial-divisors)
    - [Binomial Coefficients](/posts/combinatorics/binomial-coefficients)
    - [Catalan Numbers](/posts/combinatorics/catalan-numbers)
- **Techniques**
    - [The Inclusion-Exclusion Principle](/posts/combinatorics/inclusion-exclusion)
    - [Burnside's lemma / Pólya enumeration theorem](/posts/combinatorics/burnside)
    - [Stars and bars](/posts/combinatorics/stars-and-bars)
    - [Generating all $K$-combinations](/posts/combinatorics/generating-combinations)
- **Tasks**
    - [Placing Bishops on a Chessboard](/posts/combinatorics/bishops-on-chessboard)
    - [Balanced bracket sequences](/posts/combinatorics/bracket-sequences)
    - [Counting labeled graphs](/posts/combinatorics/counting-labeled-graphs)

## Các Phương Pháp Số Học

- **Search**
    - [Ternary Search](/posts/num-methods/ternary-search)
    - [Newton's method for finding roots](/posts/num-methods/roots-newton)
- **Integration**
    - [Integration by Simpson's formula](/posts/num-methods/simpson-integration)

## Hình Học

- **Elementary operations**
    - [Basic Geometry](/posts/geometry/basic-geometry)
    - [Finding the equation of a line for a segment](/posts/geometry/segment-to-line)
    - [Intersection Point of Lines](/posts/geometry/lines-intersection)
    - [Check if two segments intersect](/posts/geometry/check-segments-intersection)
    - [Intersection of Segments](/posts/geometry/segments-intersection)
    - [Circle-Line Intersection](/posts/geometry/circle-line-intersection)
    - [Circle-Circle Intersection](/posts/geometry/circle-circle-intersection)
    - [Common tangents to two circles](/posts/geometry/tangents-to-two-circles)
    - [Length of the union of segments](/posts/geometry/length-of-segments-union)
- **Polygons**
    - [Oriented area of a triangle](/posts/geometry/oriented-triangle-area)
    - [Area of simple polygon](/posts/geometry/area-of-simple-polygon)
    - [Check if points belong to the convex polygon in O(log N)](/posts/geometry/point-in-convex-polygon)
    - [Minkowski sum of convex polygons](/posts/geometry/minkowski)
    - [Pick's Theorem - area of lattice polygons](/posts/geometry/picks-theorem)
    - [Lattice points of non-lattice polygon](/posts/geometry/lattice-points)
- **Convex hull**
    - [Convex hull construction](/posts/geometry/convex-hull)
    - [Convex hull trick and Li Chao tree](/posts/geometry/convex-hull-trick)
- **Sweep-line**
    - [Search for a pair of intersecting segments](/posts/geometry/intersecting-segments)
    - [Point location in O(log N)](/posts/geometry/point-location)
- **Miscellaneous**
    - [Finding the nearest pair of points](/posts/geometry/nearest-points)
    - [Delaunay triangulation and Voronoi diagram](/posts/geometry/delaunay)
    - [Vertical decomposition](/posts/geometry/vertical-decomposition)
    - [Half-plane intersection - S&I Algorithm in O(Nlog N)](/posts/geometry/halfplane-intersection)

## Đồ Thị

- **Graph traversal**
    - [Breadth First Search](/posts/graph/breadth-first-search)
    - [Depth First Search](/posts/graph/depth-first-search)
- **Connected components, bridges, articulations points**
    - [Finding Connected Components](/posts/graph/search-for-connected-components)
    - [Finding Bridges in O(N+M)](/posts/graph/bridge-searching)
    - [Finding Bridges Online](/posts/graph/bridge-searching-online)
    - [Finding Articulation Points in O(N+M)](/posts/graph/cutpoints)
    - [Strongly Connected Components and Condensation Graph](/posts/graph/strongly-connected-components)
    - [Strong Orientation](/posts/graph/strong-orientation)
- **Single-source shortest paths**
    - [Dijkstra - finding shortest paths from given vertex](/posts/graph/dijkstra)
    - [Dijkstra on sparse graphs](/posts/graph/dijkstra-sparse)
    - [Bellman-Ford - finding shortest paths with negative weights](/posts/graph/bellman-ford)
    - [0-1 BFS](/posts/graph/01-bfs)
    - [D´Esopo-Pape algorithm](/posts/graph/desopo-pape)
- **All-pairs shortest paths**
    - [Floyd-Warshall - finding all shortest paths](/posts/graph/all-pair-shortest-path-floyd-warshall)
    - [Number of paths of fixed length / Shortest paths of fixed length](/posts/graph/fixed-length-paths)
- **Spanning trees**
    - [Minimum Spanning Tree - Prim's Algorithm](/posts/graph/mst-prim)
    - [Minimum Spanning Tree - Kruskal](/posts/graph/mst-kruskal)
    - [Minimum Spanning Tree - Kruskal with Disjoint Set Union](/posts/graph/mst-kruskal-with-dsu)
    - [Second best Minimum Spanning Tree - Using Kruskal and Lowest Common Ancestor](/posts/graph/second-best-mst)
    - [Kirchhoff Theorem](/posts/graph/kirchhoff-theorem)
    - [Prüfer code](/posts/graph/pruefer-code)
- **Cycles**
    - [Checking a graph for acyclicity and finding a cycle in O(M)](/posts/graph/finding-cycle)
    - [Finding a Negative Cycle in the Graph](/posts/graph/finding-negative-cycle-in-graph)
    - [Eulerian Path](/posts/graph/euler-path)
- **Lowest common ancestor**
    - [Lowest Common Ancestor](/posts/graph/lca)
    - [Lowest Common Ancestor - Binary Lifting](/posts/graph/lca-binary-lifting)
    - [Lowest Common Ancestor - Farach-Colton and Bender algorithm](/posts/graph/lca-farachcoltonbender)
    - [Solve RMQ by finding LCA](/posts/graph/rmq-linear)
    - [Lowest Common Ancestor - Tarjan's off-line algorithm](/posts/graph/lca-tarjan)
- **Flows and related problems**
    - [Maximum flow - Ford-Fulkerson and Edmonds-Karp](/posts/graph/edmonds-karp)
    - [Maximum flow - Push-relabel algorithm](/posts/graph/push-relabel)
    - [Maximum flow - Push-relabel algorithm improved](/posts/graph/push-relabel-faster)
    - [Maximum flow - Dinic's algorithm](/posts/graph/dinic)
    - [Maximum flow - MPM algorithm](/posts/graph/mpm)
    - [Flows with demands](/posts/graph/flow-with-demands)
    - [Minimum-cost flow](/posts/graph/min-cost-flow)
    - [Assignment problem. Solution using min-cost-flow in O (N^5)](/posts/graph/Assignment-problem-min-flow)
- **Matchings and related problems**
    - [Bipartite Graph Check](/posts/graph/bipartite-check)
    - [Kuhn' Algorithm - Maximum Bipartite Matching](/posts/graph/kuhn-maximum-bipartite-matching)
- **Miscellaneous**
    - [Topological Sorting](/posts/graph/topological-sort)
    - [Edge connectivity / Vertex connectivity](/posts/graph/edge-vertex-connectivity)
    - [Tree painting](/posts/graph/tree-painting)
    - [2-SAT](/posts/graph/2sat)
    - [Heavy-light decomposition](/posts/graph/hld)

## Các Lĩnh Vực Khác

- **Sequences**
    - [RMQ task (Range Minimum Query - the smallest element in an interval)](/posts/sequences/rmq)
    - [Longest increasing subsequence](/posts/sequences/longest-increasing-subsequence)
    - [Search the subsegment with the maximum/minimum sum](/posts/others/maximum-average-segment)
    - [K-th order statistic in O(N)](/posts/sequences/k-th)
- **Game Theory**
    - [Games on arbitrary graphs](/posts/game-theory/games-on-graphs)
    - [Sprague-Grundy theorem. Nim](/posts/game-theory/sprague-grundy-nim)
- **Schedules**
    - [Scheduling jobs on one machine](/posts/schedules/schedule-one-machine)
    - [Scheduling jobs on two machines](/posts/schedules/schedule-two-machines)
    - [Optimal schedule of jobs given their deadlines and durations](/posts/schedules/schedule-with-completion-duration)
- **Miscellaneous**
    - [Josephus problem](/posts/others/josephus-problem)
    - [15 Puzzle Game: Existence Of The Solution](/posts/others/15-puzzle)
    - [The Stern-Brocot Tree and Farey Sequences](/posts/others/stern-brocot-tree-farey-sequences)


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
