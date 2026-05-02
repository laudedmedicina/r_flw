# 🧠 R Analysis Studio

A modern, interactive, step-by-step interface for learning and performing statistical analysis in **R** — designed for clarity, speed, and professional workflows.

---

## ✨ Overview

**R Analysis Studio** is a lightweight web-based UI that guides users through the full data analysis pipeline:

* Data loading
* Data inspection
* Missing value handling
* Descriptive statistics
* Statistical testing
* Correlation analysis
* Visualization (ggplot-style thinking)
* Regression modeling
* Post-hoc analysis & effect size
* Export & reproducibility

It combines **code + interpretation + visual guidance** in a single streamlined interface.

---

## 🚀 Features

### 📊 Guided Workflow

* 10 structured steps covering the full analysis lifecycle
* Progress tracking and navigation system
* Smart step-based recommendations

### 💡 Smart Tips Panel

* Context-aware suggestions:

  * Graph selection
  * Statistical tests
  * Data handling strategies

### 🧪 Built-in Statistical Logic

* Parametric vs non-parametric guidance
* Test selection table
* Assumption checks integrated into workflow

### 🎨 Professional UI

* Dark-mode optimized
* Minimalist academic design
* Typography tuned for readability
* Smooth transitions and clean layout

### 📈 Visual Components

* Correlation heatmap (custom SVG)
* Scatter plots with grouping
* Metrics cards
* Decision tables

### 📦 Reproducibility Focus

* Encourages:

  * `set.seed()`
  * `renv`
  * Export pipelines
  * Session logging

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3 (custom variables + modern layout)**
* **Vanilla JavaScript**
* No external frameworks (fully lightweight)

---

## 📂 Project Structure

```
r-analysis-studio/
│
├── index.html        # Main application file
├── README.md         # Project documentation
└── assets/           # (optional future expansion)
```

---

## ⚙️ Installation & Usage

### 1. Clone the repository

```bash
git clone https://github.com/your-username/r-analysis-studio.git
cd r-analysis-studio
```

### 2. Run locally

Simply open:

```
index.html
```

in your browser.

No dependencies required.

---

## 🧠 Intended Audience

* Medical students
* Researchers
* Data analysts
* R beginners → intermediate users
* Anyone needing **structured statistical workflows**

---

## 📌 Example Workflow

1. Load dataset (`read.csv`, `read_excel`)
2. Inspect structure (`str`, `summary`)
3. Handle missing values (`naniar`, `na.omit`)
4. Run descriptive stats
5. Choose correct statistical test
6. Visualize relationships
7. Build regression model
8. Interpret results
9. Run post-hoc tests
10. Export reproducible outputs

---

## 🎯 Design Philosophy

* **Clarity over complexity**
* **Guided learning over raw tooling**
* **Professional aesthetics**
* **Zero friction setup**

---

## 🔧 Customization

You can easily modify:

* Color system → `:root` CSS variables
* Fonts → Google Fonts import
* Steps → `STEPS` array in JavaScript
* Visualizations → SVG generators

---

## ⚠️ Known Limitations

* Static (no backend/data persistence yet)
* Uses demo dataset (`mtcars`)
* No real-time R execution (UI only)

---

## 🚀 Future Improvements

* Live R execution (via API / WebAssembly)
* Dataset upload support
* Export to PDF / reports
* Advanced statistical modules
* User state persistence
* Mobile optimization

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repo
2. Create a feature branch
3. Submit a pull request

---

## 📄 License

MIT License — free to use and modify.

---

## 👨‍⚕️ Author

**Muhammad M. Elsharkawy**

---

