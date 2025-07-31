C Project in Google Colab

This repository contains a C/C++ programming project written, compiled, and executed in **Google Colab**.
It shows how you can use Google Colab — typically a Python environment — to work with C/C++ code using shell commands.

---

 Project Overview

-  Language: C 
-  Platform: Google Colab
-  File: `C_Project.ipynb`

This notebook demonstrates how to:
- Write C code directly inside Colab
- Compile it using `!gcc` (for C) 
- Run the output program and view results in-line
- Practice logic and implementation without needing a local IDE

---

 Run on Google Colab

You can open and run this notebook on Google Colab with just a click:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YourUsername/YourRepoName/blob/main/C_Project.ipynb)

---

 File Description

| File Name         | Description                          |
|------------------|--------------------------------------|
| `C_Project.ipynb` | Main Colab notebook with C/C++ code |

---

How It Works

```cpp
%%writefile program.c   // Save C code to a file
!gcc program.c -o output  // Compile it
!./output                // Execute the compiled binary
