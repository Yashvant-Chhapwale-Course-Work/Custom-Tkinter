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
| 4.  **Custom-Tkinter Window Geometry(Width x Height)**                                                         | >> [` CHECK CONTENT `](#adjusting-custom_tkinter_window-dimensions)                           |
| 5.  **Creating Custom-Tkinter Window Instance (CTk( ))**                                                       | >> [` CHECK CONTENT `](#creating-custom_tkinter_window_instance-CTk)                          |
| 6.  **Set Application Logo i.e, Window Icon**                                                                  | >> [` CHECK CONTENT `](#setting-window-icon)                                                  |
| 7.  **Custom-Tkinter Frames and Scrollable-Frames**                                                            | >> [` CHECK CONTENT `](#creating-custom_tkinter-frames-and-scrollable_frames)                 |
| 8.  **Displaying Text and Images using Custom-Tkinter Labels**                                                 | >> [` CHECK CONTENT `](#creating-custom_tkinter-labels-for-displaying-text-and-images)        |
| 9.  **Custom-Tkinter Buttons and Segmented-Buttons**                                                           | >> [` CHECK CONTENT `](#creating-custom_tkinter-buttons-and-segmented_buttons)                |
| 10. **Custom-Tkinter Check_Box and Combo_Box**                                                                 | >> [` CHECK CONTENT `](#creating-custom_tkinter-check_box-and-combo_box)                      |

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


