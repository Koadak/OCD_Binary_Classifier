## ⚙️ Getting Started

1. **Install dependencies**  
   Run the following command in your terminal:
   ```bash
   pip install -r requirements.txt
   ```
   If there is an error requiring the install of Rust and Cargo, please run the following command:
   ```bash
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
   ```
   You might want to delete this from your PATH variables after running the code

2. **Place the scan folders**  
   - Move `Methodology1_Scans` into the `Methodology #1` directory.
   - Move `Methodology2_Scans` into the `Methodology #2` directory.  
   
   > Both folders are available in the Canvas assignment titled **“Week 13: Final Report and Presentation”**
   >Note:This project uses python 3.10

---

## 🚀 Running the Code

### 🔹 Methodology #1

1. Navigate to the `Methodology #1` directory.
2. Run the following scripts in order:
3. Note: You do not have to run these commands, they are here to let you know which files to run

   ```bash
   python 'Methodology #1/Visiontransformer.py'
   python 'Methodology #1/XGBoost_ML.py'
   ```

### 🔹 Methodology #2

1. Navigate to the `Methodology #2` directory.
2. Run the following scripts in sequence:
   ```bash
   python 'Methodology #2/Create_FC_Dataset.py'
   python 'Methodology #2/FC_NN_Stage1.py'
   python 'Methodology #2/FC_NN_Stage2.py'
   ```

---

## 📁 Folder Structure

```
OCD_Classification_Project/
│
├── Methodology #1/
│   ├── Methodology1_Scans/
│   ├── Visiontransformer.py
│   └── XGBoost_ML.py
│
├── Methodology #2/
│   ├── Methodology2_Scans/
│   ├── Create_FC_Dataset.py
│   ├── FC_NN_Stage1.py
│   └── FC_NN_Stage2.py
│
└── requirements.txt
```

---

## 🧠 Project Overview

This project implements two distinct pipelines for classifying OCD patients based on neuroimaging data:

- **Methodology #1**: Image-based classification using Vision Transformers and XGBoost.
- **Methodology #2**: Functional connectivity matrix construction followed by a two-stage neural network classifier.

---

## 📬 Contact

For questions or collaboration inquiries, please reach out via Canvas or email.
