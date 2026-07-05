# Coding Skills Study Hub

This repository holds revision material for software-engineering assessment work: knowledge notes and multiple-choice practice covering coding, debugging and repair, compilers and programming languages, porting and migration, and developer tooling.

## Local Files

- `docs/index.html`: GitHub Pages landing page and document hub, with a curated Reading & References section (free books, interactive tools, and reference docs) for each study area.
- `docs/coding-skills.html`: six-section revision page with 66 terminology cards (including low-level topics: bit manipulation, alignment, SSA, ABI, endianness, hermetic builds), ASCII diagrams, and 81 practice questions (single answer, select-all-that-apply, arrange-in-order, plus code/settings-completion and spot-the-bug snippets covering C, Python, JS, x86-64 assembly, GDB, Make, Docker, and CI), including principal-level judgment questions and a 16-question interview drill sourced from Glassdoor/LeetCode most-asked lists (Two Sum, missing number, in-place dedup, product-except-self, Kadane's, LRU cache, stock buy/sell, merge sorted lists, whiteboard process, ...), with explanations, running score, and reshuffling retry.
- `docs/c-programming.html`: expert C revision across language and memory model, dynamic memory, systems and low-level programming, performance, and libraries and tooling (44 terminology cards + 215 questions in five exam formats - single-answer, select-all-that-apply, arrange-in-order, code-insertion, and compare-the-snippet best-practice questions covering loop optimization/SIMD/volatile/mmap/alignment/atomics - including principal-level judgment questions).
- `docs/git-version-control.html`: expert Git revision across repository management, branching strategies, collaboration workflows, core operations, and best practices (40 terminology cards + 100 questions = 20 per section in four exam formats - single-answer, select-all-that-apply, arrange-in-order, code/settings-insertion - including principal-level judgment questions).
- `docs/coding-interview.html`: 16 of the most commonly asked coding-interview problems (Two Sum, Valid Parentheses, Reverse Linked List, Kadane's, BFS level-order, Number of Islands, Binary Search, Coin Change, etc.) as a collapsible Q&A - problem statement, key insight, worked Python solution, and time/space complexity - plus an 8-pattern cheat sheet and an offline search filter.
- `docs/styles.css`: shared stylesheet (same look as the Isaac Sim study hub).

## Deployment

The site is designed to deploy with GitHub Pages from the `docs` folder on the `main` branch.
