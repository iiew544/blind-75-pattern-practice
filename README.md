# Blind 75: What's Really on the List, the Order That Works, and Where Pattern Practice Fits

Most people meet Blind 75 the same way. You decide to prep properly, open the list, and find 75 problem titles with no instructions attached. Which ones actually matter? Why are some locked behind LeetCode Premium? Do you go top to bottom, or topic by topic? Nobody says, so you start at problem one, feel productive for four days, and stall somewhere around Word Search II.

The list isn't the problem. It's a genuinely good filter. What's missing is everything around it — the order, the pattern behind each problem, and a way to tell whether you're actually improving or just accumulating green checkmarks.

## Where Blind 75 came from

Yangshun Tay, an engineer who worked at Facebook, put a post on Blind titled something like "New Year Gift — Curated List of Top 75 LeetCode Questions." The idea was simple: instead of grinding hundreds of problems, pick the ones that cover the interview fundamentals. Someone reposted it to the LeetCode discussion forums, it caught on, and the community eventually named it after the site where it started.

He later distilled it further into a 50-question version laid out across a five-week schedule, and built Grind 75, which is the same philosophy with adjustable size (75 to 100+ questions) and a timeline you can configure. Both live in the Tech Interview Handbook. That history matters for one practical reason: the original list was never meant to be a curriculum. It was a shortlist, built by someone who wanted to stop wasting time — and it assumes you already know how to study.

## What the 75 problems cover

The list spans ten categories. Here's the actual distribution, which is worth looking at before you plan anything:

| Category | Problems | Examples |
| --- | --- | --- |
| Tree | 14 | Maximum Depth of Binary Tree, Validate BST, Implement Trie |
| Dynamic Programming | 11 | Climbing Stairs, Coin Change, Word Break, House Robber |
| Array | 10 | Two Sum, Product of Array Except Self, 3Sum, Maximum Subarray |
| String | 10 | Longest Substring Without Repeating Characters, Valid Parentheses |
| Graph | 8 | Number of Islands, Course Schedule, Clone Graph |
| Linked List | 6 | Reverse Linked List, Merge k Sorted Lists, Reorder List |
| Binary | 5 | Number of 1 Bits, Counting Bits, Reverse Bits, Missing Number |
| Interval | 5 | Merge Intervals, Insert Interval, Meeting Rooms |
| Matrix | 4 | Set Matrix Zeroes, Spiral Matrix, Rotate Image, Word Search |
| Heap | 2 | Top K Frequent Elements, Find Median from Data Stream |

Two things jump out. Trees plus DP alone are 25 of the 75 problems — a third of the list. And the "Binary" category isn't binary search at all; it's bit manipulation, which surprises people who expected rotated-array practice there. Binary search shows up inside the Array bucket instead, as Find Minimum in Rotated Sorted Array and Search in Rotated Sorted Array.

## The part nobody mentions: six of the 75 are paywalled

Count the problems on LeetCode's community "Blind Curated 75" list and you'll get 74 entries, not 75. Try a different community copy and you might see 70. That's not sloppiness — some of the original problems are LeetCode Premium exclusives. Specifically:

- Alien Dictionary

- Graph Valid Tree

- Number of Connected Components in an Undirected Graph

- Meeting Rooms

- Meeting Rooms II

- Encode and Decode Strings

Six problems, all in Graph, Interval, or String. If you're working through Blind 75 without Premium, you'll hit a wall at some point and either pay $159/year or hunt for the problem statement elsewhere. There are free mirrors and third-party versions of each, but the point stands: the list quietly assumes a Premium subscription it never tells you about.

> Worth knowing: the original 75 were selected for topic coverage, not for how often a specific company asked them. The "these exact problems get asked at FAANG" framing came later, from people repeating the list.

## A sequence that actually holds up

Blind 75 has no required order, which is both its freedom and its trap. Solving by category beats solving in list order, because pattern recognition is built by doing three similar problems back to back, not by alternating between a linked list and a bit trick.

A structure that tends to work:

1. **Weeks 1–2: Array, String, Linked List.** The highest-frequency, lowest-abstract category. Two Sum, Valid Anagram, Contains Duplicate, Best Time to Buy and Sell Stock, then sliding window and two pointers. This is where you build the reflexes everything else depends on.

2. **Weeks 3–4: Tree, Heap, Matrix.** Trees are the largest block in the list. Do the traversals first (Maximum Depth, Same Tree, Invert Binary Tree, Level Order Traversal), then BST validation and Kth Smallest, then the hard ones like Serialize and Deserialize.

3. **Weeks 5–6: Graph, Interval, Binary.** Graphs are where most people's confidence breaks. Do Number of Islands and Clone Graph before Course Schedule, and leave Alien Dictionary until you've done topological sort at least twice.

4. **Weeks 7–8: Dynamic Programming, then a full pass back through your failures.** DP is 11 problems and it is genuinely the slowest category to internalize. Climbing Stairs, House Robber, and Coin Change give you the 1D shape; Longest Common Subsequence and Word Break give you the 2D and string-based variants.

Do the arithmetic before you commit: 75 problems at roughly 30–45 minutes each, including reading the editorial and re-implementing without hints, is somewhere between 40 and 55 hours of real work. At an hour a day that's about two months. The list is not a weekend project, and anyone who tells you it is has skipped the part where they re-solved the hard ones from scratch.

The single highest-value habit: after each problem, write one sentence about which pattern it was and how you'd recognize it next time. Blind 75 problems are variations on a small number of techniques. If you can name the technique from the problem description, you've extracted the value. If you only remember the code, you've memorized 75 answers that won't survive the first interviewer follow-up question.

## Where pattern-based practice fits in

This is the gap a list can't fill on its own. Knowing that Blind 75 contains 11 DP problems doesn't tell you which of the five DP shapes each one needs, and that decision is exactly what an interview is testing.

AlgoMonster is built around that layer rather than around problem volume. It's a patform created by ex-Google engineers, and the curriculum is organized by coding pattern — sliding window, binary search, BFS/DFS, dynamic programming — with each pattern getting a template, an explanation, and a practice ladder rather than a single solution. Third-party write-ups consistently count 48 patterns in the library. There's also an explicit Blind 75 practice list alongside AlgoMonster's own Monster 50, so you can run the familiar problems while being pushed to name the pattern and complexity before writing code.

What's on the paid plan, per the current subscribe page:

- All patterns, lessons, and problems unlocked

- Unlimited Speedrun, the timed drilling mode

- Unlimited AI assistant usage

- Real questions from major tech companies, refreshed monthly

- 500+ lessons across six courses, with roughly 1,000 illustrations and 3,000+ editorials

- Member discount on live bootcamps

- Bonus courses included at no extra cost: a Foundation course for CS fundamentals and a Build an LLM course covering tokenization, attention, and training

A few honest limitations. The content is text and diagrams, not video, so if you learn from watching someone type, this isn't the format for you. The problem count is in the hundreds, not thousands — it's a curated set, not a bank. And system design coverage is introductory; if you're interviewing at L5 or above with a dedicated design round, you'll need something else for that portion. Note also that partner-built courses like Quant Interview Prep are sold separately.

AlgoMonster also seems to run aggressive seasonal promotions. The subscribe page has shown Pro Yearly at $198 list with 50% off, and the same for lifetime at $378 list. Which brings us to the part people actually ask about.

## AlgoMonster pricing: every current plan

| Plan | What you get | Price | Billing | Get it |
| --- | --- | --- | --- | --- |
| Free | Limited access to a subset of patterns, lessons, and the practice tool | $0 | — | [Start on the free plan](https://algo.monster?fpr=li69) |
| Pro — Yearly | All patterns, lessons and problems, unlimited Speedrun and AI assistant, monthly-updated company questions, 12 months of access, bonus Foundation and Build an LLM courses | $99/year ($8.25/mo) at current promotional pricing; list $198 | Billed annually, cancel or upgrade anytime | [Check the yearly plan price](https://algo.monster?fpr=li69) |
| Pro — Lifetime | Everything in Yearly plus lifetime updates and an internal referral to a top tech company for qualified candidates | $189 one-time at current promotional pricing; list $378 | One-time payment | [See lifetime access](https://algo.monster?fpr=li69) |

Two caveats worth stating plainly. There's no monthly plan — it's annual or lifetime, no month-to-month billing. And those discounted prices move with whatever promotion is running, so the number you see at checkout may differ from the number above; the list prices are the stable reference point. Some versions of the yearly page have also shown a short free trial before the annual charge kicks in.

If you want to compare against what you'd otherwise pay: LeetCode Premium runs about $159/year, and $99/year or $189 once undercuts that. The tradeoff isn't price, it's format and scope — you're buying structured pattern teaching with a smaller problem set, not a giant question bank.

## Who should skip this

AlgoMonster is a poor first stop if you're still learning what a hash map is. The pattern material assumes you can already write correct, compiling code in at least one language and that your bottleneck is choosing an approach, not implementing it.

It's also the wrong tool if your interview loop includes a serious system design round you haven't prepared for, or if behavioral interviews are where you keep losing offers. Those need dedicated prep, and no amount of DP drilling substitutes for them.

And if you're the type who needs a video explanation before a concept clicks, the text-and-diagram format will slow you down rather than speed you up. That's a real limitation, not a knock.

## Short answers to the usual questions

**Do I need LeetCode Premium to finish Blind 75?** No, but six of the problems are Premium-only on LeetCode itself. Graph Valid Tree, Alien Dictionary, Meeting Rooms, Meeting Rooms II, Number of Connected Components in an Undirected Graph, and Encode and Decode Strings. Free versions exist elsewhere, and pattern-focused platforms cover the same techniques without the paywall.

**Is Blind 75 enough for FAANG?** It covers the techniques that show up constantly in coding screens. It doesn't cover system design, behavioral rounds, or company-specific quirks, and 75 problems is a floor, not a ceiling — expect to add volume once the patterns are in place.

**Blind 75 or Grind 75?** Grind 75 is the same author's later version with adjustable size and a schedule built around your timeline. If you have eight weeks and want a defined endpoint, Blind 75 is fine. If your interview is in three weeks or you want a slower ramp, Grind 75 adapts better.

**How long does it take?** Roughly 40–55 hours of focused work, or about two months at an hour a day, plus revisit time for the problems you fail the first pass.

**Do I need to solve all 75?** If you can look at any problem on the list and immediately name the pattern, its complexity, and the shape of the solution, you've gotten what the list has to offer. Counting solved problems is a weaker signal than being able to explain your approach out loud in five minutes.

---

The reason Blind 75 keeps working is that it forces scarcity on a problem space that has no natural end. It fails when you treat it as a checklist and stop asking why each problem is on it. Fix the order, name the pattern after every problem, and re-solve what broke you — that's the difference between two months of grinding and two months of getting measurably faster.

👉 [Browse the free AlgoMonster content and see the current plan pricing](https://algo.monster?fpr=li69) if you want the pattern layer underneath the list handled for you.
