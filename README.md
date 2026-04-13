

# ArchitectMD | High-Performance Resume Engine

**ArchitectMD** is a browser-native, developer-focused resume orchestrator that converts structured Markdown into a professional, one-page A4 PDF. Unlike standard converters, ArchitectMD preserves clickable hyperlinks and enforces strict industry-standard typesetting constraints to ensure your resume remains high-impact and concise.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)
![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)

## 🚀 Purpose
Modern recruitment often requires resumes to be one page in length and digitally optimized. Standard PDF exporters often result in blurry text or lose hyperlink metadata. ArchitectMD solves this by:
- **Enforcing A4 Constraints:** A strict 210mm x 297mm layout prevents "page bleed" and ensures professional formatting.
- **Metadata Preservation:** All links (GitHub, LinkedIn, Portfolios) remain fully clickable in the exported PDF.
- **Developer-Centric UX:** A real-time, split-pane editor with Dark Mode and resizable gutters designed for a seamless coding workflow.

## ✨ Key Features
- **Live Preview:** Instant synchronization between the Markdown editor and the rendered A4 page.
- **Smart Syntax Parser:** Automatically detects headers, professional experience alignments (using pipes), and stylized section underlines.
- **Glassmorphism UI:** A sleek, modern interface with support for Day/Night themes.
- **High-Resolution Export:** Utilizes high-scale rendering to ensure text remains crisp even on high-DPI displays.
- **Privacy First:** 100% browser-based processing. Your data never leaves your machine.

## 🛠️ Tech Stack
- **Frontend:** HTML5, Tailwind CSS (Custom Dark Mode Configuration).
- **Libraries:** [html2pdf.js](https://rawgit.com/eKoopmans/html2pdf/master/dist/html2pdf.bundle.min.js) for link preservation and A4 scaling.
- **Icons:** FontAwesome 6.4.0.
- **Typography:** Inter & JetBrains Mono (via Google Fonts).

## 📖 Usage Guide & Syntax

The engine uses a specialized "Smart Markdown" flavor to handle professional typesetting:

| Feature | Syntax | Result |
| :--- | :--- | :--- |
| **Name Header** | `# YOUR NAME` | Centered, bold header at the top. |
| **Section Titles** | `WORK EXPERIENCE` | ALL CAPS lines become underlined section headers. |
| **Experience Splits** | `Role \| Company \| Date` | Automatically aligns text to the left and right edges. |
| **Clickable Links** | `[Portfolio](URL)` | Creates blue, clickable hyperlinks in the PDF. |
| **Bullet Points** | `- Achievement` | Professional aligned bullet list. |
| **Emphasis** | `**Skill**` | Standard bolding for key terms. |

## 📦 Local Setup
Since the app is entirely self-contained in a single file, setup is instant:

1. Clone the repository:
   ```bash
   git clone https://github.com/adhikary-dipankar/LaTex2Pdf.git
   ```
2. Open `index.html` in any modern web browser (Chrome or Edge recommended for best PDF rendering).
3. Start architecting your resume.

## 🤝 Support
If you find this tool helpful, consider supporting the project to keep it open-source and free:
- **Give a ⭐** to the repository to help others find it.
- **Support via UPI:** Scan or use ID `dipu98adhikary-1@oksbi`.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Developed with ❤️ by [Dipankar Adhikary](https://github.com/adhikary-dipankar)*
