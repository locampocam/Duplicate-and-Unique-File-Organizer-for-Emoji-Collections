# 🎨 Duplicate and Unique File Organizer for Local Files

This Python script helps organize emoji image collections by identifying duplicate and unique files. It ensures that your collection remains clean and well-organized by separating repeated files from unique ones.

## 📌 Features

- ✅ Extracts file names from a specified folder, ignoring file extensions.  
- ✅ Compares extracted names with a reference list to detect duplicates.  
- ✅ Moves duplicate files to a designated folder.  
- ✅ Creates a new folder for unique files that do not match the reference list.  
- ✅ Outputs a `.txt` file containing all unique file names.  

## 🚀 How It Works

1. Place the emoji images inside the `emogi` folder.  
2. Run the script to generate a list of filenames (`nombres.txt`).  
3. Provide a second list (`nombres_discord.txt`) to compare names.  
4. The script will:
   - Move duplicate files to the `duplicados` folder.
   - Keep unique files in the `no_duplicados` folder.

## 🛠 Requirements

- Python 3.x  
- `shutil` and `os` (standard Python libraries)  

## 📂 Folder Structure
📁 Project Folder │── 📁 emogi # Folder containing emoji images │── 📁 duplicados # Folder where duplicate files are moved │── 📁 no_duplicados # Folder where unique files are stored │── 📄 nombres.txt # List of all filenames (without extensions) │── 📄 nombres_discord.txt # Second list of filenames for comparison │── 📜 script.py # Main script to execute


## 💡 Why Use This?

If you manage a large collection of emojis and want to avoid duplicates, this tool helps automate the process, saving time and effort.

---

🎉 **Keep your emoji collection clean and duplicate-free!** 🎉
