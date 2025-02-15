<div align="center">
   <img src="https://github.com/user-attachments/assets/3f11292f-3f6a-4e25-9de9-3bafa4150daa" alt="Scribe Logo" width="200" height="200">
</div>

# Custom_Tkinter

This repository simulates a development **roadmap** for creating a "Custom_Tkinter" Application namely, **Scribe_Smart Notes**.

<div align="center">
   
   **📌 For more information on "Scribe_Smart Notes" visit our [Page](https://github.com/Yashvant-Chhapwale/Scribe_Smart-Notes)** <br>
   **📌 Click [`Download`](https://github.com/Yashvant-Chhapwale/Scribe_Smart-Notes/releases) to start using "Scribe_Smart Notes"**
</div>

---

## About Custom-Tkinter
CustomTkinter is a modern **GUI library for Python** that enhances Tkinter with a sleek, customizable look using themes, rounded corners, and improved widgets. It is built on top of Tkinter but offers a more modern design with dark mode support.

### Features:
- `Theming_Support:` Light, Dark, and System themes.
- `Custom_Widgets:` Includes modern buttons, sliders, and checkboxes.
- `Rounded_Corners and Hover_Effects:` Aesthetic improvements over standard Tkinter.
- `Built-in Colors & Styling:` Easily customizable UI elements.
- `Scalability:` Responsive UI that adapts to different screen sizes.
  <br>
  
**📌 Visit the [Documentation](https://customtkinter.tomschimansky.com/) to know more about `Custom_Tkinter`.**

---

<div align="center">
 <h1>Development RoadMap</h1>
</div>

<div align="center">
 
| TITLE                                                                                                          | SECTION_LINK                                                                                  |
|----------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| 1.  **Creating a Python Virtual Environment**                                                                  | >> [` CHECK CONTENT `](#creating-a-python-virtual-environment)                                |
| 2.  **Installing and Importing required Modules for the Application**                                          | >> [` CHECK CONTENT `](#installing-and-importing-required-modules)                            |
| 3.  **Custom-Tkinter Window Themes**                                                                           | >> [` CHECK CONTENT `](#custom_tkinter-window-themes)                                         |
| 4.  **Custom-Tkinter Window Geometry(Width x Height)**                                                         | >> [` CHECK CONTENT `](#ajust-custom_tkinter-window-dimensions)                               |
</div>

---

## Creating a Python Virtual Environment
### 1. Ensure Python is Installed:
- **For ` Windows ` Systems:** <br>
     Ensure Python is installed by running the following **prompt**:
     ```
     python --version
     ```
- **For ` Linux / MacOS ` Systems:** <br>
     Ensure Python is installed by running the following **prompt**:
     ```
     python3 --version
     ```
<br>

### 2. Create a Virtual Environment:
- **For ` Windows ` Systems:** <br>
     Create a `Virtual Environment` in Python by running the following **prompt**:
     ```
     python -m venv myenv
     ```
- **For ` Linux / MacOS ` Systems:** <br>
     Create a `Virtual Environment` in Python by running the following **prompt**:
     ```
     python3 -m venv myenv
     ```
<br>

### 3. Activate the Virtual Environment:
- **For ` Windows ` Systems:** <br>
     `Activate` the `Virtual Environment` in Python by running the following **prompt**:
     ```
     # For Command Prompt:
     myenv\Scripts\activate

     # For Powershell:
     myenv\Scripts\Activate.ps1
     ```
- **For ` Linux / MacOS ` Systems:** <br>
     `Activate` the `Virtual Environment` in Python by running the following **prompt**:
     ```
     source myenv/bin/activate
     ```
<br>

### 4. Deactivate the Virtual Environment:
- **For ` Windows ` Systems:** <br>
     After use, `Deactivate` the `Virtual Environment` in Python by running the following **prompt**:
     ```
     deactivate
     ```
- **For ` Linux / MacOS ` Systems:** <br>
     After use, `Deactivate` the `Virtual Environment` in Python by running the following **prompt**:
     ```
     deactivate
     ```
     
---

## Installing and Importing required Modules
### 1. Required Standard_Libaries:
- **`os`(Operating System) Library:** <br>
  - Provides functions to interact with the operating system.
  - Used for file handling, environment variables, and system commands.
  
   **Use the following `Import Statement` in your code:**
    ```
    import os
    ```

- **`sys`(System) Library:** <br>
  - Provides system-specific functions and parameters.
  - Used for command-line arguments, interpreter interaction, and module management.
  - Ex:
      - `sys.exit()`: For **Exiting** the program.
      - `sys.path()`: It returns a list of directories where Python looks for modules when importing them. Can dynamically add a directory to Python's Module_Search_Paths using `sys.path.append()`.
  
   **Use the following `Import Statement` in your code:**
    ```
    import sys
    ```

- **`tkinter` Library:** <br>
  - Python's built-in GUI toolkit for creating graphical user interfaces.
  - Ex:
      - `tkinter.filedialog`: A module in Tkinter for Opening and Saving files via `File_Dialog_Windows`.<br>
       <img src="https://github.com/user-attachments/assets/abfeacd9-e276-4cea-8dcd-358d1cc6d51d" width=350 height=200><br>
      - `tkinter.messagebox`: Provides `Pop_Up Dialog_Boxes` for messages, warnings, and errors.
      - `tkinter.font`: Handles `Font-related Functionality` in Tkinter.
      - `tkinter.ttk`: `Themed_Tkinter_Widgets(ttk)` for a more modern and consistent look. (Ex: `ttk.Notebook`, `ttk.Button`, `ttk.Label`, `ttk.Entry`, `ttk.Checkbutton`, `ttk.Combobox`, `ttk.Progressbar`)
  
   **Use the following `Import Statement` in your code:**
    ```
    import tkinter
    ```
    **OR**
     ```
    from tkinter import filedialog, messagebox. font, ttk
    ```

- **`threading` Library:** <br>
  - Provides tools for running Multiple Threads in parallel.
  - Useful for **Performing Background Tasks** without freezing the UI.
  
   **Use the following `Import Statement` in your code:**
    ```
    import threading
    ```
<br>

### 2. Required Third-Party_Libaries:
- **`customtkinter` Library:** <br>
  - An advanced version of Tkinter with modern UI elements and themes.
  - Provides additional widgets and customization options.<br>
  
  **Run the following Prompt to install Custom Tkinter:**
    ```
    pip install customtkinter
    ```
   **Use the following `Import Statement` in your code:**
    ```
    import customtkinter as ctk
    ```
    
- **`google.generativeai` Library:** <br>
  - Google's **Generative AI SDK(Software_Development_Kit)** for interacting with AI models like **Gemini**. 
  - Used for **Text_Generation**, **AI-Based tasks**, and **API_Interactions**.<br>
  
  **Run the following Prompt to install Custom Tkinter:**
    ```
    pip install google-generativeai
    ```
   **Use the following `Import Statement` in your code:**
    ```
    import google.generativeai as genai
    ```
    
- **`pyinstaller` Library:** <br>
  - It is used to convert Python_Scripts into standalone **Executables** (**.exe** for Windows, **.app** for macOS, etc).
  - It bundles all dependencies into a single package so that users can run the application without installing Python. <br>
  
  **Run the following Prompt to install Custom Tkinter:**
    ```
    pip install pyinstaller
    ```
    
- **Alternatively, Run this single command to install all required Libraries:**
  ```
  pip install customtkinter google-generativeai pyinstaller
  ```
<br>

<div align="center">
   ________________________________________________________
</div>

### Note:
- Don't Forget to [`Activate`](#3-activate-the-virtual-environment) your **Python_Virtual_Environment** before package installations.
- ⚠️ Without a Virtual Environment, Python packages are installed globally, which can lead to **"conflicts"** between different Projects that require different versions of the same package.
  
---

## Custom_Tkinter Window Themes:
**In CustomTkinter, you can adjust the Theme using the [`set_appearance_mode()`](#1-set_appearance_mode) and [`set_default_color_theme()`](#2-set_default_color_theme)  functions.**

### 1. set_appearance_mode():
- The `set_appearance_mode()` function in CustomTkinter is used to change the overall appearance of the UI, allowing you to switch between **Light**, **Dark**, or **System** Mode.
- CustomTkinter supports the following Appearance_Modes:
   - **Light:** Default light theme.
   - **Dark:** Sets a Dark theme.
   - **System:** Matches System theme settings.
- **CODE:**
  ```
  ctk.set_appearance_mode("Dark") # Sets the appearance_mode to "Dark"
                                  # Other Options: "Light" (Default), "Dark", "System"
  ```
<br>

### 2. set_default_color_theme():
- The `set_default_color_theme()` function in CustomTkinter is used to set the Color_Theme for widgets such as **Buttons**, **Progress_Bars**, and **Sliders**.
- CustomTkinter supports the following Color_Themes:
   - **blue:** Applies a Blue Color_Theme.
   - **dark-blue:** Applies a Darker_Blue Color_Theme.
   - **green:** Applies a Green Color_Theme.   
- **CODE:**
  ```
  ctk.set_default_color_theme("blue") # Sets the color_theme to "blue"
                                      # Other Options: "blue" (Default), "dark-blue", "green"
                                   
  ```
<br>

### 3. Setting a Custom_Color_Theme:
- **Custom_Tkinter** allows us to create our own **Custom_Color_Theme** by defining a `JSON` file with custom color themes.
- **`Step 1`:** Create a **".JSON"** file (`custom_purple.json`) and define the **Custom_Color_Theme** in the following format: <br>
  ```
  {
  "CTk": {
    "fg_color": ["#e5e5e5", "#070c1c"]
  },
  "CTkToplevel": {
    "fg_color": ["#e5e5e5", "#070c1c"]
  },
  "CTkFrame": {
    "corner_radius": 6,
    "border_width": 2,
    "fg_color": ["#8ecae6", "#14213d"],
    "top_fg_color": ["#8ecae6", "#14213d"],
    "border_color": ["#b9cbd7", "#212529"]
  },
  "CTkButton": {
    "corner_radius": 4,
    "border_width": 0,
    "fg_color": ["#14213D", "#fca311"],
    "hover_color": ["#25445f", "#fdb619"],
    "text_color": ["#fca311", "#14213D"],
    "border_color": ["#ffffff", "#e5e5e5"],
    "text_color_disabled": ["#CE93D8", "#7E57C2"]
  },
  "CTkLabel": {
    "corner_radius": 0,
    "fg_color": "transparent",
    "text_color": ["#14213D", "#9bd1f2"]
  },
  "CTkEntry": {
    "corner_radius": 2,
    "border_width": 2,
    "fg_color": ["#F3E5F5", "#070c1c"],
    "border_color": ["#fca311", "#335480"],
    "text_color": ["#32373b", "#e5e5e5"],
    "placeholder_text_color": ["#14213d", "#fca311"]
  },
  "CTkCheckBox": {
    "corner_radius": 2,
    "border_width": 2,
    "fg_color": ["#14213d", "#335480"],
    "border_color": ["#14213d", "#335480"],
    "hover_color": ["#335480", "#1e2749"],
    "checkmark_color": ["#fca311", "#fca311"],
    "text_color": ["#14213d", "#9bd1f2"],
    "text_color_disabled": ["#CE93D8", "#B39DDB"]
  },
  "CTkSwitch": {
    "corner_radius": 1000,
    "border_width": 3,
    "button_length": 0,
    "fg_color": ["#ffffff", "#28427b"],
    "progress_color": ["#14213d", "#fca311"],
    "button_color": ["#0096c7", "#f77f00"],
    "button_hover_color": ["#0077b6", "#fca311"],
    "text_color": ["#14213d", "#9bd1f2"],
    "text_color_disabled": ["#CE93D8", "#B39DDB"]
  },
  "CTkSlider": {
    "corner_radius": 1000,
    "button_corner_radius": 1000,
    "border_width": 6,
    "button_length": 0,
    "fg_color": ["#ffffff", "#28427b"],
    "progress_color": ["#14213d", "#fca311"],
    "button_color": ["#0096c7", "#f77f00"],
    "button_hover_color": ["#0077b6", "#fca311"]
  },
  "CTkComboBox": {
    "corner_radius": 2,
    "border_width": 1,
    "fg_color": ["#ffffff", "#070c1c"],
    "border_color": ["#fca311", "#28427b"],
    "button_color": ["#fca311", "#28427b"],
    "button_hover_color": ["#ffd60a", "#335480"],
    "text_color": ["#14213d", "#fca311"],
    "text_color_disabled": ["#CE93D8", "#B39DDB"]
  },
  "CTkScrollbar": {
    "corner_radius": 800,
    "border_spacing": 7,
    "fg_color": "transparent",
    "button_color": ["#14213d", "#fca311"],
    "button_hover_color": ["#14213d", "#fca311"]
  },
  "CTkSegmentedButton": {
    "corner_radius": 4,
    "border_width": 2,
    "fg_color": ["#14213d", "#fca311"],
    "selected_color": ["#25445f", "#ffcc00"],
    "selected_hover_color": ["#25445f", "#fdb619"],
    "unselected_color": ["#14213d", "#fca311"],
    "unselected_hover_color": ["#25445f", "#fdb619"],
    "text_color": ["#fca311", "#14213D"],
    "text_color_disabled": ["gray74", "gray60"]
  },
  "CTkTextbox": {
    "corner_radius": 6,
    "border_width": 2,
    "fg_color": ["#f8f9fa", "#5e5e5e"],
    "border_color": ["#e5e5e5", "#212529"],
    "text_color": ["#ffffff", "#e5e5e5"],
    "scrollbar_button_color": ["#14213d", "#fca311"],
    "scrollbar_button_hover_color": ["#14213d", "#fca311"]
  },
  "CTkScrollableFrame": {
    "label_fg_color": ["#14213D", "#9bd1f2"]
  },
  "DropdownMenu": {
    "fg_color": ["#ffffff", "#070c1c"],
    "hover_color": ["#ffaa00", "#1e2749"],
    "text_color": ["#14213d", "#fca311"]
  },
  "CTkFont": {
    "macOS": {
      "family": "SF Display",
      "size": 13,
      "weight": "normal"
    },
    "Windows": {
      "family": "Roboto",
      "size": 13,
      "weight": "normal"
    },
    "Linux": {
      "family": "Roboto",
      "size": 13,
      "weight": "normal"
    }
  }
  }
  ```
  **`📝Note`:** The **RAW Color_Theme File** follows the format:<br>
  ```
  {
  "Widget_Name":{
  "Widget_Attribute":["color_theme_for_LightMode","color_theme_for_DarkMode"],
  },
  }
  ```
- **`Step 2`:** Pass this **RAW** file in the `set_default_color_theme()` function: <br>
  ```
  ctk.set_default_color_theme("./custom_purple.json")

  root = ctk.CTk()
  root.mainloop()
  ```

---
