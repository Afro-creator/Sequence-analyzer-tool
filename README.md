# 🧬 Sequence Analyzer Tool

A simple Python-based bioinformatics tool for analyzing DNA sequences from FASTA files.

---

## 🚀 Features

* Reads DNA sequences from FASTA files
* Calculates:

  * Sequence length
  * GC content (%)
  * Reverse complement

---

## 📂 Project Structure

```
sequence-analyzer/
│── sequence_analyzer.py
│── sample.fasta
│── README.md
```

---

## ⚙️ Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/sequence-analyzer.git
cd sequence-analyzer
```

2. Ensure you have Python installed (Python 3.7+ recommended)

---

## ▶️ Usage

Run the script:

```
python sequence_analyzer.py
```

Enter the path to your FASTA file when prompted:

```
Enter path to FASTA file: sample.fasta
```

---

## 📊 Example Output

```
=== Sequence Analysis Results ===
Header: >Sample_DNA_Sequence
Length: 46 bp
GC Content: 50.0%
Reverse Complement:
TAGCTAGCTAGCTAGCTACGATCGATCGATCGTACTAGCTACGCAT
```

---

## 🧠 Concepts Covered

* FASTA file parsing
* DNA sequence manipulation
* GC content calculation
* Reverse complement logic

---

## 🔬 Future Improvements

* Support for multiple sequences in FASTA
* Visualization (GC plots)
* Translation to protein sequences
* CLI arguments instead of input()

---

## 👨‍💻 Author

Edwin Koech
Bioinformatics Enthusiast | Molecular Biology Graduate

---

## 📜 License

This project is open-source and available under the MIT License.
