# 🎨 Image to Colored ASCII Art  

Convert images into **colored ASCII art** directly in Python (Jupyter/Kaggle notebooks).  
This mini-project demonstrates how to process images, map pixels to ASCII characters, and preserve colors for a vibrant output.  

---

## ✨ Features  
- 🖼️ Converts any image into colored ASCII art  
- 🎨 Preserves original RGB colors  
- 📏 Adjustable output size (width, font size, line height)  
- 💾 Saves output as an **HTML file** for easy sharing  
- ⚡ Runs seamlessly on **Kaggle/Jupyter Notebooks**  

---

## 📂 Project Structure  

```bash
Image-to-ASCII-Art/
│
├── input/
│   └── dog-image-2/
│       └── dog.jpeg              # Example input image
│
├── output/
│   └── ascii_art_colored.html    # Generated ASCII art (HTML file)
│
├── ascii_art.py                  # Main Python script / notebook code
│
└── README.md                     # Project documentation

```
## 🚀 How to Run  

### 1️⃣ Install dependencies  

pip install pillow

### 2️⃣ Upload your image (example path in Kaggle)
/kaggle/input/dog-image-2/dog.jpeg

### 3️⃣ Run the script
image_to_colored_ascii("/kaggle/input/dog-image-2/dog.jpeg",
                       width=60, font_size=10, line_height=10)

### 4️⃣ View results
✅ ASCII art is displayed inside the notebook
✅ An HTML file (ascii_art_colored.html) is saved and can be downloaded
