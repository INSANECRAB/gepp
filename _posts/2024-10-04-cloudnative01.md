---
title: "Cloud Native : difference between cloud native and monolithic traditional architecture (modifying)"
categories:
  - cloudnative
tags:
  - cloudnative
  - architecture
  - note
---

What's the key point of both cloud native and traditional architecture?

* session status

below is not related to this subject, just sample texts.

### Ordered -- Unordered -- Ordered

1. ordered item
2. ordered item 
  * **unordered**
  * **unordered** 
    1. ordered item
    2. ordered item
3. ordered item
4. ordered item

### Ordered -- Unordered -- Unordered

1. ordered item
2. ordered item 
  * **unordered**
  * **unordered** 
    * unordered item
    * unordered item
3. ordered item
4. ordered item

### Unordered -- Ordered -- Unordered

* unordered item
* unordered item 
  1. ordered
  2. ordered 
    * unordered item
    * unordered item
* unordered item
* unordered item

### Unordered -- Unordered -- Ordered

* unordered item
* unordered item 
  * unordered
  * unordered 
    1. **ordered item**
    2. **ordered item**
* unordered item
* unordered item

### Task Lists

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
  - [ ] Follow discussions
  - [x] Push new commits