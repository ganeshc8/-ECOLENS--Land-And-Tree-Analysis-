# 🌱 EcoLens: Tree and Land Segmentation

EcoLens is a deep learning-based application built with **TensorFlow** and **Streamlit** for aerial image segmentation.  
It helps in identifying and mapping trees, land, roads, and buildings from drone or satellite images.

---

## 🚀 Features
- Upload aerial images (`.jpg`, `.jpeg`, `.png`).
- Perform semantic segmentation into:
  - Background clutter (Grey)
  - Building (Red)
  - Road (Yellow)
  - Tree (Green)
  - Small Land (Magenta)
- View **segmentation mask** and **overlay** on the original image.
- Built with **Streamlit** for easy web-based interaction.

---

## 📂 Project Structure
```
EcoLens/
│── best_model.keras       # Trained deep learning segmentation model
│── app.py                 # Streamlit app (main script)
│── README.md              # Documentation
```

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ecolens.git
   cd ecolens
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate    # On Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 📦 Requirements

Your `requirements.txt` should include:
```
streamlit
tensorflow
numpy
pillow
matplotlib
```

Install via:
```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the Streamlit app:
```bash
streamlit run app.py
```

Then, open the local server link in your browser (e.g., `http://localhost:8501`).

---

## 🖼️ Example

1. Upload an aerial image.
2. View predicted segmentation mask.
3. Compare overlay on the original image.

Example Output:

- **Uploaded Image**  
  (Original aerial photo)

- **Predicted Segmentation**  
  (Color-coded mask with class labels)

- **Overlay on Original Image**  
  (Blended visualization of segmentation + original image)

---

## 🎨 Class Labels and Colors

| Class               | Color  |
|----------------------|--------|
| Background clutter   | Grey   |
| Building             | Red    |
| Road                 | Yellow |
| Tree                 | Green  |
| Small Land           | Magenta|

---

## 🛠️ Tech Stack
- **Frontend**: Streamlit
- **Backend**: TensorFlow (Deep Learning model)
- **Languages**: Python
- **Visualization**: Matplotlib, Pillow

---

## 📌 Notes
- Ensure that `best_model.keras` is present in the project root directory.
- Model should be trained on aerial image segmentation datasets.

---

## 🤝 Contributing
Contributions are welcome! Feel free to submit a Pull Request.

---

## 📜 License
This project is licensed under the MIT License.

---

### 👨‍💻 Author
Developed as part of **EcoLens Project** for AI-powered tree and land analysis.

