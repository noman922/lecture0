🧬 Sperm Quality Assessment Simulator (Python Tool)
This project is a Python-based simulation tool that evaluates sperm-quality indicators such as concentration, motility, and morphology, based on WHO-referenced thresholds and weighted scoring.
It can generate assessment reports, classify fertility potential, visualize scores using charts, and store results for users.

⚠️ Disclaimer:
This tool is for educational and simulation purposes only. It does not provide medical advice or clinical diagnosis. Always consult a qualified healthcare professional for real medical evaluations.

📌 Features
✔️ Validates input ranges for realistic values
✔️ Calculates sperm quality scores with small random variability (to simulate lab measurement error)
✔️ Uses WHO 2021 semen-analysis thresholds
✔️ Generates a complete printable text report
✔️ Offers optional visualization via matplotlib
✔️ Supports random sample generation
✔️ Saves test results to a local file
✔️ Maintains session history
✔️ Clean modular code for easy modification

🛠️ Tech Stack
Python 3.8+

matplotlib — for visualization

random — for variability

os — file handling

📥 Installation
1. Clone this repository
bash
Copy code
git clone https://github.com/noman922/lecture0/blob/master/Sperms%20Quality%20Test
cd sperm-quality-tester
2. Install dependencies
bash
Copy code
pip install matplotlib
▶️ Usage
Run the main script:

bash
Copy code
python sperm_quality_tester.py
After launching, the tool provides an interactive menu:

powershell
Copy code
1) Enter data  
2) Generate random sample  
3) View history  
4) Exit
You will be asked to enter:

Concentration (million/mL)

Motility (%)

Morphology (%)

You can also choose to display a bar-chart visualization.

📊 Example Output
yaml
Copy code
Sperm Quality Assessment Report:
- Concentration: 32.5 million/mL (Score: 100.0/100)
- Motility: 45.2% (Score: 88.1/100)
- Morphology: 6.2% (Score: 100.0/100)
- Overall Quality Score: 94.1/100
- Fertility Potential: High (Excellent chance of fertility)
- Thresholds Used: Conc >15, Mot >40, Morph >4
📁 Saving Reports
Reports can be stored in:

Copy code
sperm_report.txt
Each new report is appended automatically.

📦 Project Structure
cpp
Copy code
│── sperm_quality_tester.py
│── README.md
└── sperm_report.txt (auto-created)
⚠️ Medical Disclaimer (Important)
This project is intended for educational, research, and data-simulation purposes only.
It does not replace laboratory analysis, fertility testing, or medical consultation.

If you have concerns about fertility or reproductive health, always consult a licensed medical professional.

🤝 Contributing
Contributions are welcome!

Fork the repository

Create a new branch

Commit your improvements

Open a pull request

📜 License
You may choose any license you prefer (MIT suggested):

yaml
Copy code
MIT License © 2025 Your Name Noman Ali
