# Secure Image Steganography 🔍🖼️

This project implements **Least Significant Bit (LSB) steganography** to **hide and extract secret messages** within images. It modifies pixel values slightly, making the changes undetectable to the human eye.

---

## 📌 Features
✅ Hide secret text messages inside images  
✅ Extract hidden messages from stego images  
✅ Uses **LSB steganography** (modifies pixel values subtly)  
✅ Works with **PNG images** (lossless compression)  
✅ No visible changes to the image after encoding  

---

## 🔧 Installation
Ensure you have **Python 3.x** installed. Then, install the required dependencies:  
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
- The script will load `landscape.png`, hide the message, and save `stego_image_with_secret.png`.  

### **🔹 To Extract the Hidden Message**
Run the following command:  
```bash
python steganography.py --decode
```
- The script will read `stego_image_with_secret.png` and reveal the hidden message.  

---

## 📌 Example Output
### **Hiding a Message**
```
$ python steganography.py --encode
Data hidden successfully.
```
### **Extracting the Hidden Message**
```
$ python steganography.py --decode
Hidden Message: Dark Matter
```

---

## 📂 File Structure
```
/steganography_project
│── README.md
│── steganography.py
│── landscape.png            # Input image
│── stego_image_with_secret.png  # Image with hidden data
```

---

## 🛠 Future Enhancements
- Add **encryption before hiding data** for extra security  
- Implement **GUI version (Tkinter or Flask)**  
- Support **different image formats (JPEG, BMP, etc.)**  

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 💡 Author
Developed by **Anamika Agarwal**  
For inquiries, contact **anamikaagarwal506@gmail.com**

