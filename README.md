# 🌐 Social Network Simulation (OOP)

A comprehensive C++ simulation of a social media ecosystem. This project models complex relationships between Users, Pages, and Posts using Advanced Object-Oriented Programming principles.

---

## 🚀 Key Features
- **Polymorphic Interactivity:** Both `User` and `Page` objects can comment and like posts via the `Commenter` interface.
- **Activity Tracking:** Posts can hold specific activities (Feeling, Thinking, Celebrating).
- **Memory System:** A specialized `Memory` class that inherits from `Post` to share "Throwback" content.
- **Bi-directional Friendships:** Realistic friend-linking between user profiles.
- **Home Feed Logic:** A `viewHome()` function that aggregates posts from all followed pages and friends.

---

## 🛠️ Technical Architecture

### OOP Concepts Implemented:
1. **Inheritance:** `Memory` inherits from `Post`; `User` and `Page` inherit from the `Commenter` abstract base class.
2. **Polymorphism:** Virtual functions like `getName()` and `display()` ensure the correct object behavior at runtime.
3. **Association & Aggregation:** - A `Post` *has* `Comments`.
   - A `User` *has* a `Timeline`.
   - A `Comment` *knows* its `Commenter`.
4. **Memory Management:** Manual allocation using `new` and proper cleanup using `delete` to prevent memory leaks.

---

## 🎮 How to Run

### Prerequisites
- A C++ compiler (GCC/MinGW or Clang).
- A Windows environment (though this specific code is cross-platform friendly).

### Steps
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Social-Network-Sim.git](https://github.com/YOUR_USERNAME/Social-Network-Sim.git)
