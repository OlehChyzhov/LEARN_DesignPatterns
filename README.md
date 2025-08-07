# Design Patterns Study Notes 🤓

This repository contains C# implementations of design patterns based on a course I've taken. 🚀🚀🚀

---

### 📂 File Structure by Course Section

In this Console application, each design pattern has its own dedicated folder.

#### 🔷 SOLID Principles Structure

Each principle is implemented in a separate file and structured as follows:

- `#Default Objects` — Objects required for demonstration.
- `#Problem` — Step-by-step explanation of the problem or violation.
- `#*_ViolationExample` *(optional)* — Example showing how the principle is violated.
- `#Solution` — Step-by-step explanation of the correct implementation.
- `#*_Example` — A class with a `Run()` method that can be invoked from `Main`.

#### 🔷 Other Design Patterns Structure

Each design pattern has its own folder containing:

- A `Problem.cs` file that demonstrates the issue the pattern addresses.
- One or more subfolders representing specific variations or implementations of the pattern.

Within these subfolders, you'll find the necessary files and classes that illustrate the pattern in detail.

- If the required classes are small, they are usually placed together in the same file as the design pattern code, organized with regions for clarity.
- Larger classes are separated into individual files for better maintainability.

Note that models like `Car` or `Person` are pattern-specific and may differ between patterns or their variations.

Additionally, each pattern folder typically contains a static example class with a `Run()` method to demonstrate usage, similar to the approach used in the SOLID principles section.

---

### 🧠 Purpose

This repository serves as a **quick-reference guide**.  
It helps reinforce concepts and acts as a cheat sheet when working with design patterns in the future.
