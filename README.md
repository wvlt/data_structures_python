# 📚 Data Structures & Algorithms in Python

> **Code repository for my YouTube DSA tutorial series** 🎥

Welcome! This repository contains all the code examples and implementations from my Data Structures and Algorithms tutorial videos. Whether you're preparing for technical interviews, solving LeetCode problems, or just want to understand how data structures work in Python, you've come to the right place!

⭐ **If you find this helpful, please star this repo and subscribe to my channel!** ⭐

---

## 🎯 What You'll Find Here

- **Complete code examples** from each video
- **Step-by-step implementations** with clear explanations
- **Common patterns and techniques** used in LeetCode problems
- **Beginner-friendly explanations** that make complex concepts easy to understand

---

## 📖 Video 1: Linked Lists in Python - Understanding ListNode

> 🤔 *"I don't understand the ListNode class"* - 219+ people on LeetCode

If linked lists feel confusing, you're not alone! This is THE foundational video you need before tackling any LeetCode linked list problems.

### 🎯 What You'll Learn:

- ✅ What a ListNode actually IS (using the treasure hunt analogy that finally makes it click)
- ✅ Why we use `.val` and `.next` instead of regular Python lists
- ✅ How to create and connect nodes step-by-step
- ✅ How to traverse a linked list without getting lost
- ✅ Common beginner mistakes (and how to avoid the dreaded "NoneType has no attribute" error)

### 💡 Perfect if you:

- ❌ Get confused when you see ListNode in LeetCode problems
- ❌ Don't understand why we can't just use regular Python lists
- ❌ Keep getting NoneType errors when working with linked lists
- ❌ Want to prepare for technical interviews

By the end of this video, you'll understand linked lists well enough to tackle problems like "Merge Two Sorted Lists," "Reverse Linked List," and more!

📚 **This is Part 1 of my Linked List series** - we build the foundation here, then solve real LeetCode problems in the next videos.

### 📝 Code Examples in `1_listnode.ipynb`

The notebook contains practical examples demonstrating:

1. **Basic ListNode Class Definition**
   - The fundamental structure with `val` and `next` attributes

2. **Creating and Connecting Nodes**
   - Example 1: Creating individual nodes (kitchen, bedroom, garage)
   - Example 2: Connecting two nodes (`first` → `second`)
   - Example 3: Building a chain of three nodes (`node1` → `node2` → `node3`)

3. **Accessing Node Values**
   - How to access `val` attribute
   - Understanding `None` when `next` is not set

4. **Traversing a Linked List**
   - Using a `current` pointer to move through the list
   - Understanding when you've reached the end (when `current` becomes `None`)

### 🔑 Key Concepts Covered:

- **Node Creation**: `ListNode(val)` creates a new node with a value
- **Linking Nodes**: `node1.next = node2` connects nodes together
- **Traversal Pattern**: Using `current = current.next` to move through the list
- **None Handling**: Understanding when `next` is `None` (end of list)

### ⏱️ Video Timestamps:

- 0:00 - Why linked lists confuse everyone
- 1:30 - The treasure hunt analogy (this will make it click!)
- 4:00 - Building your first ListNode in Python
- 7:00 - Connecting multiple nodes together
- 10:00 - Traversing a linked list (the right way)
- 13:00 - Common errors and how to debug them
- 15:30 - When to use linked lists vs regular lists

---

## 🚀 Getting Started

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/data_structures_python.git
   cd data_structures_python
   ```

2. **Open the notebooks:**
   - Use Jupyter Notebook, JupyterLab, or VS Code with Jupyter extension
   - Each notebook corresponds to a video in the series

3. **Follow along:**
   - Watch the corresponding video
   - Run the code examples
   - Experiment and modify the code to deepen your understanding

---

## 📚 Series Structure

- **Part 1**: Understanding ListNode (this video) ✅
- **Part 2**: Merge Two Sorted Lists (coming soon)
- **Part 3**: Reverse Linked List (coming soon)
- *More videos coming...*

---

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to open an issue or submit a pull request!

---

## ⭐ Support

If you find these tutorials helpful:
- ⭐ **Star this repository** to help others find it
- 🔔 **Subscribe to my YouTube channel** for more DSA content
- 💬 **Share with friends** who are also learning DSA

---

## 📌 Tags

`#linkedlist` `#python` `#leetcode` `#programming` `#datastructures` `#coding` `#algorithms` `#tutorial` `#beginnerfriendly` `#tech`

---

## 📝 License

This repository is for educational purposes. Feel free to use the code for learning and practice!

---

**Happy Coding! 🎉**

*Remember: Understanding data structures is a journey. Take your time, practice, and don't hesitate to rewatch videos or experiment with the code!*
