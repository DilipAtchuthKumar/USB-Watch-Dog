# 🛡️ USB Watch Dog  

## 🔍 Overview  
**USB Watch Dog** is a Python-based security tool designed to manage and control USB port access on a computer. By allowing users to enable or disable USB ports as needed, it helps prevent unauthorized device connections, data theft, and potential malware infections via USB drives.  

The application features a **password-protected GUI**, ensuring that only authorized users can modify USB access settings. With a sleek Tkinter interface and visual enhancements, **USB Watch Dog** provides both security and usability in one package.  

---

## ⚙️ Features  
- 🔒 **Password Protection:** Secure USB control actions behind a password to prevent unauthorized changes.  
- 🔌 **Enable/Disable USB Ports:** Quickly block or unblock USB access with a single click.  
- 🖥️ **Interactive GUI:** Built with Tkinter, featuring custom backgrounds, button hover effects, and an intuitive layout.  
- 📄 **Project Info Page:** A dedicated button opens an HTML file containing detailed project information.  

---

## 🧩 Installation  

1. **Clone this repository:**  
   ```bash
   git clone https://github.com/DilipAtchuthKumar/usb-watch-dog.git
   cd usb-watch-dog
   
2. **Install the required dependencies.**
   ```bash
   pip install Pillow

3. **Ensure you have the necessary batch files:**
    - block_usb.bat: To disable USB ports.
    - unblock_usb.bat: To enable USB ports.
      
(Update the file paths in the Python script as needed.)

4. **Add your project information page:**
Create a file named project_info.html containing your project details, and place it in the main directory.

## 🚀 Usage
1. **Run the script:**
   ```bash
   python usb_watch_dog.py

2. **The GUI will open, allowing you to:**
    - Disable USB ports (password-protected).
    - Enable USB ports (password-protected).
    - View project information in an HTML file.

3. **The password for accessing the enable/disable functionality can be set by modifying the password variable in the code.**


## 🖼️ Screenshots
Main Interface

![image](https://github.com/user-attachments/assets/8e85ce21-59dc-48df-9ec7-26d889ca7944)

## 📁 Project Structure
    usb-physical-security/
    │
    ├── usb_watch_dog.py            # Main Python script for the GUI
    ├── block_usb.bat               # Batch file to disable USB ports
    ├── unblock_usb.bat             # Batch file to enable USB ports
    ├── project_info.html           # HTML file containing project information
    └── wallpaper.png               # Background image for the GUI

## 🧠 Dependencies
- Python 3.x
- Tkinter
- Pillow (for image handling)
- Webbrowser (for opening project info)
- Subprocess (for running batch files)

Install dependencies via:

    pip install Pillow

## 🤝 Contributing
Contributions are always welcome!
If you’d like to improve USB Watch Dog, feel free to fork the repository and submit a pull request.
Feedback, suggestions, and feature ideas are greatly appreciated.

