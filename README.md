# Data-Structure-Algorithms-1649A
 
Markdown
# 📚 Bookstore Management System

A console-based Java application designed to manage a bookstore's inventory and process customer orders. 

This project was built from scratch **without using Java's built-in collections framework** (`java.util.ArrayList`, `java.util.LinkedList`, etc.). Instead, it features custom-built generic data structures and sorting algorithms, making it a great demonstration of Data Structures and Algorithms (DSA) in practice.

## ✨ Features

* **Inventory Management**: 
  * Add new books to the catalog with titles, custom or auto-generated unique codes (`#1234`), prices, and stock quantities.
  * View the complete list of available books.
* **Order Processing (FIFO)**: 
  * Place new orders by selecting books from the catalog.
  * Orders are placed into a custom Queue and processed sequentially.
  * View all pending and completed orders, automatically aggregating duplicate book entries.
* **Search Functionality**: 
  * Search through orders using keywords (customer name, address, order status, book title, or book code).
* **Automatic Sorting**: 
  * Books within an order are automatically sorted alphabetically by title using a custom **QuickSort** algorithm.
* **Performance Benchmarking**: 
  * Includes built-in execution time measurements (in nanoseconds) to benchmark the performance of the custom Array, Queue, and QuickSort implementations.

## 🛠️ Technical Details

This application implements several core computer science concepts from scratch:

* `MyArray<T>`: A custom, generic dynamic array that automatically resizes (doubles capacity when full, shrinks when mostly empty) to store books and order quantities.
* `MyQueue<T>`: A custom, generic queue implemented via a singly linked-list (`Node<T>`) to handle order processing in a First-In-First-Out (FIFO) manner.
* **QuickSort**: A custom recursive QuickSort algorithm implementation specifically tailored to sort `Book` objects by their string titles.

## 🚀 Getting Started

### Prerequisites
* Java Development Kit (JDK) 8 or higher installed on your machine.

### Installation & Execution

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/your-repo-name.git](https://github.com/yourusername/your-repo-name.git)
   cd your-repo-name
Compile the Java file:

Bash
javac Bookstore.java
Run the application:

Bash
java Bookstore
💻 Usage
Upon running the application, you will be presented with a menu in the console. Enter the number corresponding to the action you want to take:

Plaintext
Choose an option:
1. Place Order
2. Process Order
3. View All Orders
4. Search orders
5. Add Book
6. View Book
7. Exit
Follow the on-screen prompts to navigate the system. The application will automatically run a performance benchmark of the custom data structures and print the execution times to the console right before the menu appears.

📝 License
This project is open-source and available under the MIT License.


### Tips for your GitHub Repository:
* **Replace the placeholders:** Make sure to update the `git clone` URL with your actual GitHub username and repository name.
* **Screenshots:** If you want to make the README even better, take a screenshot of
