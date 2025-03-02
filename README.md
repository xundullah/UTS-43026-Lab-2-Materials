# **🚀 Economic Dispatch of Generators in a Power System**  
## **43026 Energy Economics, Optimisation and Policy - Autumn 2025**  
### **Optimisation Approaches Using Python**  

![Python](https://img.shields.io/badge/Python-3.x-blue.svg) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg) ![Google Colab](https://img.shields.io/badge/Google-Colab-yellow.svg)  

---

## **📌 Overview**  

The **economic dispatch** problem involves distributing power generation among multiple generators at the **lowest cost** while ensuring that the **total power demand is met**. This repository contains **four Jupyter Notebook labs** that explore different mathematical optimisation approaches to solve this problem.  

### **🔢 Optimisation Techniques Covered:**  
✅ **Linear Programming (LP)** – Basic cost minimisation using linear constraints.  
✅ **Quadratic Programming (QP)** – More realistic cost modelling with quadratic terms.  
✅ **Nonlinear Programming (NLP)** – Incorporating cubic cost functions for greater accuracy.  
✅ **Integer Programming (IP)** – Power dispatch in fixed discrete increments for real-world applicability.  

---

## **📂 Lab Contents**  

| Lab No. | Optimisation Type | Description | Notebook File |
|---------|------------------|-------------|---------------|
| **Lab 2-1** | Linear Programming (LP) | Basic cost minimisation with linear functions | [Lab2.1.ipynb](https://github.com/xundullah/UTS-43026-Lab-2-Materials/blob/main/Lab2.1.ipynb) |
| **Lab 2-2** | Quadratic Programming (QP) | More realistic cost modelling with quadratic terms | [Lab2.2.ipynb](https://github.com/xundullah/UTS-43026-Lab-2-Materials/blob/main/Lab2.2.ipynb) |
| **Lab 2-3** | Nonlinear Programming (NLP) | Cost modelling using linear, quadratic, and cubic functions | [Lab2.3.ipynb](https://github.com/xundullah/UTS-43026-Lab-2-Materials/blob/main/Lab2.3.ipynb) |
| **Lab 2-4** | Integer Programming (IP) | Power dispatch with integer-based allocations | [Lab2.4.ipynb](https://github.com/xundullah/UTS-43026-Lab-2-Materials/blob/main/Lab2.4.ipynb) |

---

## **🚀 Running the Labs in Google Colab**  

You can easily run these labs in **Google Colab** without requiring any local setup. Follow these steps:  

### **📌 Step 1: Open Google Colab**  
Go to **[Google Colab](https://colab.research.google.com/)**.

### **📌 Step 2: Open a Notebook from GitHub**  
- Click on **File** → **Open Notebook**.  
- Select the **GitHub** tab.  
- Paste this repository link:  
  ```plaintext
  https://github.com/xundullah/UTS-43026-Lab-2-Materials
  ```
- Select the desired notebook (**Lab2.1.ipynb**, **Lab2.2.ipynb**, **Lab2.3.ipynb**, or **Lab2.4.ipynb**).  
- Click **Open Notebook**.

### **📌 Step 3: Run the Notebook**  
Once the notebook opens, click **Runtime** → **Run all** to execute all cells.

---

## **📖 Lab Details**  

### **Lab 2-1: Linear Programming Approach**  
🔹 **Objective**: Solve economic dispatch using **Linear Programming (LP)**.  
🔹 **Key Concepts**:  
- Models generator costs as **linear functions**.  
- Power generation is **continuous** within limits.  
- Uses **`scipy.optimize.linprog`** for solving LP.  

---

### **Lab 2-2: Quadratic Programming Approach**  
🔹 **Objective**: Solve economic dispatch using **Quadratic Programming (QP)**.  
🔹 **Key Concepts**:  
- Models generator costs using **linear + quadratic terms**.  
- More realistic cost structure with **diminishing returns**.  
- Uses **`scipy.optimize.minimize`** with **trust-constr** method.  

---

### **Lab 2-3: Nonlinear Programming Approach**  
🔹 **Objective**: Solve economic dispatch using **Nonlinear Programming (NLP)**.  
🔹 **Key Concepts**:  
- Models generator costs with **linear, quadratic, and cubic components**.  
- Captures **nonlinear fuel consumption patterns**.  
- Uses **`scipy.optimize.minimize`** with **SLSQP method**.  

---

### **Lab 2-4: Integer Programming Approach**  
🔹 **Objective**: Solve economic dispatch using **Integer Programming (IP)**.  
🔹 **Key Concepts**:  
- Models power generation as **integer variables** (e.g., 10 MW increments).  
- More realistic for **practical power dispatch**.  
- Uses **`scipy.optimize.milp`** for integer-based optimisation.  

---

## **🛠 Dependencies & Installation**  

These labs require **Python 3.x** and the following packages:  
```bash
pip install numpy scipy matplotlib
```

However, if using **Google Colab**, these dependencies are **pre-installed**, and no setup is required.  

---

## **📜 License**  
This project is licensed under the **MIT License**. Feel free to use, modify, and share.  

---

## **📬 Contact & Support**  
If you have any questions or issues, feel free to open an issue on GitHub or reach out to:   
🔗 GitHub: [xundullah](https://github.com/xundullah)  
