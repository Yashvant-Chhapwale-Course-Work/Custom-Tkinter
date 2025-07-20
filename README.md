<div align="center">
   <img src="https://github.com/user-attachments/assets/3f11292f-3f6a-4e25-9de9-3bafa4150daa" alt="Custom_Tkinter Logo" width="200" height="200">
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
 
| TITLE                                                                                                          | SECTION_LINK                                                                                |
|----------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| 1.  **Creating a Python Virtual Environment**                                                                  | >> [` 🔗 CONTENT `](#creating-a-python-virtual-environment)                                |
| 2.  **Installing and Importing required Modules for the Application**                                          | >> [` 🔗 CONTENT `](#installing-and-importing-required-modules)                            |
| 3.  **Custom-Tkinter Window Themes**                                                                           | >> [` 🔗 CONTENT `](#custom_tkinter-window-themes)                                         |
| 4.  **Custom-Tkinter Window Geometry(Width x Height)**                                                         | >> [` 🔗 CONTENT `](#adjusting-custom_tkinter_window-dimensions)                           |
| 5.  **Creating Custom-Tkinter Window Instance (CTk( ))**                                                       | >> [` 🔗 CONTENT `](#creating-custom_tkinter_window_instance-CTk)                          |
| 6.  **Set Application Logo i.e, Window Icon**                                                                  | >> [` 🔗 CONTENT `](#setting-window-icon)                                                  |
| 7.  **Custom-Tkinter Frames and Scrollable-Frames**                                                            | >> [` 🔗 CONTENT `](#creating-custom_tkinter-frames-and-scrollabe_frames)                  |
| 8.  **Displaying Text and Images using Custom-Tkinter Labels**                                                 | >> [` 🔗 CONTENT `](#creating-custom_tkinter-labels-for-displaying-text-and-images)        |
| 9.  **Custom-Tkinter Buttons and Segmented-Buttons**                                                           | >> [` 🔗 CONTENT `](#creating-custom_tkinter-buttons-and-segmented_buttons)                |
| 10. **Custom-Tkinter Check_Box and Combo_Box**                                                                 | >> [` 🔗 CONTENT `](#creating-custom_tkinter-check_box-and-combo_box)                      |
| 11. **Custom-Tkinter Switch and Slider**                                                                       | >> [` 🔗 CONTENT `](#creating-custom_tkinter-switch-and-slider)                            |
| 12. **Custom-Tkinter Entry and Text_Box**                                                                      | >> [` 🔗 CONTENT `](#creating-custom_tkinter-entry-and-text_box)                           |
| 13. **Custom-Tkinter Widget Attributes_List**                                                                  | >> [` 🔗 CONTENT `](#listing-custom_tkinter-widget-attributes)                             |
| 14. **Manipulating Widget Attributes at Runtime using `.configure()`**                                         | >> [` 🔗 CONTENT `](#manipulating-attributes-using-configure--method)                      |
| 15. **Widget Layout Methods (`Pack`, `Place` and `Grid`)**                                                     | >> [` 🔗 CONTENT `](#widget-layout-methods-pack-place-and-grid)                            |
| 16. **Creating a Tabbed Interface using Tkinter's Notebook Widget**                                            | >> [` 🔗 CONTENT `](#creating-a-tabbed-interface-using-ttknotebook-)                       |
| 17. **Styling Tkinter's Notebook Widget using Style() Function**                                               | >> [` 🔗 CONTENT `](#styling-ttknotebook--using-ttkstyle--function)                        |
| 18. **Packaging a Python Script into an EXE using PyInstaller**                                                | >> [` 🔗 CONTENT `](#packaging-a-python-script-into-a-standalone-exe-using-pyinstaller)    |
| 19. **Packaging a Python Script into an EXE using Nuitka**                                                     | >> [` 🔗 CONTENT `](#packaging-a-python-script-into-a-standalone-exe-using-nuitka)         |
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
    from tkinter import filedialog, messagebox, font, ttk
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
- **`Step 1`:** Create a **".JSON"** file (`midnightOcean.json`) and define the **Custom_Color_Theme** in the following format: <br>
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
  ctk.set_default_color_theme("./midnightOcean.json")

  root = ctk.CTk()
  root.mainloop()
  ```
-  📌 Click [Here](https://github.com/Yashvant-Chhapwale-Course-Work/Custom-Tkinter/releases/tag/theme_1.0) to **Download** the `Custom Theme` File.

---

## Adjusting Custom_Tkinter_Window Dimensions:
**In CustomTkinter, you can adjust the Initial Resolution of the Window using the [`geometry()`](#1-geometry) function, Minimum Resize Dimensions for the Window using the [`minsize()`](#2-minsize) function and Maximum Resize Dimensions for the Window using the [`maxsize()`](#3-maxsize) function.**

### 1. geometry():
- The `geometry()` function in CustomTkinter sets the initial **Size** and **Position** of the Application Window.
- **CODE:**
  ```
  # Syntax:
  # root.geometry("<width> x <height> + <x_offset> + <y_offset>")

  root.geometry("600x350+750+100")
  ```
<br>

### 2. minsize():
- The `minsize()` function sets the **Minimum Resizable Width and Height** of the window, preventing the user from resizing it below the given dimensions.
- **CODE:**
  ```
  # Syntax:
  # root.minsize(<width>, <height>)

  root.minsize(350, 200)                      
  ```
<br>

### 3. maxsize():
- The `maxsize()` function sets the **Maximum Resizable Width and Height** of the window, preventing the user from resizing it beyond the given dimensions.
- **CODE:**
  ```
  # Syntax:
  # root.maxsize(<width>, <height>)

  root.maxsize(1000, 450)                      
  ```
<br>

---

## Creating Custom_Tkinter_Window_Instance CTk():
### 1. CTk():
- In `CustomTkinter`, the `CTk()` class is used to create the **Main_Application Window**, similar to `Tk()` in Standard `Tkinter`.
- **CODE:**
  ```
  import customtkinter as ctk
  
  app = ctk.CTk()
  ```
<br>

### 2. mainloop():
- In CustomTkinter, `mainloop()` is a method that starts the event loop of the application. It keeps the GUI running and listens for user interactions like button clicks, text input, and window resizing.
- In other words, When `mainloop()` is called, the application enters an **infinite loop that waits for events**.
- **CODE:**
  ```
  import customtkinter as ctk
  
  app = ctk.CTk()
  app.mainloop() #Starts the Event Loop                   
  ```
<br>

### 3. Creating an Application Window Using a Custom Class:
- When using **Object-Oriented Programming (OOP)** in **Custom_Tkinter**, you define a **Class** for your application and create an **Instance** of that class to run the program.
- Using a class makes the application `Modular` and `Scalable`.
- Steps to Create an **Application Instance**:
  - Define a **Class** that inherits from `tk.Tk` (for the Main_Application_Window).
  - Initialize the class using `__init__()`.
  - Create an **Instance** of the Class.
  - Run the **Event_Loop** using `.mainloop()`.
- **CODE:**
  ```
  import customtkinter as ctk

   # Customize theme for the Custom-Tkinter App
   ctk.set_appearance_mode("Dark")
   ctk.set_default_color_theme("./midnightOcean.json")

   #1. Define a Class for the Application
   class Main(ctk.CTk):
       #2. Initialize the Class
       def __init__(self):
           super().__init__() 

           # Set "Application_Title"
           self.title("Scribe")

           # Display-Window_Settings
           self.geometry("600x350")
           self.minsize(350,200)

  #3. Create an Instance of the Class
  app = Main()

  #4. Run the Event_Loop and Start the Application
  app.mainloop()
  ```
  - **`Note:`**
    - `__init()__` is a special method (also known as a constructor) that is automatically called when a new Object of a class is created. It typically contains:
       - **`Parameters`** to accept input values.
       - **`Default Attribute Values`** for the Object Instance of the Class (`self.attribute = value`).
       - **`Optional Logic`** like validation or function calls.
    - `super().__init__()` is used in Python when a class inherits from a parent class. It helps our Application_Class to inherit features from Custom_Tkinter (CTk()) Parent Class Constructor. 
<br>
  
---

## Setting Window Icon:
### 1. iconbitmap():
- You can set a custom Icon for a Costom_Tkinter Window using the `iconbitmap()` method for `.ico` files.
- **CODE:**
  ```
   app = ctk.CTk()
   app.iconbitmap("icon.ico")

   app.mainloop()
  ```
<br>

### 2. Setting a Window_Icon dynamically at Runtime using "wm_iconbitmap()":
- To dynamically set a Window_Icon at runtime in **CustomTkinter**, we use `wm_iconbitmap()`, which allows specifying an `.ico` file for the Application_Window.
- This method ensures compatibility across different execution environments, including standalone executables `.exe` files created with `PyInstaller` as well as Python Scripts `.py`.
- **CODE:**
  ```
   if getattr(sys, 'frozen', False):
            base_path = sys._MEIPASS  
        else:
            base_path = os.path.dirname(os.path.abspath(__file__))

        icon_path = os.path.join(base_path, "images", "scribe_logo.ico")

        self.wm_iconbitmap(icon_path)  
  ```
- **Explanation:**
  -  Above code ensures that the **Icon** is correctly applied in both development `.py` and packaged `.exe` execution.
  -  `getattr(sys, 'frozen', False)`: It checks whether the Python script is running as a `frozen (compiled)` executable.
      - The `sys.frozen` only exists when the script is compiled into an executable (e.g., with PyInstaller). 
      - If `sys.frozen` exists → Returns `True`.
      - If `sys.frozen` does not exist → Returns `False (default value)`.
  -  `sys._MEIPASS`: It is used by **PyInstaller** to extract files for **Executables** i.e, `.exe` .
  -  `os.path.dirname(os.path.abspath(__file__))`: This code is used to access the parent folder/directory of the Python Script `.py` being developed.
  -  `__file__`: It is a special attribute in **Python** that represents the `Path of the Current Script(.py)` which is being executed. 
  -  `os.path.join(base_path, "images", "logo.ico")`: This code is used to build the correct file path to the `.ico` file. It appends `/images/logo.ico` to either `sys._MEIPASS` or the obtained parent directory from `os.path.dirname(os.path.abspath(__file__))` depending upon the type of environment and execution.
  -  `wm_iconbitmap()`: This is a method of the **Window_Manager (wm)**, which is why it is prefixed with `wm_`. It is an alias for `iconbitmap()` and works the same way i.e, it is same as [**`iconbitmap()`**](#1-iconbitmap) function.
<br>

---

## Creating Custom_Tkinter Frames and Scrollabe_Frames:
### 1. CTkFrame():
- The `CTkFrame()` method is used to create a **Simple Container** for grouping widgets together.
- **CODE:**
  ```
   import customtkinter as ctk
   app=ctk.CTk()

   # Create a container/Frame and assign it to the "frame" variable
   frame = ctk.CTkFrame(app, width=300, height=200)
  
   app.mainloop()
  ```
<br>

### 2. CTkScrollableFrame():
- The `CTkScrollableFrame()` is similar to **CTkFrame()** but, it allows **Scrolling** when the content exceeds the available space.
- **CODE:**
  ```
   import customtkinter as ctk
   app=ctk.CTk()

   # Create a Scrollable_Frame and assign it to the "scrollableFrame" variable
   scrollableFrame = ctk.CTkScrollableFrame(app, width=300, height=200)
  
   app.mainloop()
  ```
<br>

---

## Creating Custom_Tkinter Labels for displaying Text and Images:
### 1. CTkLabel():
- The `CTkLabel()` is a widget in **CustomTkinter** that allows you to display text with a Window or Frame.
- **CODE:**
  ```
   import customtkinter as ctk
   app=ctk.CTk()

   # Create a Label and assign it to the "label" variable
   label = ctk.CTkLabel(app, text="Hello!")
  
   app.mainloop()
  ```
<br>

### 2. CTkImage():
- The `CTkImage()` is a **CustomTkinter** class that allows you to use images in light and dark mode dynamically. It is primarily used with widgets like `CTkLabel()`, `CTkButton()`(rarely),etc.
- **`CTkImage()` Attributes**:
  - `light_image`: This is the image that will be displayed when the application is in **Light_Mode**.
  - `dark image`: This is the image that will be displayed when the application is in **Dark_Mode**.
  - `size`(Optional): Defines the dimensions of the image in the format `(width,height)`.
- Also, we need to import `Pillow (PIL)` because **CustomTkinter's CTkImage** requires images to be in the `PIL Image_Format` rather than direct file_paths.<br>
  Run the following **Command** in Terminal to install `Pillow`:
  ```
  pip install pillow
  ```
  After installing `Pillow` ,  import the `Image` module from the Pillow library, allowing you to open, manipulate, and save images in Python.
  ```
  from PIL import Image
  ```
- **CODE:**
  ```
   import customtkinter as ctk
  
   #Import PIL for Image_Handling
   from PIL import Image 
  
   app=ctk.CTk()

   # Create a CTkImage Object
   my_image = ctk.CTkImage(light_image=Image.open("images/lightImage.png"), dark_image=Image.open("images/darkImage.png"), size=(50, 50))
  
   # Create a Label to display the image and assign it to the "label" variable
   label = ctk.CTkLabel(app, image=my_image, text="")
  
   app.mainloop()
  ```
<br>

---

## Creating Custom_Tkinter Buttons and Segmented_Buttons:
### 1. CTkButton():
- The `CTkButton()` is used for creating a **modern**, **customizable** button in **CustomTkinter**, designed to match the theme and appearance settings of the library.
- We can also define a `Function` to be executed when the button is **Clicked** using the `command` Attribute.
- **CODE:**
  ```
   import customtkinter as ctk
   app=ctk.CTk()

   # Define a Function "onClick" that is executed whenever the "button" is clicked
   def onClick():
      print("Hello User!");
  
   # Create a Button and assign it to the "button" variable
   button = ctk.CTkButton(app, text="Click Me", command=onClick)

   app.mainloop()
  ```
<br>

### 2. CTkSegmentedButton():
- The `CTkSegmentedButton()` in **CustomTkinter** is a button that consists of **Multiple Selectable Segments**.
- It allows users to switch between different options, making it ideal for mode **selection**, **filtering**, or **toggling between views**.
- You can also use the `values` Attribute in `CTkSegmentedButton` to define the different **selectable options** available in the button.
- **CODE:**
  ```
   import customtkinter as ctk
   app=ctk.CTk()
  
   # Define a Function "onClick" that is executed whenever the "button" is clicked
   def onClick(value):
      print(f"You chose {value}")
  
   # Create a Segmented_Button and assign it to the "segmentedButton" variable
   segmentedButton = ctk.CTkSegmentedButton(app, values=["Rock", "Paper", "Scissors"], command=onClick)

   app.mainloop()
  ``` 
<br>

### Note:
- The `Function` to be executed on **Clicking** the button must be defined before defining the **button**, or else the `command` Attribute might fail to recognize the function!
<br>

---

## Creating Custom_Tkinter Check_Box and Combo_Box:
### 1. CTkCheckBox():
- A `CTkCheckBox()` is a customizable checkbox widget in **CustomTkinter** that allows users to toggle between **Checked** and **Unchecked** states.
- It can be used to let users select multiple options in a **form**, **survey**, or **settings** panel.
- **CODE:**
  ```
   import customtkinter as ctk
   app = ctk.CTk()

   # Create a Function "onCheck" which performs operations depending upon the "checkbox's State"
   def onCheck():
      print(f"Checkbox State: {checkbox.get()}")  # 1 if checked, 0 if unchecked

   # Create a CheckBox
   checkbox = ctk.CTkCheckBox(app, text="Accept Terms", command=onCheck)

   app.mainloop()
  ```
<br>

### 2. CTkComboBox():
- A `CTkComboBox()` is a **Dropdown_Menu** that allows users to select one option from multiple choices.
- The `values` attribute is used for displaying multiple choices in **Combo_Box**.
- **CODE:**
  ```
   import customtkinter as ctk
   app = ctk.CTk()

   # Define a Function "onClick" that is executed whenever a "Choice" is selected in the "ComboBox"
   def onClick(choice):
      print(f"You chose {choice}")

   # Create a ComboBox
   combo = ctk.CTkComboBox(
      app, 
      values=["Rock", "Paper", "Scissors"], 
      command=onClick
   )

   app.mainloop()
  ```
<br>

---

## Creating Custom_Tkinter Switch and Slider:
### 1. CTkSwitch():
- A `CTkSwitch()` is a widget in **CustomTkinter** that provides a **Modern Toggle_Switch**.
- It allows users to switch between `ON` and `OFF` states.
- Core Attributes:
  - `command`: Calls a function when toggled.
  - `variable`: A temporary container which stores the **Switch_State**.
  - `onvalue` / `offvalue`: Defines **Values** for **ON** and **OFF** states.
- **CODE:**
  ```
   import customtkinter as ctk
   app = ctk.CTk()
  
   # Define the "Function" to be executed when the "Switch_State" is "Toggled"
   def toggleSwitch():
      print("Switch is:", switch_var.get())

   # Create a "Switch_Variable"
      switchState = ctk.StringVar(value="on")  # Default to "on" or "off" Switch_State

   # Create a "CTkSwitch()" Instance
      switch = ctk.CTkSwitch(app, text="Switch",
                             command=toggleSwitch,
                             variable=switchState,
                             onvalue="on", offvalue="off")
  
   app.mainloop()
  ```
<br>

### 2. CTkSlider():
- The `CTkSlider()` is a modern, customizable **Slider_Widget** that allows users to select a value from a specified range. 
- Core Attributes:
  - `command`: Calls a function for "Slider_Event".
  - `from_`: Defines the **Minimum_Value** for the Slider.
  - `to`: Defines the **Maximum_Value** for the Slider.
- You can also set the Slider to a **Default_Value** using the `slider.set(value)` function. Replace the `value` with an `Integer`.
- **CODE:**
  ```
   import customtkinter as ctk
   app = ctk.CTk()

   # Define a Function "onSlide" that is executed eith a "Slider_Event"
   def onSlide(value):
      print(f"User Counts: {int(value)}")

   # Create a "CTkSlider()" instance
   slider = ctk.CTkSlider(app, from_=0, to=100, command=onSlide)

   # Set "Default_Value" for the Slider
   slider.set(50)  
  
   app.mainloop()
  ```
<br>

---

## Creating Custom_Tkinter Entry and Text_Box:
### 1. CTkEntry():
- The `CTkEntry()` is a `Single-Line Text Input` Widget that allows users to enter a `Short String`, such as a **name**, **email**, or **password**.
- You can also include a **Placeholder** using the `placeholder_text` attribute.
- **CODE:**
  ```
   import customtkinter as ctk
   app = ctk.CTk()
  
   # Define a Function "get_input()" to get the input data from the "CTkEntry()" Widget
   def get_input():
      print("Hello: ", entry.get())

   # Create a "CTkEntry()" instance
   entry = ctk.CTkEntry(app, placeholder_text="Enter your name")
  
   app.mainloop()
  ```
- **Important **Methods** for manipulating Inputs:**
  - **`.get()`:** Retrieves the `Current Input_Text` from the Widget.<br>
  ```
  # Retrieves the Current_Text from the entry
  entry_text = entry.get()
  ```
  - **`.insert(index,text)`:** Inserts text at a Specific_Index.<br>
  ```
  # Insert Text at the Beginning
  entry.insert(0, "Text_Value")  
  ```
  ```
  # Insert Text at the End
  entry.insert("end", "Text_Value")
  ```
  - **`.delete(start,end)`:** Deletes text from the given Index_Range.<br>
  ```
  # Clear all Text
  entry.delete(0, "end")  
  ```
<br>

### 2. CTkTextbox():
- A `CTkTextbox()` is a `Multi-Line Text Input` Widget used for `Longer String` input, such as **comments**, **messages**, or **notes**.
- **CODE:**
  ```
   import customtkinter as ctk
   app = ctk.CTk()

   # Define a Function "get_text()" to get text input from the "CTkTextbox()" Widget
   def get_text():
      print("User:", textbox.get("1.0", "end"))  # ".get("1.0", "end")" is used to get all the Text from "row 1, column 01" (i.e, "1.0") to the "end" 

   # Create a "CTkTextbox()" instance
   textbox = ctk.CTkTextbox(app, width=300, height=100)
  
   app.mainloop()
  ```
- **Important **Methods** for manipulating Input Text:**
  - **`.get("1.0","end")`:** Retrieves the `Current Input_Text` from the Widget.<br>
  ```
  # Retrieves the Current_Text from the entry
  textbox_text = textbox.get("1.0", "end")
  ```
  - **`.insert(row_index.col_index,text)`:** Inserts text at a Specific_Index.<br>
  ```
  # Insert Text at the Beginning
  textbox.insert("1.0", "Text_Value")
  ```
  ```
  # Insert Text at the End
  textbox.insert("end", "Text_Value")
  ```
  - **`.delete(start,end)`:** Deletes text from the given Row.Column_Range.<br>
  ```
  # Clear all Text
  textbox.delete("1.0", "end")
  ```
<br>

---

## Listing Custom_Tkinter Widget Attributes:

| Attribute                    | Description                                                | Example                                                                                           |
|------------------------------|------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| 1.  *text*                   | Sets the `Text` to be displayed for the Widgets            | ``` button = ctk.CTkButton(app, text = "Click Me") ```                                            |
| 2.  *width*                  | Sets the Widget's `Width` in **pixels**                    | ``` button = ctk.CTkButton(app, width = 300) ```                                                  |
| 3.  *height*                 | Sets the Widget's `Height` in **pixels**                   | ``` button = ctk.CTkButton(app, width = 300, height = 150) ```                                    |
| 4.  *fg_color*               | Sets the `Foreground_Color`                                | ``` button = ctk.CTkButton(app, fg_color = "#fca311") ```                                         |
| 5.  *bg_color*               | Sets the `Background_Color`                                | ``` button = ctk.CTkButton(app, bg_color = "transparent") ```                                     |
| 6.  *text_color*             | Sets the `Text_Color`                                      | ``` button = ctk.CTkButton(app, text_color = "#14213D") ```                                       |
| 7.  *hover_color*            | Changes the Widget’s color when the user `hovers` over it  | ``` button = ctk.CTkButton(app, hover_color = "#fdb619") ```                                      |
| 8.  *corner_radius*          | Sets the Widget's `Border_Curvature`                       | ``` button = ctk.CTkButton(app, corner_radius = 5) ```                                            |
| 9.  *border_width*           | Sets `Border_Thickness`                                    | ``` button = ctk.CTkButton(app, border_width = 2) ```                                             |
| 10. *font*                   | Sets `Font_Family`, `Font_Size` and `Font_Style`           | ``` button = ctk.CTkButton(app, text = "Click Me", font = ("Arial", 12, "normal")) ```            |
| 11. *padx*                   | Adds `Padding` along `X-axis`                              | ``` button = ctk.CTkButton(app, padx = 5) ```                                                     |
| 12. *pady*                   | Adds `Padding` along `Y-axis`                              | ``` button = ctk.CTkButton(app, pady = 10) ```                                                    |
| 13. *anchor*                 | `Aligns` the **Widget's Content to `w (Left or West)`, `e (Right or East)`, `n (Top or North)`, `s (Bottom or South)`, `nw (Top-Left or NorthWest)`, `ne (Top-Right or NorthEast)`, `sw (Bottom-Left or SouthWest)`, `se (Bottom-Right or SouthEast)`**                          | ``` button = ctk.CTkButton(app, anchor = "w") ```                                                 |
| 14. *command*                | `Assigns a Function` to be executed by the Widget          | ``` button = ctk.CTkButton(app, command = onClick) ```                                            |
<br>

---

## Manipulating Attributes using configure( ) Method:
### configure():
- The `configure()` method allows you to dynamically change Widget's Attributes after the widget is created.
- **Syntax:**
  ```
  <widget_name>.configure(<attribute> = <value>)
  ```
- **Example:**
  ```
  button = ctk.CTkButton(app, text="")
  button.pack(pady=10)
  
  button.configure(text="Click Me")
  ```
<br>

---

## Widget Layout Methods (Pack, Place and Grid):
- We have learned how to define widgets, but to **display** them and **enable interactions**, we must use `Layout` Methods to position them within the window.
- Widgets are **not visible** unless placed inside the window using the `Layout` Methods.
- **Some `Layout` Methods are:**
   - [`pack()`](#1-pack)
   - [`place()`](#2-place)
   - [`grid()`](#3-grid)
<br>

### 1. pack(): 
- It stacks widgets **Vertically** or **Horizontally**.
- By default it arranges widgets in `Top-to-Bottom` order.
- It is generally used to arrange widgets `horizontally` or `vertically` inside a parent widget (Ex: `CTkFrame`).
- Core Attributes:
   -  `side`: It controls the `Widget_Placement_Direction` i.e, the direction in which the widgets are to be stacked. (`"top"`, `"bottom"`, `"left"`, `"right"`)
   -  `fill`: Expands a widget to cover the screen in the given direction. (`"x"`, `"y"`, `"both"`, `None`)
   -  `expand`: Makes widget fill the extra space on resizing. (`True` or `False`)
   -  `padx` and `pady`: Adds `Padding (Spacing)` around the widget.
   -  `ipadx` and `ipady`: Adds `Internal Padding` to the widget. Can be used for increasing the Widget's Size.
   -  `anchor`: Positions the Widget. (`center`,`n`,`s`,`e`,`w`,etc.)
- **SAMPLE CODE:**
  ```
   import customtkinter as ctk
   app=ctk.CTk()

   # Define a Function "onClick" that is executed whenever the "button" is clicked
   def onClick():
      print("Hello User!");
  
   # Create a "CTkButton" and assign it to the "button" variable
   button = ctk.CTkButton(app, text="Click Me", command=onClick)

   # Pack the "CTkButton" instance using the "pack()" function 
   button.pack(
      side="top",       # Position button at the top
      anchor="center",  # Align button to the center
      expand=True,      # Allow resizing
      fill="none",      # Keep original size
      padx=20, pady=20, # External spacing
      ipadx=10, ipady=5 # Internal spacing
   )

   app.mainloop()
  ```
<br>

### 2. place(): 
- It is used to **precisely position** widgets using `X` and `Y` **Coordinates**.
- It is useful for `overlapping` widgets without causing errors during **User Interactions**.
- It is ideal for `Absolute Positioning` of the Widgets.
- Core Attributes:
   -  `x`: Sets the `X-Coordinate` i.e, `Horizontal Positioning`.
   -  `y`: Sets the `Y-Coordinate` i.e, `Vertical Positioning`.
   -  `relx`: Defines the horizontal position `Relative to the Parent Widget’s Width`.
      - `relx = 0.0` stands for **0% of Parent Widget's Width** i.e, `Left Edge`.
      - `relx = 0.5` stands for **50% of Parent Widget's Width** i.e, `Horizontal Center`.
      - `relx = 1.0` stands for **100% of Parent Widget's Width** i.e, `Right Edge`.
   -  `rely`: Defines the vertical position `Relative to the Parent Widget’s Height`.
      - `rely = 0.0` stands for **0% of Parent Widget's Height** i.e, `Top Edge`.
      - `rely = 0.5` stands for **50% of Parent Widget's Height** i.e, `Vertical Center`.
      - `rely = 1.0` stands for **100% of Parent Widget's Height** i.e, `Bottom Edge`. 
   -  `width`: Sets the Widget's `Width`.
   -  `height`: Sets the Widget's `Height`.
   -  `relwidth`: Defines Widget's Width as a `Fraction of the Parent’s Width`. (`0.0`(0%) to `1.0`(100%))
   -  `relheight`: Defines Widget's Height as a `Fraction of the Parent’s Height`. (`0.0`(0%) to `1.0`(100%))
   -  `anchor`: Sets the `Reference Point` for positioning. (`center`,`n`,`s`,`e`,`w`,etc.)
- **SAMPLE CODE:**
  ```
   import customtkinter as ctk
   app = ctk.CTk()

   # Define a Function "onClick" that is executed whenever the "button" is clicked
   def onClick():
      print("Hello User!");

   # Create a "CTkButton" and assign it to the "button" variable
   button = ctk.CTkButton(app, text="Click Me", command=onClick)

   # Place the "CTkButton" instance using the "place()" function 
   button.place(
       # x=200, y=150,         # Absolute position (unnecessary as "relx" and "rely" are being used!)
       relx=0.5, rely=0.5,     # Positions button at the absolute center of the Viewing Window
       # width=100, height=50  # Fixed size (unnecessary as "relwidth" and "relheight" are being used!)
       relwidth=0.2,           # Sets the relative width
       relheight=0.1,          # Sets the relative height
       anchor="center",        # Aligns the button to the "center"     
   )

   app.mainloop()   
  ```
<br>

### 3. grid(): 
- This method is used for arranging widgets in a `Table-Like` structure (i.e, `Rows` & `Columns`).
- It is ideal for `Form Layouts`, `Dashboards`, and `Structured UIs`.
- Core Attributes:
   -  `row`: Specifies the `Row` Number. (**0-Based Indexing**)
   -  `column`: Specifies the `Column` Number. (**0-Based Indexing**)
   -  `rowspan`: **Expands** widget across `Multiple Rows`.
   -  `columnspan`: **Expands** widget across `Multiple Columns`.
   -  `padx` and `pady`: Adds `Padding (Spacing)` around the widget.
   -  `ipadx` and `ipady`: Adds `Internal Padding` to the widget. Can be used for increasing the Widget's Size.
   -  `relwidth`: Defines Widget's Width as a `Fraction of the Parent’s Width`. (`0.0`(0%) to `1.0`(100%))
   -  `relheight`: Defines Widget's Height as a `Fraction of the Parent’s Height`. (`0.0`(0%) to `1.0`(100%))
   -  `sticky`: It is used for `Aligning` the Widget within its `Grid Cell`. (`center`,`n`,`s`,`e`,`w`,etc.)
- We can also use the `grid_rowconfigure()` and `grid_columnconfigure()` methods to control how **Rows and Columns Expand** inside another Widget or the Viewing Window.
   - `grid_rowconfigure(index, weight = value)`: Controls `Row Expansion`.
   - `grid_columnconfigure(index, weight = value)`: Controls `Column Expansion`.
   - **`NOTE`:** Setting `weight=1` allows `Resizing`, making the **row / column flexible**.  
- **SAMPLE CODE:**
  ```
   import customtkinter as ctk
   app = ctk.CTk()

   # Define a Function "onClick" that is executed whenever the "button" is clicked
   def onClick():
      print("Hello User!");

   # Create a "CTkButton" and assign it to the "button" variable
   button = ctk.CTkButton(app, text="Click Me", command=onClick)

   # Place the "CTkButton" instance using the "grid()" function
   button.grid(
      row=0, column=0,          # Position the button in row_0, column_0
      rowspan=1, columnspan=1,  # Span across 1 row and 1 column
      sticky="nsew",            # Expand in all directions
      padx=20, pady=20,         # External spacing
      ipadx=10, ipady=5         # Internal spacing
   )

   # Configure the Rows and Columns to allow Expansion
   app.grid_rowconfigure(0, weight=1)
   app.grid_columnconfigure(0, weight=1)

   app.mainloop()   
  ```
<br>

---

## Creating a Tabbed Interface using ttk.Notebook( ):
- A `Tabbed Interface` allows users to switch between different sections of a GUI using `Tabs`, similar to a Web Browser.
- In **Tkinter / Custom_Tkinter**, this can be achieved using `ttk.Notebook()` from the `tkinter.ttk` module.
- First, we need to **import** `Notebook` from `tkinter.ttk` module:
  ``` 
  from tkinter.ttk import Notebook
  ```
- Then, we need to create a `Notebook (Tab Container)`:
  ```
  notebook = Notebook(app)
  ```
- Finally, we need to **position** and **display** the notebook using `Layout Methods`:
  ```
  notebook.pack(expand=True, fill="both")
  ```
  <br>
  
### Important Notebook Functions:
- `add(<notebook_child>, text="Tab_name")`: Adds a new `Tab (Frame)` to the Notebook.
  ```
  notebook.add(tab1, text="Home")
  ```
- `select(<existing_notebook_child>)`: Switches to an existing `Tab (Frame)` which is specified in the arguments.
  ```
  notebook.select(tab1)
  ```
- `forget(<existing_notebook_child>")`: Completely removes an existing `Tab (Frame)` from the Notebook.
  ```
  notebook.forget(tab1)
  ```
- `hide(<existing_notebook_child>")`: Hides a Tab without deleting it (can be shown later using the `add()` Function).
  ```
  # Hide the Tab
  notebook.hide(tab1)

  # Display the Tab again
  notebook.add(tab1)
  ```
- `index(<existing_notebook_child>")`: Gets the `Numerical_Index` of a `Tab`.
  ```
  print(notebook.index(tab1)) # Output: 0 (if tab1 is the first tab)
  ```
- `tab(<existing_notebook_child>, attribute = "Value")`: It is used to `Get` or `Set` properties of a specific `Tab` **dynamically**.
  ```
  notebook.tab(tab1, text="New Home", state="normal", padding=[10, 5])
  ```
  **OR**<br>
  We can also use the `tab()` Function to get all the `Properties` of a specific `Tab` from the Notebook.
  ```
  tab_properties = notebook.tab(tab1)
  print(tab_properties)
  ```
- `enable_traversal()`: Allows users to switch between Tabs using `Ctrl+Tab` and `Ctrl+Shift+Tab`.
  ```
  notebook.enable_traversal()
  ```
- `instate(["state"], <command>)`: It is used to check whether a `Tab` is in a specific state like `disabled`, `selected`, or `normal`.
  ```
  if notebook.instate(["disabled"]):
     print("The Notebook is disabled.")
  ```
  **OR**
  ```
  def displayMessage():
     print("Tab is Selected from Notebook.")

  notebook.instate(["selected"], displayMessage)
  ```
<br>

---

## Styling ttk.Notebook( ) using ttk.Style( ) Function:
- The `ttk.Notebook()` widget creates Tabbed Interfaces, but its default style is quite basic. You can **Customize** it using the `ttk.Style()` class.
- **CODE:**
  ```
  # Create an instance of the "ttk.Style()" class
  style = ttk.Style()
  
  # Configure the "ttk.Notebook()" Attributes
  style.configure("TNotebook", background="#2e2e2e", foreground="#000000", borderwidth=0, padding=[0, 1])  

  # Style the ttk.Notebook() "Tabs (Frames)"
  style.configure("TNotebook.Tab", background="#242424", foreground="#ffc300", padding=[10, 6], font=("Comic Sans MS", 10, "normal"), corner_radius=0)  

  # Configure the "Selected Tab's" Attributes
  style.map("TNotebook.Tab", background=[("selected", "#1d1d1d")], foreground=[("selected", "#ffd60a")], borderwidth="0")
  ```
<br>

---
<br>

## Packaging a Python Script into a Standalone (.exe) using PyInstaller:
### What is PyInstaller?
- `PyInstaller` is a Python tool that packages **Python Scripts** into **Standalone Executable (`.exe`)** files.
- This allows you to run Python programs **without requiring Python to be installed** on your system.
- It is **Customizable** i.e, we can add `Icons`,`Hidden Imports`, and `Additional Files`.
<br>

### PyInstaller Installation:
- Paste the following prompt in your **Terminal** to install `PyInstaller`:
  ```
  pip install pyinstaller
  ```
<br>

### Packaging a Python Script:
- Paste the following prompt in your **Terminal** to package a `Python Script` into `Standalone Executable (.exe)`:
  ```
  pyinstaller --onefile --noconsole --icon=<filepath> --add-data "<filepath>" <filename>.py
  ```
  **`Note:`** Replace `<filename>` with your `Python_Script's` Name which you want to be bundled and `<filepath>` with your `Application_Icon's` File Path.
<br>

### PyInstaller Flags:
|Sr. No. |PyInstaller Flag                                            |Description                                                                                       |
|--------|------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
|1       |`--onefile`                                                 |Create a single **executable (.exe)**.                                                            |
|2       |`--noconsole`                                               |Hides **Console Window** (for GUI).                                                               |
|3       |`--icon=<filepath>`                                         |Set **Custom Icon** for the executable.                                                           |
|4       |`--add-data "<filepath>"`                                   |Adds **additional files and resources** to the bundled executable.                                |

<br>

---
<br>

## Packaging a Python Script into a Standalone (.exe) using Nuitka:
### What is Nuitka?
- `Nuitka` is a **Python Compiler** that translates your scripts into `C code`, creating a highly optimized **Standalone Executable** (`.exe`).
- This allows you to distribute and run `Python` programs without requiring Python to be installed on the target system.
- It is highly customizable, allowing you to **embed** `icons`, **include** `data files`, and **manage** `dependencies` with plugins.
<br>

### Nuitka Installation:
- Paste the following prompt in your **Terminal** to install `Nuitka`:
  ```
  pip install nuitka
  ```
<br>

### Packaging a Python Script:
- Paste the following prompt in your **Terminal** to package a `Python Script` into `Standalone Executable (.exe)`:
  ```
    nuitka --standalone --enable-plugin=<pluginName> --include-data-dir=<source>=<destination> --windows-icon-from-ico=<filepath> --windows-console-mode=disable <filename>.py    
  ```
  **`Note:`** Replace `<filename>` with your `Python_Script's` Name which you want to be bundled and `<filepath>` with your `Application_Icon's` File Path.
<br>

### Nuitka Flags:
|Sr. No. |PyInstaller Flag                                            |Description                                                                                       |
|--------|------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
|1       |`--standalone`                                              |Create a single **executable (.exe)**.                                                         |
|2       |`--enable-plugin=<pluginName>`                              |Hides **Console Window** (for GUI).                                              |
|3       |`--include-data-dir=<source>=<destination>`                 |Set **Custom Icon** for the executable.                                   |
|4       |`--windows-icon-from-ico=<filepath>`                        |Adds **additional files and resources** to the bundled executable.                     |
|5       |`--windows-console-mode=disable`                            |Adds **additional files and resources** to the bundled executable.                     |

<br>

---

