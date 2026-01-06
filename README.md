# 🥷 Ninja Archive 3.2 - A ClassDojo Photo, Video and Post Downloader Extension for Chromium Based Browsers, Google Chrome, Microsoft Edge

**Ninja Archive** is a simple, privacy-friendly browser extension for **Chromium-based browsers** (Chrome, Edge, Brave, etc.).  
It allows parents and guardians to **archive all their child’s ClassDojo Story content** — including photos, videos, PDFs, captions, and full JSON metadata — automatically organised by date.

---

## ✨ Features

- 📅 **Date range filtering** – choose the period you wish to download  
- 🖼️ **Photos** – automatically saved as JPG/PNG files  
- 🎥 **Videos** – saved in their original MP4 format  
- 📄 **PDFs** – download
- 🧾 **Story text export** – captions, teacher names, and post text saved in plain-text `.txt` archives  
- 💾 **JSON archive** – full raw post data (`data.json`) included for reference  
- 🗂️ **Automatic folder sorting** – all files neatly organised by day under  
  `ClassDojo Downloads/YYYY-MM-DD/`  
- 🧠 **No external servers** – all processing runs locally in your browser  

---

## 🔒 Permissions

The extension only requests access to the specific ClassDojo domains required for content retrieval:
home.classdojo.com
sphotos.classdojo.com
svideos.classdojo.com

---

## 🧭 Installation (Chromium browsers)

1. Download the latest ZIP release from the [**Releases page**](https://github.com/8bitwilliam/Ninja/releases).  
2. Unzip the archive to a convenient folder.  
3. Open your browser’s extensions page:  
   - **Chrome** → `chrome://extensions/`  
   - **Edge** → `edge://extensions/`  
4. Enable **Developer Mode** (toggle in the top-right).  
5. Click **Load unpacked** and select the extracted folder containing `manifest.json`.  
6. You’ll now see the **🥷 Ninja Archive** icon appear in your browser toolbar.  

---

## ▶️ Usage

1. Log in to **ClassDojo** as a parent or guardian.  
2. Navigate to your child’s **Story** page.  
3. Click the **Ninja Archive** icon in your browser's extension icon or toolbar.   
4. Choose a start and end date.  
5. Click **Download**.  

The extension will:  
- Automatically scan the Story feed  
- Download all attachments (photos, videos, PDFs)  
- Create `.txt` files containing the teacher name and story text with filenames. 
- Generate a `data.json` file containing the full metadata for all posts  

---

## 📁 Output Example
ClassDojo Downloads/

├── 2025-10-14/

│   ├── 2025-10-14_photo_abc123.jpg

│   ├── 2025-10-14_video_456xyz.mp4

│   └── 2025-10-14.txt

├── 2025-10-15/

│   ├── 2025-10-15_photo_789lmn.jpg

│   ├── 2025-10-15.txt

└── data.json


Each folder represents a single day’s posts.  
Every `.txt` file summarises the teacher, story caption, and linked attachments.

---

## 🧩 Technical Notes

- **Manifest V3** – fully Chrome/Edge-compliant  
- **All local** – no cloud services or tracking  
- **Region-aware** – 🇬🇧 🇦🇺 🇳🇿 🇨🇦 🇺🇸 🇪🇺 - supports multiple ClassDojo content formats  
