# Campus-Maintenance-System-C
A colorful, terminal-based Campus Maintenance Management System built in C, featuring persistent file I/O and report generation.*

## 💡 Project Overview
This project is a coursework for my **COM102: Programming Language C** course. It is a lightweight Campus Maintenance Management System designed to handle repair requests, dispatch technicians, and generate formatted summary reports. 

While it fulfills the academic requirements of a standard C assignment, I treated it as a professional engineering simulation by incorporating custom ANSI color coding for the terminal UI, persistent local file I/O (database generation), and robust memory/error handling.

### 🔍 A Note on "Requirements Traceability"
If you explore the source code (`main.c`), you will notice specific inline comments such as `// [Page 3, Section 1]`. 

These annotations map directly to the strict assignment specifications provided in the `Description of Assignment.pdf`. I intentionally preserved these comments to demonstrate **Requirements Traceability**—showing exactly how each block of logic and data structure fulfills the "client's" specific business requirements.

## 🛠️ Tech Stack & Features
* **Language:** C (Standard Library)
* **Core Concepts Used:** Structs, File I/O Operations, Pointer Manipulation, Custom UI Formatting.
* **Features:**
  - Create, view, and assign maintenance requests.
  - Persistent data storage (reads/writes to `.txt` databases).
  - Generates automated formatted reports for 'NEW' requests.
  - Colorful Terminal UI to break the monotony of standard console applications.

## 🚀 How to Run
To compile and run this system on your machine:
1. Ensure you have a C compiler installed (like GCC).
2. Clone this repository and navigate to the folder.
3. Compile the code:
   ```bash
   gcc main.c -o campus_maintenance
4. Run the executable:
   ```bash
   ./campus_maintenance
   ```

*(Note: The program will automatically generate `all_data_db.txt` and `new_requests.txt` in the same directory upon running.)*

## 📁 Repository Structure
* `main.c`: The core source code featuring strict requirement mappings.
* `Description of Assignment.pdf`: The original "Client Requirements" / Assignment specification.
* `Campus-Maintenance-System-C.pdf`: My comprehensive system design, logic flowchart, and testing report.

## 🙏 Acknowledgements
* **The Ultimate MVP:** A very special thank you to my favorite person and best "Chief Technical Mentor", [Noelle1831-k](https://github.com/Noelle1831-k). As a freshman navigating the world of programming, having a brilliant Master's student to guide (and tolerate) my endless bugs made all the difference. Thank you for debugging with me, keeping me sane through pointer arithmetic, and being my unconditional supporter! ❤️

## 📬 Contact Information
* **Email:** wlan9509@gmail.com
* **Personal WeChat:** Cynthia_wlan9509
* **GitHub:** [Cynthia-wlan9509](https://github.com/Cynthia-wlan9509)
