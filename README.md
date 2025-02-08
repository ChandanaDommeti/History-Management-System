# Browser History Manager

This is a simple Java-based browser history manager that allows users to navigate through their browsing history using a tab-based system.

## Features

- Open a new tab with a specified URL.
- Navigate to the previous tab.
- Navigate to the next tab.
- Display the currently open tab.
- Exit the application.

## How It Works

- The program maintains a **back stack** and a **forward stack** to track tab navigation.
- When a new tab is opened, the current tab is pushed onto the back stack.
- Navigating back moves the current tab to the forward stack and retrieves the previous tab.
- Navigating forward moves the current tab back onto the back stack and retrieves the next tab.

## Installation & Usage

1. Clone the repository or download the source code.
2. Compile the Java file:
   ```sh
   javac HistoryManagement.java
3. Run the program:
   ```sh
   java HistoryManagement
   
Follow the on-screen instructions to manage your browser tabs.

## Example Usage

--- Welcome to Browser History Manager ---
1. Open new tab
2. Go to previous tab
3. Go to next tab
4. Show current tab
5. Exit
Choose an option: 1
Enter website URL: google.com
New tab opened: google.com

## Requirements

Java 8 or later
Any standard Java compiler (e.g., javac)

## Future Enhancements

- Add support for multiple open tabs at once.
- Implement a graphical user interface (GUI).
- Save and load browser history across sessions.
