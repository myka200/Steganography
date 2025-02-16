# Secure Image Steganography

This project implements **LSB (Least Significant Bit) steganography** to **hide and extract secret messages** in images. It allows users to embed messages inside images without visible distortion.

---

## 📌 Features
✅ Hide text messages inside images  
✅ Extract hidden messages from stego images  
✅ Uses **LSB steganography** (modifies pixel values subtly)  
✅ Works with **PNG images** (lossless compression)  

---

## 🔧 Installation
Ensure you have **Python 3.x** installed. Then, install the required libraries:  
```bash
pip install opencv-python numpy pillow
```

---

## 🚀 Usage
### **🔹 To Hide a Message in an Image**
Run the following command:  
```bash
python steganography.py --encode
```
- You will be asked to enter the **image file** and **secret message**.  
- The script will generate a **stego image** with the hidden message.  

### **🔹 To Extract the Hidden Message**
Run the following command:  
```bash
python steganography.py --decode
```
- Enter the **stego image filename** when prompted.  
- The script will **reveal the hidden message**.

---

## 📌 Example Output
### **Hiding a Message**
```
$ python steganography.py --encode
Enter the input image filename: landscape.png
Enter the secret message: Dark Matter
Message hidden successfully in stego_image_with_secret.png
```

### **Extracting the Hidden Message**
```
$ python steganography.py --decode
Enter the stego image filename: stego_image_with_secret.png
Hidden Message: Dark Matter
```

---

## 📂 File Structure
```
/steganography_project
│── README.md
│── steganography.py
│── landscape.png
│── stego_image_with_secret.png
```

---

## 🛠 Future Enhancements
- Add **encryption for additional security**  
- Implement **GUI version (Tkinter or Flask)**  
- Expand to **video/audio steganography**  

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 🤝 Contribution
Feel free to contribute by submitting a **pull request** or reporting issues.  

---

## 💡 Author
Developed by **Anamika Agarwal**  
For inquiries, contact **anamikaagarwal506@gmail.com**

