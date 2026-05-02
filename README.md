# 🎵 MP3 Tag Reader & Editor in C

## 📌 Overview
This project is a command-line based MP3 Tag Reader and Editor developed in C. It reads and modifies ID3 metadata tags such as Title, Artist, Album, Year, Genre, and Comments from MP3 files.

## 🚀 Features
- View MP3 metadata (ID3 tags)
- Edit metadata fields
- Supports:
  - Title (TIT2)
  - Artist (TPE1)
  - Album (TALB)
  - Year (TYER)
  - Genre (TCON)
  - Comments (COMM)

## 🛠️ Technologies Used
- C Programming
- File Handling (fopen, fread, fwrite)
- String manipulation

## ⚙️ How It Works
1. Reads MP3 file header
2. Verifies "ID3" format
3. Extracts tag frames
4. Displays or edits tag values

## ▶️ Usage

### Compile:
```bash
gcc main.c view.c edit.c -o mp3_tag

## 📷 Sample Output



## 🔗 GitHub Repository
https://github.com/Mwriky/mp3-tag-reader-c
