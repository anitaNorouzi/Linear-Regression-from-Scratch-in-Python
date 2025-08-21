# Linear-Regression-from-Scratch-in-Python

Looking for code that matches the equation exactly, **without any frameworks**?  
This is it!
I wrote it to see what’s happening behind the scenes.  


---


## 🚀 Features
- Implementation of:
  - Cost function (Mean Squared Error)
  - Gradient computation
  - Batch Gradient Descent optimizer
- Works with **multiple features (n > 1)**  
- Includes visualization of **cost vs. iterations**  
- No machine learning libraries used — just pure Python + NumPy  

## ⚙️ How It Works
1. **Initialize parameters** `w` (weights) and `b` (bias).  
2. **Compute predictions**:  
   \[
   f(x) = w \cdot x + b
   \]
3. **Compute cost** (Mean Squared Error).  
4. **Update parameters** with gradient descent:  
   \[
   w := w - \alpha \frac{\partial J}{\partial w}, \quad
   b := b - \alpha \frac{\partial J}{\partial b}
   \]
5. Repeat for a set number of iterations.  

---

## 📊 Example Output
- Initial weights and bias  
- Cost decreasing over iterations  
- Final trained parameters  
![Logo](Images/Screenshot%202025-08-21%20133908.png)

---

## 🔧 Requirements
- Python 3.x
- NumPy
- Matplotlib (for optional plotting)

Install dependencies:
```bash
pip install numpy matplotlib
