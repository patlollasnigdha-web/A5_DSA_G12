# Intelligent Plagiarism Detector

A Java-based **Intelligent Plagiarism Detection System** that analyzes documents and identifies matching or similar text using efficient **Data Structures and Algorithms**.

## 📌 Overview

The Intelligent Plagiarism Detector compares text from documents and detects possible plagiarism by preprocessing the content and applying string-matching algorithms.

The project demonstrates how DSA concepts can be used to build a practical text-analysis application with efficient searching and comparison.

## ✨ Features

* 📄 Document/text file reading
* 🧹 Text preprocessing and normalization
* 🔍 Pattern matching
* ⚡ KMP (Knuth-Morris-Pratt) string matching
* 🔎 Naive string matching
* 📊 Match detection and comparison
* 🖥️ Java-based backend server
* 🌐 Web-based interface for uploading and checking documents
* 📈 Plagiarism percentage/result display

## 🧠 Algorithms Used

### 1. Naive String Matching

The Naive algorithm checks a pattern against every possible position in the text.

**Time Complexity:**

* Best/Average: `O(n)`
* Worst: `O(n × m)`

### 2. KMP String Matching

The **Knuth-Morris-Pratt (KMP)** algorithm improves pattern searching by avoiding unnecessary comparisons using the **LPS (Longest Prefix Suffix)** array.

**Time Complexity:**

* Preprocessing: `O(m)`
* Searching: `O(n)`
* Overall: `O(n + m)`

Where:

* `n` = length of the text
* `m` = length of the pattern

## 🏗️ Project Structure

```text
DSA-PROJECT/
│
├── src/
│   └── main/
│       ├── Main.java
│       ├── Server.java
│       ├── DocumentReader.java
│       ├── TextPreprocessor.java
│       ├── NaiveMatcher.java
│       └── KMPMatcher.java
│
├── data/
│   ├── documents/
│   └── results/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── app.jsx
│
└── README.md
```

## ⚙️ Technologies Used

| Technology         | Purpose                        |
| ------------------ | ------------------------------ |
| Java               | Backend and DSA implementation |
| HTML               | Webpage structure              |
| CSS                | User interface styling         |
| JavaScript / React | Frontend interaction           |
| KMP                | Efficient pattern matching     |
| Naive Matching     | Basic pattern comparison       |
| File I/O           | Document processing            |

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd DSA-PROJECT
```

### 2. Compile the Java Backend

```bash
javac src/main/*.java
```

### 3. Start the Server

```bash
java -cp src/main Server
```

The backend server will start and handle document-processing requests.

### 4. Open the Frontend

Open the frontend `index.html` in your browser or run it through a local development server.

## 🔄 Working Flow

```text
Upload Documents
       ↓
Read Document Content
       ↓
Text Preprocessing
       ↓
Tokenization / Normalization
       ↓
Pattern Matching
       ↓
Naive + KMP Algorithms
       ↓
Compare Matching Content
       ↓
Calculate Similarity
       ↓
Display Plagiarism Result
```

## 📊 Expected Output

The system provides:

* Number of matching patterns
* Matching text/content
* Similarity information
* Plagiarism detection result
* Comparison between submitted documents

## 🎯 DSA Concepts Demonstrated

This project applies several core DSA concepts:

* Strings
* Arrays
* File handling
* Pattern matching
* Prefix/LPS arrays
* Algorithmic complexity
* Searching techniques
* Modular programming

## 🔮 Future Enhancements

* Support for PDF and DOCX files
* Advanced similarity algorithms
* Sentence-level plagiarism detection
* Highlighting of matching text
* Multiple-document comparison
* Improved similarity scoring
* Database integration
* Authentication and user history

## 👩‍💻 Team

**Snigdha Patlolla**
**Shravya**

## 📚 Academic Project

This project was developed as part of a **Data Structures and Algorithms (DSA)** project to demonstrate the practical application of string-processing and pattern-matching algorithms.

---

⭐ **Intelligent Plagiarism Detector — Detect. Compare. Analyze.**
