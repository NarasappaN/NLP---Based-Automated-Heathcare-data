📌Overview
This project is designed to automate the cleansing and preprocessing of healthcare datasets using Natural Language Processing (NLP) and data processing techniques. It ensures that missing values, inconsistent data, and medical abbreviations are handled effectively to improve data quality for further analysis and decision-making.


🎯 Features
-Automated Data Cleaning: Handles missing values, incorrect data entries, and duplicates.
-Medical Abbreviation Expansion: Uses NLP to replace abbreviations with their full medical terms.
-Date of Birth & Age Fixing: Corrects missing or inconsistent age and DOB values.
-Doctor-Disease Mapping: Assigns diagnosis codes based on doctor specializations.
-Expense Anomaly Handling: Fixes incorrect or missing expense values.
-BLEU Score Calculation: Evaluates abbreviation expansion accuracy using NLP.
-Streamlit UI: Provides an easy-to-use interface for file uploads and cleansed data download.

🛠️ Requirements
Ensure you have the following dependencies installed:
"pip install pandas numpy streamlit nltk openpyxl fpdf matplotlib seaborn"

🚀 How to Run
1. Clone the Repository:
2. Run the Streamlit Application:
   "streamlit run home.py"
3. Upload a Healthcare Dataset: Ensure your dataset is in Excel format (.xlsx).
4. Download the Cleaned Data: Once the process is complete, download the cleansed file.

🤝 Contributing
Feel free to contribute by submitting pull requests or raising issues.

Happy coding! 🚀

   
