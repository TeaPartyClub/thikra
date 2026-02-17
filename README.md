# ذكرى Thikra
# 🎞️ FilmStrip: Instant Negative Developer

> **Turn your film negatives into digital photos instantly, right in your browser.**

<img width="2344" height="1332" alt="image" src="https://github.com/user-attachments/assets/07f6ed7b-8c2f-41e2-b966-b8d268ec2462" />

## 🚀 Overview

**FilmStrip** is a client-side web application designed to democratize film development. Traditional photo studios can charge up to **50 SAR** just to scan and process negatives. We believe you should be able to do this comfortably at home for **free**.

Built in a single-day sprint by a team of three developers, this tool leverages the power of the **HTML5 Canvas API** to process image data in real-time without ever sending your photos to a server.

### 🌟 Key Features
* **Instant Inversion:** Converts negative film strips (color or B&W) to positive images.
* **Privacy First:** All processing happens in your browser. No images are uploaded to a cloud.
* **Fine-Tuning Controls:** Adjust Exposure, Contrast, and Color Temperature to get the perfect look.
* **Export:** Download your developed photos in high resolution.
* **Mobile Friendly:** Works on smartphones for "scan and go" functionality.

## 🛠️ Tech Stack

* **Frontend:** React.js (Vite)
* **Styling:** Tailwind CSS
* **Image Processing:** HTML5 Canvas API & Custom Pixel Manipulation Algorithms
* **Deployment:** Vercel / GitHub Pages

## 🏁 Getting Started

Follow these instructions to set up the project locally on your machine.

### Prerequisites
* Node.js (v14 or higher)
* npm or yarn

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/filmstrip-app.git](https://github.com/your-username/filmstrip-app.git)
    cd filmstrip-app
    ```

2.  **Install dependencies**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Start the development server**
    ```bash
    npm run dev
    # or
    yarn dev
    ```

4.  **Open your browser**
    Navigate to `https://thikra.vercel.app/` (or the port shown in your terminal).

## 📸 How to Use

1.  **Backlight your negative:** Place your film strip against a white screen (phone or laptop with a white background).
2.  **Upload/Snap:** Take a photo of the negative using this web app, or upload an existing image file.
3.  **Develop:** The app automatically inverts the colors.
4.  **Edit:** Use the sliders to correct the "Orange Mask" (cyan tint) and adjust brightness.
5.  **Save:** Click download to save your new digital memory!

## 🤝 The Team

Built with ❤️ by:

* **[@173p](https://github.com/173p)**
* **[@rubaian](https://github.com/rubaian)** 


## 🔮 Future Roadmap

* [ ] **Auto-Color Correction:** Algorithm to automatically detect and remove the orange film mask.
* [ ] **Batch Processing:** Upload multiple images at once.
* [ ] **Crop & Rotate:** Basic editing tools before processing.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Project initiated on [17/02/2026] as a rapid-prototype solution to accessible film photography.*
