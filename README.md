# To-Do List App
[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/ZainaRahman/A-simple-to-do-list-app)

A simple and intuitive To-Do List application for Android built with Java. This app allows users to quickly add and manage their tasks. It features a clean interface with a dynamic, animated gradient background.

## Features

*   **Add Tasks:** Easily add new items to your to-do list using the input field.
*   **Remove Tasks:** Simply long-press an item in the list to delete it. A confirmation toast message will appear.
*   **Input Validation:** Prevents adding empty tasks and prompts the user to enter text.
*   **Animated Background:** The app background features a smooth, animated gradient transition for a visually appealing experience.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   Android Studio installed on your machine.
*   An Android emulator or a physical Android device.

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/zainarahman/to_to_list_app.git
    ```
2.  **Open in Android Studio:**
    *   Launch Android Studio.
    *   Select `File > Open` and navigate to the cloned project directory.
3.  **Build the Project:**
    *   Wait for Android Studio to sync the Gradle files and download all dependencies.
4.  **Run the App:**
    *   Select an available emulator or connect a physical device.
    *   Click the `Run 'app'` button (green play icon).

## How to Use

1.  Launch the application on your device or emulator.
2.  In the text field at the top, type the task you want to add.
3.  Tap the **"Add"** button. The task will now appear in the list.
4.  To remove a task, press and hold the specific item in the list. It will be deleted, and a "Item Removed" message will be displayed.

## Technology Stack

*   **Language:** Java
*   **Platform:** Android
*   **UI Toolkit:** Android XML Layouts
*   **Core Components:**
    *   `AppCompatActivity`
    *   `ListView` with `ArrayAdapter`
    *   `EditText` and `Button` for user input.
*   **Build Tool:** Gradle
