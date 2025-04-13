# 🔺 Triangle Translation – Computer Graphics
This project demonstrates how to **translate a triangle** using a **direction vector** in Python.  
It is part of basic **Computer Graphics lab**, helping visualize 2D geometric transformations.

> 📍 Implemented using **Python** and **Matplotlib**

## 📌 **Algorithm**
The program follows these steps:
1. ✏️ Define a function `translateTriangle()` that takes the coordinates of the triangle's vertices and the translation vector as input  
2. ➕ Calculate the coordinates of the **translated triangle** by adding the translation vector to each vertex  
3. 🧾 Use **Matplotlib** to plot both the original and translated triangles  
4. 🧑‍💻 Prompt the user to enter:
   - Coordinates of the triangle (`X1, Y1`, `X2, Y2`, `X3, Y3`)  
   - Direction vector components (`X`, `Y`)  
5. 🧠 Call the function to **translate and visualize** the result

---

## 🚀 **Usage**
To run the code:
```bash
# Run the Python script
python triangle_translation.py

📥 We'll be prompted to input:
Coordinates of the 3 triangle vertices
Translation vector (X, Y)

📈 After that, the original and translated triangles will be displayed using Matplotlib.
🧪 Example

Example input:
🔄 Translation Example:
A triangle translated using vector V = 5i + 3j

Enter the value of X1: 1  
Enter the value of Y1: 2  
Enter the value of X2: 3  
Enter the value of Y2: 4  
Enter the value of X3: 5  
Enter the value of Y3: 6  
Enter vector X: 5  
Enter vector Y: 3

📊 The program will plot the original and translated triangle.

💻 Requirements
- Python 3.x
- Matplotlib
- Install the required library with:

bash
pip install matplotlib

📜 License
This project is licensed under the MIT License – free to use for educational purposes.
