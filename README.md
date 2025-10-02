# 🎉 AKConverter

**AKConverter** is a Windows desktop application that allows you to easily convert various file and media formats.The language is not specified because it is in a rar file. This is a C# program.

---

## ⚠️ IMPORTANT: FFmpeg REQUIRED!

Some conversions require **FFmpeg**:  


**For easy setup, download the official 3 EXE package:**

[💻 FFmpeg Windows 64-bit (3 EXE) – Official Package](https://github.com/BtbN/FFmpeg-Builds/releases/download/latest/ffmpeg-master-latest-win64-gpl.zip)  

**Steps to use:**
1. Download and extract the zip file.  
2. Place the `ffmpeg.exe`, `ffplay.exe`, and `ffprobe.exe` files in the same folder as Mega File Converter.  
3. Now all conversions that require FFmpeg will work directly! 🚀  

---

## 🛠️ How to Use

1. Run AKConverter.  
2. Select the source file or folder.  
3. Choose the conversion type.  
4. Select the output location and click the `Convert` button.  
5. Monitor the conversion status in the log panel.
6. DONT FORGET FFMPEG!!!  

---

✅ Requirements

- Windows 10 or higher  
- .NET Framework 4.8 (or compatible)  
- FFmpeg (required for some conversions)  
- LibreOffice (recommended for DOCX → PDF conversion)

##Supported Conversions

- PNG → JPG
- JPG → PNG
- WEBP → PNG (FFmpeg required)
- GIF → PNG (first frame only)
- BMP → PNG
- ICO → PNG (first icon only)
- MP4 → MP3 (FFmpeg required)
- MP3 → WAV (FFmpeg required)
- AVI → MP4 (FFmpeg required)
- ZIP → Folder (extract files)
- Folder → ZIP (compress folder)
- CSV → XLSX
- XLSX → CSV
- TXT → JSON (each line as array element)
- DOCX → PDF (LibreOffice recommended) 

---

## 📄 License

This project is licensed under the MIT License.
