# 🧬 Sequence Translator Using Python

A simple Python-based bioinformatics tool for translating **DNA nucleotide sequences into protein sequences** using the standard genetic code.

This project demonstrates a fundamental concept in bioinformatics: converting nucleotide information into its corresponding amino-acid sequence through **codon-to-amino-acid translation**.

## 🔬 Project Overview

DNA sequences contain genetic information encoded as nucleotides:

**A — Adenine**
**T — Thymine**
**G — Guanine**
**C — Cytosine**

During translation, the DNA sequence is read in groups of three nucleotides called **codons**. Each codon corresponds to an amino acid according to the genetic code.

For example:

```text
DNA:
ATG GCT TTT GAA TAA

Protein:
M   A   F   E   *
```

Here:

* `ATG` → Methionine (M)
* `GCT` → Alanine (A)
* `TTT` → Phenylalanine (F)
* `GAA` → Glutamic acid (E)
* `TAA` → Stop codon (`*`)

## 🎯 Objectives

The main objectives of this project are to:

* Translate DNA sequences into protein sequences
* Understand codon-based genetic translation
* Implement a genetic code table in Python
* Practice string manipulation and biological sequence processing
* Demonstrate a fundamental bioinformatics workflow using Python

## ⚙️ How It Works

The program follows these basic steps:

```text
DNA Sequence
     ↓
Validate / Process Sequence
     ↓
Split into Codons
     ↓
Codon Lookup
     ↓
Amino Acid Sequence
     ↓
Protein Sequence
```

### Translation Process

1. Accept a DNA sequence as input.
2. Process the nucleotide sequence in groups of three.
3. Match each codon with its corresponding amino acid.
4. Build the resulting protein sequence.
5. Return the translated protein sequence.

## 💻 Technologies

* **Python 3**
* String manipulation
* Dictionaries
* Functions
* Genetic code / codon table
* Basic bioinformatics concepts

## 📁 Repository Structure

```text
Sequence-Translator-Using-Python/
│
├── Sequence Translator using Python.py
├── code.py
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Bioinformatician-dev/Sequence-Translator-Using-Python.git
```

### 2. Navigate to the project

```bash
cd Sequence-Translator-Using-Python
```

### 3. Run the Python script

```bash
python "Sequence Translator using Python.py"
```

or:

```bash
python code.py
```

## 🧪 Example

### Input

```text
ATGGCTTTTGAATAA
```

### Translation

```text
MAFE*
```

The `*` represents a stop codon.

## 🧬 Biological Background

Protein synthesis involves two major stages:

```text
DNA
 ↓
Transcription
 ↓
mRNA
 ↓
Translation
 ↓
Protein
```

In this project, the focus is on the **translation step**, where nucleotide codons are mapped to amino acids according to the genetic code.

The standard genetic code contains **64 codons**:

* 61 codons encode amino acids
* 3 codons function as stop signals
* `ATG` commonly serves as the start codon and encodes methionine

## 📚 Learning Outcomes

Through this project, you can learn how to:

* Represent biological sequences using Python
* Work with DNA nucleotide strings
* Create and use codon dictionaries
* Implement biological sequence translation
* Convert a biological concept into a computational algorithm
* Build foundational Python skills for bioinformatics

## 🔮 Future Improvements

Possible extensions include:

* [ ] Add DNA sequence validation
* [ ] Support RNA sequences (`U` instead of `T`)
* [ ] Add reverse-complement translation
* [ ] Translate all six reading frames
* [ ] Detect start and stop codons automatically
* [ ] Add FASTA file input
* [ ] Support multiple sequences
* [ ] Add amino-acid three-letter codes
* [ ] Create a command-line interface
* [ ] Add unit tests
* [ ] Build a Streamlit web interface
* [ ] Add sequence visualization

## 👩‍💻 Author

**Bioinformatician-dev**

Exploring the intersection of **biology, programming, bioinformatics, and computational research**.

🔗 GitHub: https://github.com/Bioinformatician-dev

---

⭐ If you find this project useful for learning Python or bioinformatics, consider starring the repository.

**Discover • Code • Analyze 🧬**
