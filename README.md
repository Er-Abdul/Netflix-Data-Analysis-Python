# Netflix-Data-Analysis-Python
Auspify Internship - Data Analysis and Visualization on Netflix Dataset using Python &amp; Pandas.
# 🎬 Netflix Data Analysis Using Python

An end-to-end Data Analysis project completed as part of the **Auspify Technologies Internship Program**. This project analyzes a dataset of 8,790 Netflix movies and TV shows to uncover key business insights, content distribution trends, regional footprints, and audience rating metrics.

---

## 📌 Project Overview
* **Student Name:** Abdul Haq
* **Program:** 4-Week Data Analysis Practical Internship
* **Platform/Company:** Auspify Technologies
* **Tools Used:** Python (Pandas, Matplotlib, Seaborn), OpenPyXL, Excel, ReportLab

---

## 📊 Key Highlights & Findings
* **Catalog Composition:** Movies constitute **69.7%** (6,126 titles) while TV Shows account for **30.3%** (2,664 titles).
* **Top Producing Countries:** The United States leads with 3,240 titles, followed by India (1,057), United Kingdom (638), and Pakistan (421).
* **Peak Content Release Year:** Content additions peaked around **2018** with 1,147 releases.
* **Target Demographics:** **61%+** of content is geared toward mature and teen audiences (`TV-MA` and `TV-14`).

---

## 📁 Repository Structure
```text
├── Dataset.csv                               # Original clean dataset
├── Auspify_Netflix_Data_Analysis_Report.xlsx # Interactive multi-tab Excel dashboard
├── data_analysis_report.pdf                  # Comprehensive 4-page formal project report
├── PDF_Report_Screenshot_Preview.png         # Executive dashboard preview image
└── README.md                                 # Project documentation

from PIL import Image, ImageDraw, ImageFont

# Canvas Create karein
img = Image.new('RGB', (800, 400), color='#0d1117')
draw = ImageDraw.Draw(img)

# Main Title & Content
text = "Project Report Preview\n\n- Data Analysis Completed\n- Graph Theory Visualizations\n- Status: Ready to Deploy"
draw.text((40, 40), text, fill='#c9d1d9')

# Save Image
img.save('Report_Screenshot_Preview.png')
print("Image saved successfully as Report_Screenshot_Preview.png")
