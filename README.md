# Awesome Algorithm Thinking [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources to build algorithmic thinking — for students, self-learners, and anyone who wants to think like a computer scientist.

Algorithmic thinking is not about memorizing code. It is about **breaking problems into steps, finding patterns, and building mental models** that work across math, physics, biology, and real engineering.

**Who this is for:** High school students with curiosity, anyone starting competitive programming, and people who want to understand how software actually works under the hood.

---

## Contents

- [Why Algorithm Thinking Matters](#why-algorithm-thinking-matters)
- [Visualizers — See Algorithms Move](#visualizers--see-algorithms-move)
- [Implementations — Read the Code](#implementations--read-the-code)
- [Learning Paths](#learning-paths)
- [Math Foundation](#math-foundation)
- [Practice Platforms](#practice-platforms)
- [Mind-Blowing Projects Built with Algorithms](#mind-blowing-projects-built-with-algorithms)
- [Books (Free)](#books-free)
- [For the Curious: Deep Rabbit Holes](#for-the-curious-deep-rabbit-holes)

---

## Why Algorithm Thinking Matters

Before diving in — here is why this matters beyond just "getting a job":

- A sorting algorithm is the same logic as ranking exam scores, ranking players, or sorting proteins by size
- Dijkstra's shortest path algorithm runs inside Google Maps, logistics systems, and game AI
- The math behind compression (zip files) is the same math behind JPEG images and MP3 audio
- Neural networks are just matrix multiplication — which is just high school linear algebra, repeated millions of times

Once you internalize a handful of core ideas, you start seeing them **everywhere**.

---

## Visualizers — See Algorithms Move

*The fastest way to understand an algorithm is to watch it run.*

- **[Algorithm Visualizer](https://github.com/algorithm-visualizer/algorithm-visualizer)** ⭐47,000 — Interactive visualizations of 50+ algorithms. Watch sorting, pathfinding, tree traversal — all animated step by step. [Live site](https://algorithm-visualizer.org)

- **[VisuAlgo](https://visualgo.net)** — University of Singapore's free visualizer. Covers data structures and algorithms with pseudocode highlighted as the animation runs. One of the best teaching tools on the internet.

- **[Data Structure Visualizations (USFCA)](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)** — Old-school but comprehensive. Every major data structure with step-by-step animation.

- **[Pathfinding Visualizer](https://github.com/clementmihailescu/Pathfinding-Visualizer)** ⭐6,000 — Draw walls on a grid and watch Dijkstra, A*, BFS, DFS find the shortest path in real time. Hypnotic.

- **[Sorting Visualizer](https://github.com/morwholly/sorting-visualizer)** — Bubble sort vs quicksort vs merge sort racing each other. After this, you will never forget why O(n²) is slow.

---

## Implementations — Read the Code

*Read real implementations in the language you know.*

- **[TheAlgorithms/Python](https://github.com/TheAlgorithms/Python)** ⭐230,000 — Every algorithm implemented in clean Python. Search trees, graph algorithms, dynamic programming, machine learning basics. The biggest algorithm repo on GitHub. Start here.

- **[TheAlgorithms/JavaScript](https://github.com/trekhleb/javascript-algorithms)** ⭐190,000 — Same scope as above but in JavaScript. Also includes complexity notes (Big O) for every algorithm.

- **[karpathy/micrograd](https://github.com/karpathy/micrograd)** ⭐10,000 — Andrej Karpathy (ex-Tesla AI) builds a neural network engine in **200 lines of Python**. Uses nothing but high school math (derivatives, the chain rule). Read this when you want to understand how AI actually works — not the hype, the math.

- **[nayuki/Project-Nayuki](https://github.com/nayuki/Project-Nayuki)** ⭐1,000 — A competitive programmer's personal collection. Implementations of 100+ algorithms with mathematical explanations. Dense but rewarding.

---

## Learning Paths

*Structured roads from zero to strong.*

- **[jwasham/coding-interview-university](https://github.com/jwasham/coding-interview-university)** ⭐310,000 — A software engineer spent 8 months following this self-made curriculum and got hired at Amazon. It maps out everything a CS degree covers — arrays, linked lists, trees, graphs, dynamic programming — with free resources for each topic. The most starred learning list on GitHub.

- **[ossu/computer-science](https://github.com/ossu/computer-science)** ⭐175,000 — A full open-source computer science degree, assembled from MIT, Stanford, and Berkeley courses. Algorithms section alone is worth bookmarking.

- **[Teach Yourself CS](https://teachyourselfcs.com)** — Nine subjects, nine best books, nine best video courses. Opinionated and excellent. Written by two Silicon Valley engineers.

- **[competitive-programming-library](https://github.com/cp-algorithms/cp-algorithms)** — E-Maxx Algorithms in English. The reference that competitive programmers worldwide use. Written for people who want to understand *why* algorithms work, not just copy them.

---

## Math Foundation

*Algorithms are applied math. Build the foundation and everything else clicks.*

- **[rossant/awesome-math](https://github.com/rossant/awesome-math)** ⭐8,000 — Curated list of free mathematics textbooks and lecture notes. Covers everything from basic algebra to topology, with quality ratings.

- **[3Blue1Brown — Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)** — 16 short videos that give you the visual intuition for matrices, vectors, and transformations. This is the most important math background for machine learning and graphics. Watch before touching NumPy.

- **[3Blue1Brown — Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)** — Builds the whole of calculus in one sitting using animations. If you think calculus is just memorizing formulas, this will change your mind.

- **[betaveros/noulith](https://github.com/betaveros/noulith)** — A programming language designed by a competitive math olympiad winner. Reading the source shows how math thinking translates directly to code.

---

## Practice Platforms

*You only build this skill by doing. Pick one and go.*

| Platform | Best For | Difficulty | Free? |
|---|---|---|---|
| [Project Euler](https://projecteuler.net) | Math + programming fusion | Medium–Hard | Yes |
| [LeetCode](https://leetcode.com) | Interview-style problems | Easy–Hard | Mostly |
| [Codeforces](https://codeforces.com) | Competitive programming | All levels | Yes |
| [USACO Guide](https://usaco.guide) | Structured competitive prog | Bronze–Platinum | Yes |
| [Advent of Code](https://adventofcode.com) | Puzzle-style, December yearly | Easy–Hard | Yes |

**For beginners:** Start with Project Euler problems 1–10. Each one teaches a concept (divisibility, Fibonacci, prime numbers) that is directly on the gaokao math syllabus.

**USACO** is the USA Computing Olympiad. The Bronze level is achievable for a dedicated high school student in 3–6 months. Many top university applicants in China now include USACO results in their portfolios.

---

## Mind-Blowing Projects Built with Algorithms

*These will make you say "I want to build something like that."*

- **[Shazam algorithm explained](https://github.com/worldveil/dejavu)** ⭐6,000 — Audio fingerprinting in Python. This is essentially how Shazam identifies songs. Uses Fast Fourier Transform (FFT) — which is on the university math syllabus, but now you can *do* something with it.

- **[maze generators](https://github.com/razimantv/mazegenerator)** — Generates perfect mazes using graph algorithms (DFS, BFS). See how a 30-line algorithm creates something that looks impossible to generate.

- **[Conway's Game of Life implementations](https://github.com/topics/game-of-life)** — Zero player game that produces complex emergent behavior from 4 rules. A classic entry point into computational thinking.

- **[minimax-chess](https://github.com/thomasahle/sunfish)** ⭐3,000 — A chess engine in 111 lines of Python. Uses the minimax algorithm — the same logic in every board game AI ever written. Read the whole thing in one afternoon.

- **[Huffman compression from scratch](https://github.com/drichardson/huffman)** — The algorithm inside every `.zip` file. Once you understand it, you will see why some files compress more than others.

---

## Books (Free)

- **[Open Data Structures](https://opendatastructures.org)** — Free textbook covering arrays, linked lists, heaps, hash tables, and trees. Implementations in Python, Java, and C++.

- **[Competitive Programmer's Handbook](https://cses.fi/book/book.pdf)** — 300-page PDF, free. Written by a Finnish ICPC medalist. The best single resource for competitive programming. Dense but worth it.

- **[Introduction to Algorithms (MIT OCW)](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/)** — MIT's full algorithm course with lecture videos, problem sets, and solutions. Free. This is what MIT freshmen take.

---

## For the Curious: Deep Rabbit Holes

*Warning: these will cost you hours of sleep.*

- **[P vs NP — explained simply](https://www.youtube.com/watch?v=YX40hbAHx3s)** — The most famous unsolved problem in computer science. A $1,000,000 prize awaits the solver. You can understand the question in 10 minutes with high school math.

- **[Primality testing](https://en.wikipedia.org/wiki/Miller%E2%80%93Rabin_primality_test)** — How do computers check if a 2048-digit number is prime? The answer involves modular arithmetic (which is on the competition math syllabus) and probability theory.

- **[Fast inverse square root](https://en.wikipedia.org/wiki/Fast_inverse_square_root)** — The famous hack from the Quake 3 source code. A bit manipulation trick that made 3D games run in 1999. 20 lines of C that changed game history.

- **[k-d tree](https://en.wikipedia.org/wiki/K-d_tree)** — The data structure behind "find the nearest restaurant." Used in GPS, robotics, and computer vision. Elegant once you see it.

---

## Contributing

Pull requests welcome. Keep it focused: resources must be free, high quality, and genuinely useful for someone building algorithmic thinking from scratch. Star counts are approximate and updated periodically.

---

## Related Lists

- [awesome-gaokao](https://github.com/daligao/awesome-gaokao) — Gaokao exam resources
- [awesome-diy-science](https://github.com/daligao/awesome-diy-science) — Virtual labs and science simulations
- [awesome-sci-fi](https://github.com/daligao/awesome-sci-fi) — Sci-fi and hacker culture reading list
- [gaokao-tools](https://github.com/daligao/gaokao-tools) — Anki decks, study tools, Python paths

---

*Built for a 16-year-old who keeps saying "I'm not a math person." You are. You just haven't seen the right angle yet.*
